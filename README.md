# ⚡ React Speed — Human Reflex Tester
**VishwaNova 2026 · National Level Weboreel AI Hackathon**

*The average human reacts in 250ms. Are you average?*
A brutally minimal, psychologically tense reflex-testing experience where one flash of green separates the legends from the slow. Click too early and face the consequences.

---

## ✨ Features

**🟢 Psychological Tension Engine:** The wait delay is randomized between 1.5 and 5 seconds, deliberately preventing muscle-memory cheating. The screen holds you in a red "WAIT..." state, building anticipation — then detonates into full green without warning.

**🚨 False Start Punishment:** Clicking before the green flash triggers an immediate "JUMPED THE GUN!" state — the screen slams red, a harsh descending buzz fires from the Web Audio API, and the round is voided. No shortcuts allowed.

**📊 5-Round Rolling Average:** Each attempt logs its millisecond result to a live panel. After 5 rounds, a rolling average is calculated and displayed alongside a performance rating — Superhuman, Excellent, Average, or Slow — with color-coded feedback.

**🏅 Dynamic Rating System:** Results are graded in real time with labels that shift color and scale — sub-150ms earns a pulsing gold "SUPERHUMAN" badge while anything above 300ms gets a gently shamed "Keep Practicing" in muted red.

**🔊 Audio Feedback Pair:** The Web Audio API fires two distinct sounds — a sharp high sine burst on the green flash (the "GO" signal) and a satisfying low thud chime on a successful click, reinforcing the feedback loop physically through sound.

**📱 Full Touch Support:** The entire viewport is the click target — tap anywhere on desktop or mobile. No buttons to hunt for. Pure focus.

---

## 🛠️ Tech Stack

**HTML5** — Single full-viewport click surface, result panel structure.
**Vanilla CSS3** — Instant full-screen color transitions, scale animations on rating badges, scanline aesthetic overlay.
**Vanilla JavaScript** — `performance.now()` precision timing, randomized delay via `setTimeout`, rolling average calculation across attempt history.
**Web Audio API** — Synthesized "GO" signal tone and click-confirmation thud, false-start penalty buzz — all generated in real time, zero audio files.

---

## 📸 Try It Out

Simply double-click the `index.html` file to open it in any modern browser. No servers, build steps, or dependencies required.

---

*Built with ⚡ for VishwaNova 2026*
