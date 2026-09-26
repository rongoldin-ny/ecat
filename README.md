# eCat Translator

A prototype that turns human "meows" into English. It is one file, `index.html`, and is built for iPhone Safari.

## How it works
- The app counts bursts of sound instead of recognising words. A new meow starts at the drop in volume on its "m", so meows said back to back still count separately.
- Each meow is written out according to how long it lasted: "Mew", "Meow", "Meooow" and so on.
- The number of meows picks a phrase from `phrases.js`. If at least half the meows were long, the phrase comes from a more dramatic list. The phone's built-in voice reads it aloud.
- `phrases.js` has 110 normal and 110 dramatic phrases for each count (1 to 6, where 6 means 6 or more). A phrase doesn't repeat until all the others in its list have been used.
- Add `?debug` to the URL to see live sound levels, which helps when tuning the detector on a phone.

## Demo on an iPhone
The iPhone only allows the mic on an `https://` page. The easiest way to get one:
1. On GitHub, go to **Settings → Pages**. Set the source to "Deploy from a branch" and pick `main`, folder `/ (root)`.
2. Open the Pages URL in Safari and tap **Turn on mic**, then **Allow**.
3. Turn off silent mode so you can hear the voice.

Tip: pause briefly between meows, since the pauses are how it counts them.

## Versions
Each push gets the next version (v0.1, v0.2, …). Update the version shown in `index.html` (`#version`), add an entry to `CHANGELOG.md`, and tag the commit (`git tag v0.X`).
