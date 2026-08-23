# AAC Access Systems v0.77 Current Updates

## v0.77 explicit space controls

This release adds clearer manual spacing controls to the statistical word-prediction and ambiguous 8-key disambiguation interfaces.

### Changes

- Added an explicit **Space** button to the Statistical word prediction interface.
- Added an explicit large **Space** button to the Ambiguous 8-key keyboard interface.
- Enlarged the Ambiguous keyboard **Clear sequence** control.
- Preserved statistical next-word prediction and prefix-completion behavior.
- Preserved ambiguous-key statistical candidate filtering and ranking.

### Validation

- JavaScript syntax validated with `node --check`.
- Headless browser simulation completed with no page initialization errors.
- Confirmed word-prediction Practice mode includes the new Space button and that it inserts a space.
- Confirmed word-prediction prefix completion still displays predictions after typing `he`.
- Confirmed Ambiguous keyboard Practice mode includes enlarged Clear sequence and Space controls.
- Confirmed Ambiguous keyboard Space inserts a space.
- Confirmed Ambiguous keyboard Clear sequence clears typed telephone-key digits without changing output.
