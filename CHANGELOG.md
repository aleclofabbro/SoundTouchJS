Changelog
### 0.1.17 (2020-04-01)

### 0.1.16 (2020-04-01)


### Bug Fixes

* action test step 12 ([8e09725](https://github.com/cutterbl/SoundTouchJS/commit/8e097257dd71d98b49f7a4aaeb409771bd65e1ac))

### 0.1.15 (2020-04-01)


### Bug Fixes

* action test step 11 ([a48aba2](https://github.com/cutterbl/SoundTouchJS/commit/a48aba209c2e0e35629bad5fb8a38b261a3457ee))

### 0.1.14 (2020-04-01)


### Bug Fixes

* action test step 11 ([e60a584](https://github.com/cutterbl/SoundTouchJS/commit/e60a58445f6a8aae4984e68d6ffde25403065765))

### 0.1.13 (2020-04-01)

### 0.1.12 (2020-04-01)

# Change Log

## 5 March, 2018

- Updated dependencies to resolve security issue with their dependencies
- Updated the 'example.js' to account for autoplay policy changes in Chrome. Big Thanks to Colin Hill for reporting it.

## 22 September, 2018

- Custom Event dispatch from the PitchShifter, to broadcast 'play' event
- Add `PitchShifter.on()` and `PitchShifter.off()` methods for registering and destroying event listener on audio node
- **Breaking Changes: ** change PitchShifter.sampleRate and PitchShifter.duration from functions to variables