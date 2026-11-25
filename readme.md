# 🎬 Urban Air Quality Assistant: Video Demo (v2)

A narrated, self-running demo page with **Start** and **Stop** buttons. It explains the app's description, v2 features, testing, architecture, roles and responsibilities, and Gen AI disclosure.

**Live demo:** `https://<your-github-username>.github.io/<repo-name>/`
**App repository:** https://github.com/GundluruRajasekhar/airquality-assistant
**Author:** Gundluru Rajasekhar

## ▶ How to Use
1. Open `index.html`.
2. Press **▶ Start**. Scenes play automatically with voice and captions.
3. Press **■ Stop** at any time to end and reset.
4. Untick **Voice narration** for a silent, caption-only run.

## 🎥 How to Record the Video Submission
1. Open the page in a full browser window (use a desktop browser so voices are available).
2. Start your screen recorder (Windows: Win+G, Mac: Shift+Cmd+5, or OBS) and capture the browser tab with system audio.
3. Press **Start**. Stop recording when the "Future Scope and Thank You" scene ends (about 3 to 4 minutes).
4. Upload the video (YouTube unlisted or Google Drive with public view access) and paste the link in your submission.

To use your own voice instead, untick **Voice narration**, record your microphone, and read the script below.

## 🧱 Files
```
├── index.html        # Demo page (Start/Stop, narration, captions, 11 scenes)
├── requirements.md   # Requirements and acceptance criteria
├── readme.md         # This file, including the full script
└── tasks.md          # Task plan and test checklist
```

## 📜 Full Video Script (11 scenes, about 3 to 4 minutes)

**Scene 1: Urban Air Quality Assistant**
"Hello, and welcome. This is the Urban Air Quality Assistant, version two. It turns an AQI reading into a clear category, personalised health advice, and a trend you can track."

**Scene 2: The Problem**
"City residents see an AQI number every day, but few know what it means for their health. Children, older adults, and people with asthma or heart conditions need clear, specific guidance quickly."

**Scene 3: The Solution**
"The assistant is a rule-based web app that runs entirely in your browser. It follows the standard six-level AQI scale from zero to five hundred, and adapts its advice to the person it is for."

**Scene 4: Live Demo** *(screen types 135, then 340)*
"Here is a live example. I enter one hundred thirty five. The app shows Unhealthy for Sensitive Groups, moves the gauge, and, for children, adds a tip to limit outdoor play. Now I enter three hundred forty. The category becomes Hazardous and an emergency pollution alert appears. Invalid values, such as six hundred, show a clear error instead."

**Scene 5: Key Features**
"Version two adds many features. A trend chart with statistics. A comparison of places. Export to CSV and a downloadable report. Health and emergency alerts. Voice guidance that reads the result aloud. And a light and dark theme that remembers your choice."

**Scene 6: Built-in Testing**
"Quality is built in. A Run self-tests button executes twenty automated checks in the browser, covering every category, the boundary values, invalid input, audience advice, and spreadsheet safety. Results are shown as text, so they never depend on colour alone."

**Scene 7: Architecture**
"The code is organised into six modules. The AQI module holds the pure logic. Store manages local data and exports. The accessibility module handles errors, focus, theme, and voice. Charts draws the trend line. The UI module renders the page. And Tests verifies the logic automatically."

**Scene 8: Accessibility, Security, Privacy**
"Accessibility is built in, with labels, a skip link, announced errors, full keyboard use, and text labels alongside colour. For security, the app writes text safely, limits input, and neutralises formulas in exports. It makes no network calls, so your data never leaves your device."

**Scene 9: Roles and Responsibilities**
"Now the roles and responsibilities. The Product Owner defines the problem and acceptance criteria. The Full Stack Developer builds the logic, validation, history, and deployment. The UI and Accessibility Lead designs layout, contrast, and screen reader support. The QA Tester runs the self-tests and the manual checklist. The Security and Privacy Officer ensures safe input handling. And Documentation and DevOps maintains the readme and publishes the app."

**Scene 10: Gen AI Disclosure**
"A note on Gen AI. Claude, by Anthropic, was used as a coding and documentation assistant during development. The running application itself uses no Gen AI service. All advice comes from predefined rules, and all output was reviewed, tested, and deployed by the developer."

**Scene 11: Future Scope and Thank You**
"Next steps include live AQI data, an installable offline app, and Telugu, Hindi, and English guidance. Thank you for watching. Please open the live link and try it yourself. The guidance is general information and not medical advice."

## 👥 Roles and Responsibilities
| Role | Responsibility |
|------|----------------|
| Product Owner | Problem, users, acceptance criteria |
| Full Stack Developer | Logic, validation, history, deployment |
| UI/UX and Accessibility Lead | Layout, contrast, focus, screen reader support |
| QA Tester | Self-tests and 13-step manual checklist |
| Security and Privacy Officer | Safe input handling; no data leaves the device |
| Documentation and DevOps | README, requirements, tasks, GitHub Pages |

## 🚀 Deploy to GitHub Pages
1. Upload the four files to the root of a public repository (or a `video-demo` folder in your app repository).
2. Settings → Pages → Source: `main` branch, `/ (root)` → Save.
3. Share the link `https://<username>.github.io/<repo-name>/` (add `/video-demo/` if it is in a folder).

## ♿ Accessibility and Security
Skip link, labelled controls, live captions for all narration, visible focus, reduced-motion support, text rendered with `textContent` only, no external scripts or network calls.

## ⚠️ Browser Note
Voice narration uses the browser's built-in Speech Synthesis, and voices differ by device. If no voice is available, the demo runs from captions on a timer.

## 🤖 Gen AI Disclosure
Claude (Anthropic) assisted with code, debugging, and documentation. The deployed app and this demo page use no Gen AI API.
