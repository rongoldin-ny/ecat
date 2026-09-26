# Changelog

Each push to `main` gets a new version (v0.1, v0.2, …). The version is shown in the bottom-right corner of the app, and each release has a matching git tag.

## v0.4
- The translations are now what the person is saying *to* their cat, like "Hey cat." or "Can I get you a fish?". There are 1,320 new phrases.
- Better at catching the pause between meows. Low frequencies are filtered out before measuring, so the humming "m" at the start of each meow shows up as a clear dip.
- More natural voice: it prefers the phone's Enhanced or Premium voices, uses normal pitch and speed, and says stretched words like "Pleeease" normally.
- `?debug` now also shows which voice was picked.

## v0.3
- Mute button in the top-right corner turns off the spoken translation. The setting is remembered on the phone.
- Long meow lists and long translations no longer overlap on the result screen. The wave shrinks and the text gets smaller when needed.

## v0.2
- Meows said back to back are now counted separately. The detector uses the drop in volume at each "m" instead of waiting for silence.
- Long vs. short meows: each is written out according to its length ("Mew", "Meow", "Meooooow"). Mostly long meows get a more dramatic translation.
- 1,320 phrases in `phrases.js`: 110 normal and 110 dramatic for each count from 1 to 6+. A phrase doesn't repeat until all the others in its list have been used.
- Cat home-screen icon and favicon.
- `?debug` view that shows live sound levels.

## v0.1
- First prototype: pink sound wave, mic listening, meow counting, cat spinner, translations and speech.
