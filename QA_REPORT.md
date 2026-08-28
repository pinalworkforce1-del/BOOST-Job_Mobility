# QA Report — BOOST Skill Mobility v0.9

Static/build validation completed before packaging. Interactive pilot testing in a normal browser is still recommended for audio timing, perceived pacing, and mobile UX.

| Check | Result | Detail |
|---|---|---|
| Scenario count | PASS | 24 scenarios |
| Four scenarios per RIASEC family | PASS | {'R': 4, 'I': 4, 'A': 4, 'S': 4, 'E': 4, 'C': 4} |
| Unique scenario IDs | PASS | 24 unique |
| Unique scenario images | PASS | 24 unique images |
| Unique scenario audio | PASS | 24 unique files |
| Unique reflection audio | PASS | 24 unique files |
| Custom reflections present | PASS | 24 custom prompts |
| Exactly one strongest answer per scenario | PASS | 24/24 |
| correct index matches strongest answer | PASS | 24/24 |
| No strongest answer is uniquely longest | PASS | none |
| Scenario assets exist | PASS | all present |
| WebP images decode | PASS | 34 valid |
| MP3 files probe | PASS | 63 valid |
| No duplicate HTML IDs | PASS | none |
| Expected stages present | PASS | welcome, setup, foundation, challengeIntro, challenge, resultsStage |
| Direct HTML asset references exist | PASS | all present |

## Change-control notes

- R2 uses the approved spill/safety rewrite and replacement `cs_scenario_r02.mp3`.
- I3 uses the approved “The Numbers Don’t Add Up” rewrite and replacement `cs_scenario_i03.mp3`.
- All other scenario narration files are retained from v0.8.
- All 24 custom Rosie reflection prompts and reflection MP3s are wired one-to-one.
- E3 received a wording-only distractor-length adjustment to remove the last unique “longest answer = strongest answer” cue; scenario logic and narration did not change.
- Scenario images were normalized to WebP for GitHub load performance.

## Pilot focus

- Verify narration ON/OFF behavior and no overlapping audio on desktop/mobile.
- Confirm each scenario image feels correct when encountered in randomized routing.
- Confirm Rosie reflection audio fires after response feedback and before preference selection.
- Confirm the six foundation cards feel useful without slowing the participant down.
- Test print / Save PDF from the final results screen.
- Gather pilot feedback before revisiting any accepted-for-pilot artwork (especially S4/C2 if needed).