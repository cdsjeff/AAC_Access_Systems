# AAC Access Systems v0.81

AAC Access Systems is a standalone HTML teaching app for comparing AAC access methods, selection techniques, layout choices, and specialized AAC interface architectures.

## Version focus

v0.81 stabilizes keyboard geometry across screen sizes. Keyboard-style interfaces now preserve their intended row/column organization when the window changes size, with particular attention to QWERTY and larger 6×6 boards.

## Included files

- `AAC_Access_Systems_v0_81.html` — standalone app file.
- `index.html` — duplicate app file for simple hosting.
- `aac_statistical_prediction_corpus_v0_81.csv` — exported 1,500-string language-model corpus.
- `aac_statistical_prediction_corpus_v0_81.json` — corpus and model metadata.
- `icon_sequencing_dictionary_v0_81.csv` — icon-sequencing dictionary export.
- `CURRENT_UPDATES_AAC_Access_Systems_v0_81.md` — current update notes.

## Running the app

Open `index.html` or `AAC_Access_Systems_v0_81.html` in a modern browser. For classroom distribution, upload the package contents to a web host or GitHub Pages and open `index.html`.

## Recent revision history

- v0.81: Fixed keyboard geometry so layouts hold their intended shape across screen-size changes.
- v0.80: Added Backspace across keyboard-style interfaces and aligned ambiguous-keyboard student prediction with the maximum-efficiency simulation.
- v0.79: Repositioned the Test sentence and Output strip above the active interface and aligned Run selected machines with visible simulation playback.
- v0.78: Updated three-switch scanning to ArrowRight / ArrowDown / Space and enabled row-column and group-item scanning for vocabulary layouts.
