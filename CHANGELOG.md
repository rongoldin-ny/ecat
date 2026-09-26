# Changelog

Each push to `main` gets a new version (v0.1, v0.2, …). The version is shown in the bottom-right corner of the app, and each release has a matching git tag.

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
