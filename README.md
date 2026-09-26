# eCat Translator

A prototype that turns human "meows" into English. It is one file, `index.html`, and is built for iPhone Safari.

## How it works
- The app counts bursts of sound instead of recognising words. Each burst followed by a short pause counts as one meow.
- It shows each burst as a word: a short one is "Mew", a long one is "Meeeeow".
- The number of meows picks a random phrase from `PHRASES` in `index.html`, and the phone's built-in voice reads it aloud.

## Demo on an iPhone
The iPhone only allows the mic on an `https://` page. The easiest way to get one:
1. On GitHub, go to **Settings → Pages**. Set the source to "Deploy from a branch" and pick this branch, folder `/ (root)`.
2. Open the Pages URL in Safari and tap **Turn on mic**, then **Allow**.
3. Turn off silent mode so you can hear the voice.

Tip: pause briefly between meows, since the pauses are how it counts them.
