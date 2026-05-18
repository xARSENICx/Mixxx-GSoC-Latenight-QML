# Long Term Goals

- Benchmark QML startup time with a single-hotcue button menu.
- **Blogpost**: Once the schedule is ready and project gets structured, finish blogpost work as discussed before the end of Week 3 (or Week1 of official coding phase).
- **Implementation Guide & Dependencies:** Proceed in this parallel/sequential structure:
  - First, start with the core decks.
  - Develop the toolbar (without applying changes to the deck yet).
  - Implement and reskin effects natively within the new QML UI.
  - Address Mini, Compact, and Full layouts later, once the main deck gets merged.
- **Sampler Deck:** Once all the above is done, derive the sampler deck architecture directly from the legacy implementation.
- **Preview Deck:** Deprecate/exclude the preview deck for the new QML UI, as it is no longer needed.
- **Settings Consolidation:** Completely transition away from the dual-settings approach and deprecate the legacy skin settings menu.
- **Menu Bar:** Implement a menubar based on rons0's works to enable native accesibility features.
- **Waveform setting**: In preferences, waveform page should be redesigned as `--new-ui` has it disabled (an end goal)
- **Continuous Optimization:** Keep project startup optimizations in mind throughout the entire development process.
- **CI/CD:** Setup/improve CI catching for QML if possible.
