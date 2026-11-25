# Requirements: Urban Air Quality Assistant Video Demo (v2)

## 1. Purpose
A narrated, self-running demo page that explains Urban Air Quality Assistant v2 (description, features, testing, architecture, roles and responsibilities, Gen AI disclosure) in about 3 to 4 minutes, so reviewers understand the project without installing anything. It is also the script and visual source for a recorded video submission.

## 2. Functional Requirements
| ID | Requirement | Priority |
|----|-------------|----------|
| FR-1 | **Start** begins the demo from scene 1 | Must |
| FR-2 | **Stop** immediately halts narration, animation, and timers and resets to the welcome screen | Must |
| FR-3 | Start is disabled while playing; Stop is disabled when idle | Must |
| FR-4 | 11 scenes advance automatically: Intro, Problem, Solution, Live Demo, Key Features, Built-in Testing, Architecture, Accessibility/Security/Privacy, Roles and Responsibilities, Gen AI Disclosure, Future Scope and Thank You | Must |
| FR-5 | Voice narration via browser Speech Synthesis, with a checkbox to turn it off | Must |
| FR-6 | Live captions for every scene | Must |
| FR-7 | Progress bar, scene dots, scene counter, elapsed timer | Should |
| FR-8 | Live demo scene types AQI 135 (tips shown), then 340 (Hazardous with emergency alert) | Should |
| FR-9 | Full script readable in an expandable section for voice-over recording | Should |
| FR-10 | If speech is unavailable, scenes advance on a timer from the caption length | Must |

## 3. Roles and Responsibilities Presented
| Role | Responsibility |
|------|----------------|
| Product Owner | Problem, users, acceptance criteria |
| Full Stack Developer | Logic, validation, history, deployment |
| UI/UX and Accessibility Lead | Layout, contrast, focus, screen reader support |
| QA Tester | Self-tests and 13-step manual checklist |
| Security and Privacy Officer | Safe input handling; no data leaves the device |
| Documentation and DevOps | README, requirements, tasks, GitHub Pages |

## 4. Non-Functional Requirements
| Area | Requirement |
|------|-------------|
| Accessibility | Skip link, labelled controls, `role="status"` and `aria-live` captions, visible focus, captions for all audio, reduced-motion support |
| Responsiveness | Works from 320px to desktop |
| Performance | Single file, no external requests or libraries |
| Security | All text rendered with `textContent`; no `innerHTML`; no third-party scripts |
| Reliability | Token-based cancellation leaves no stale timers or voices after Stop; safety timeout if speech never ends |
| Compatibility | Current Chrome, Edge, Firefox, Safari; light and dark mode |
| Honesty | Gen AI use is disclosed; the app itself uses no Gen AI service |

## 5. Acceptance Criteria
1. Start plays all scenes in order with captions and (if enabled) voice.
2. Stop at any moment silences audio, stops the timer, and shows the welcome screen.
3. Start works again after Stop or after the demo ends, with no overlapping voices.
4. With voice off, the full demo still plays on timed captions.
5. The live demo scene shows both the 135 and 340 examples before moving on.
6. Page works by double-clicking `index.html` and on GitHub Pages, with no console errors.

## 6. Out of Scope
Recorded video file, background music, multi-language narration (future).
