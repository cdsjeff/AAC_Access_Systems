# AAC Access Systems v0.79 Current Updates

## v0.79 anchored test sentence + unified simulation

This release addresses two classroom-use issues in the student production and maximum-efficiency simulation panes.

### Changes

- Repositioned the live **Test** sentence and **Output** display so they sit directly above the active keyboard/interface.
- Added sticky positioning to that Test/Output strip within the production pane, keeping it visible when large interfaces such as 6×6 boards are used.
- Removed the Test/Output strip from the separate run-control bar so the sentence remains visually paired with the actual access interface.
- Changed the **Run selected machines** button so it launches the same visible optimal-path playback behavior as **Simulate selected interface**.
- Preserved internal recalculation of selected-machine comparison results when task, target text, layout set, or timing options change.

### Validation

- JavaScript syntax validated with `node --check`.
- Static DOM inspection confirmed `studentTargetView` now lives inside the production pane immediately before `studentInterface`.
- Static listener inspection confirmed `Run selected machines`, `Simulate selected interface`, and the top `Simulate` button all call the same `animateSelected` playback function.
- Version strings updated to v0.79.
