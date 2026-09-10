# AAC Access Systems v0.79

AAC Access Systems is a standalone HTML teaching app for comparing AAC access methods, selection techniques, layout choices, and specialized AAC interface architectures.

## Version focus

v0.79 improves live classroom use when larger interfaces are displayed. The current test sentence and produced output are now anchored immediately above the active keyboard/interface, and the maximum-efficiency simulation buttons now use the same visible playback pathway.

## Changes from v0.78

- Moved the live **Test** sentence and **Output** display from the separate upper run-control bar into the production pane directly above the active interface.
- Made the Test/Output strip sticky within the production pane so it remains visible while larger interfaces, including 6×6 keyboards, are used or scrolled.
- Changed **Run selected machines** so clicking it performs the same visible optimal-path playback as **Simulate selected interface**.
- Preserved automatic comparison-table refresh when task, target, or selected systems change.
- Carried forward the v0.78 changes for three-switch scanning and vocabulary-set scanning.

## Included files

- `AAC_Access_Systems_v0_79.html` — standalone app file.
- `index.html` — duplicate app file for simple hosting.
- `aac_statistical_prediction_corpus_v0_79.csv` — exported 1,500-string language-model corpus.
- `aac_statistical_prediction_corpus_v0_79.json` — corpus and model metadata.
- `icon_sequencing_dictionary_v0_79.csv` — icon-sequencing dictionary export.
- `CURRENT_UPDATES_AAC_Access_Systems_v0_79.md` — current update notes.

## Running the app

Open `index.html` or `AAC_Access_Systems_v0_79.html` in a modern browser. For classroom distribution, upload the package contents to a web host or GitHub Pages and open `index.html`.
