# RLWM Task Code — Online Version

This repository contains the RLWM task code. Search for `REPLACE_ME` and modify those values for your own use.

The experiment is built on [jsPsych](https://www.jspsych.org/7.3/).

---

## Coding Assignment

### Exercise 0: Host on Your Own Computer

1. In your terminal, run:
   ```bash
   python3 -m http.server
   ```
2. Open your browser and go to: `http://localhost:8000/exp.html`
3. Open the developer console (`Cmd+Option+J` on macOS), set breakpoints, and step through the code to understand how it's built.

---

### Exercise 1: Host the Experiment on GitHub Pages

Follow the instructions here:
[L16 — Hosting on GitHub Pages](https://github.com/ccs-ucb/290Q/blob/main/assets/labs/L16-hosting-ghp/hosting-ghp.md)

---

### Exercise 2: Pull a URL Variable for the Sequence CSV

Instead of randomly picking a sequence CSV, modify the code to read the sequence number from a URL parameter so the stimulus sequence can be selected manually.

---

### Exercise 3: Add a Free-Text Survey

Add a free-text survey at the end of the experiment asking participants for any comments or feedback (use jspsych plugin `static/jspsych/jspsych-survey-text.js`).
