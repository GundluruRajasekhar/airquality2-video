# Tasks: Urban Air Quality Assistant Video Demo (v2)

Legend: ✅ done · ⬜ to do

## Phase 1: Planning
- ✅ T1. Define goal: explain v2 description, features, testing, architecture, and roles in 3 to 4 minutes
- ✅ T2. Write the 11-scene script (see `readme.md`)
- ✅ T3. Add a Gen AI disclosure scene that matches the submission form

## Phase 2: Build (`index.html`)
- ✅ T4. Start and Stop buttons with correct enabled/disabled states
- ✅ T5. Scene engine that advances automatically
- ✅ T6. Voice narration with on/off checkbox and pronunciation fixes
- ✅ T7. Timed fallback when speech is unavailable
- ✅ T8. Live captions, progress bar, scene dots, elapsed timer
- ✅ T9. Animated live demo: AQI 135 with tips, then AQI 340 with emergency alert
- ✅ T10. Expandable full script for voice-over recording
- ✅ T11. Token-based cancellation so Stop leaves no stale audio or timers

## Phase 3: Test Checklist
| # | Action | Expected |
|---|--------|----------|
| 1 | Open page | Welcome screen; Stop disabled |
| 2 | Click Start | Scene 1 plays; Start disabled, Stop enabled; timer runs |
| 3 | Let it run | All 11 scenes play in order, then "Demo finished" |
| 4 | Scene 4 | Types 135 and shows tips, then types 340 and shows the alert |
| 5 | Click Stop mid-scene | Voice stops at once, timer stops, welcome screen returns |
| 6 | Click Start after Stop | Plays from scene 1 with no overlapping voices |
| 7 | Untick Voice narration, Start | Full demo runs silently on timed captions |
| 8 | Keyboard only (Tab, Enter) | Both buttons reachable and operable, focus visible |
| 9 | Phone width (320px) | No sideways page scroll |
| 10 | Dark mode (system setting) | Text and buttons stay readable |
| 11 | Read the expandable script | Text matches the captions |

## Phase 4: Release and Recording
- ✅ T12. Prepare the four files
- ⬜ T13. Upload the four files to GitHub and enable GitHub Pages
- ⬜ T14. Open the live link and run the checklist above
- ⬜ T15. Screen-record the demo from Start to the Thank You scene
- ⬜ T16. Upload the video (YouTube unlisted or Drive with public view) and test the link
- ⬜ T17. Paste the live link and video link into the submission form
- ⬜ T18. Confirm the Gen AI disclosure on the form matches scene 10

## Phase 5: Future Enhancements
- ⬜ Telugu and Hindi narration
- ⬜ Pause and resume button
- ⬜ Background music toggle
