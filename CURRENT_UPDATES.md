# Current Updates


## v0.60 — universal speak button

- Reworked Speak / complete so it works across all configurations, including specialized stored utterances.
- The button now speaks the current text output through the browser speech-synthesis API when text output is available.
- Speak / complete now remains useful after an auto-completed stored phrase or stored utterance: it can still vocalize the output and mark the run as spoken/complete.
- Shape-sequence output is treated as a non-speech output mode and is still marked complete rather than spoken as symbols.
- JavaScript syntax validated.


## v0.59 — enlarged all text-keyboard characters

- Extended the enlarged QWERTY character styling to all text keyboard layouts.
- Alphabetic, frequency, and QWERTY keyboards now use the same large 4× character-label treatment.
- Shape-layout sizing remains separate and unchanged.
- JavaScript syntax validated.


## v0.58 — scan cursor auditory feedback

- Added a distinct scan-cursor tone when the scanning cursor enters a new row, group, prediction item, or keyboard item.
- Kept the accepted-selection tone separate from the scanning cursor tone.
- Scan focus movement now produces brief auditory feedback while scanning; accepted selections still produce the higher selection tone.
- The existing Sound on/off button controls both accepted-selection tones and scan cursor tones.
- JavaScript syntax validated.


## v0.57 — enlarged QWERTY key characters

- Increased QWERTY keyboard character glyphs by a factor of four.
- Applied the enlargement to QWERTY key labels while leaving the key geometry and square/constrained grid behavior intact.
- JavaScript syntax validated.

This file is intended to be appended with each revision of AAC Access Systems.

## v0.56 — auditory selection feedback

- Added auditory feedback across access methods.
- The app now plays a brief tone whenever a user selection is accepted.
- Feedback is triggered for direct selection, scanning row/item selection, step scanning selection, joystick selection, Morse switch input, ambiguous-key input, abbreviation/icon/core/phrase selections, and correction selections.
- Scan focus movement alone does not play a tone.
- Added a Sound on/off button beside the Active interface field.
- JavaScript syntax validated.

## v0.55 — compact output shape tokens

- Reduced the size of shape selections only in the Output field.
- Kept enlarged shape glyphs in the main shape-layout keyboard.
- Prevented output-field shape tokens from being vertically clipped.
- Added horizontal scrolling inside the Output field when longer shape sequences exceed the field width.
- JavaScript syntax validated.

## v0.54 — enlarged shape-layout glyphs

- Enlarged visible shape glyphs in shape layouts by approximately 4×.
- Applied enlargement to shape-layout grids and scanning/joystick shape rows.
- Kept square/constrained key-grid behavior intact.
- JavaScript syntax validated.

## v0.53 — clickable shape layout checkboxes

- Fixed the Selection Set / Layouts: shapes checkboxes so they remain clickable.
- Removed logic that disabled shape-layout checkboxes in text mode.
- Shape layouts can now be selected as part of the machine-set comparison.
- JavaScript syntax validated.

## v0.52 — text highlight toggle button

- Added a Highlight on/off button to the right of the Active interface field.
- The button toggles Test-field progress highlighting.
- Removed the prior Progress highlight checkbox from the dwell/direct options section.
- JavaScript syntax validated.

## v0.51 — compact access workspace help controls

- Moved Full screen into the Direct / pointer selection options section.
- Added a progress-highlight toggle.
- Changed Test sentence to Test and Output sentence to Output.
- Removed the visible Interface label.
- Moved interface instructions to a Help button.
- Reduced vertical spacing in the persistent Test/Output pane.
- JavaScript syntax validated.
