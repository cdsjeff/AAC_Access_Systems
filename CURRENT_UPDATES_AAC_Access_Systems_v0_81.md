# AAC Access Systems v0.81 Current Updates

## v0.81 fixed keyboard geometry

This release stabilizes keyboard layout geometry so keyboard-style interfaces preserve their intended row/column organization as the browser window or screen size changes.

### Changes

- Reworked the direct keyboard rendering path to preserve original keyboard rows rather than relying on one flattened responsive grid.
- Reworked maximum-efficiency playback grid rendering to use the same row-preserving geometry.
- Added row-preserving keyboard wrappers so layouts such as QWERTY remain organized as their defined rows instead of visually collapsing or appearing as only a few oversized visible rows on large screens.
- Reduced the maximum keyboard height budget from the prior oversized scaling behavior so large layouts, including QWERTY and 6×6 boards, stay visually paired with the Test sentence and Output strip.
- Replaced CSS multiplication-based max-width behavior with JavaScript-computed viewport-width variables for stronger browser compatibility, including Safari/iPad contexts.
- Preserved v0.80 Backspace and ambiguous-keyboard parity changes.

### Validation

- JavaScript syntax validated with `node --check`.
- Confirmed app title and visible header identify v0.81.
- Confirmed QWERTY rendering now uses a row-preserving `keyMatrixRows` structure.
- Confirmed maximum-efficiency simulation rendering uses the same row-preserving structure.
- Confirmed exported corpus and icon-dictionary download filenames have been advanced to v0.81.
