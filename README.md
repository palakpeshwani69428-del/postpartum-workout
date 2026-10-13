# 4-Week Postpartum Beginner Workout Plan

A gentle, evidence-informed **single-file web app** that guides new mothers through a structured four-week postpartum exercise progression — from breath and pelvic-floor reconnection to full-body strength.

Built as one self-contained `index.html`: no build step, no dependencies, no server. Open it in any browser and it just works.

---

## Overview

Postpartum recovery is not linear. This program is designed around that reality — each week builds on the last, with breath, core-canister awareness, and pelvic-floor safety guiding every movement.

The plan is organized into **4 progressive weeks**, each with **3 sessions** of roughly 15–35 minutes. Every exercise card includes sets/reps, a plain-language description, a coaching tip, and an embedded **YouTube video demonstration** that plays on hover (desktop) or tap (mobile).

| Week | Theme | Focus |
|------|-------|-------|
| 1 | 🌱 Reconnect & Breathe | Diaphragmatic breathing, pelvic-floor activation, gentle core connection |
| 2 | 🌿 Activate & Stabilize | Bird dog, glute bridges, modified planks, balance work |
| 3 | 🌸 Strengthen & Mobilize | Squats, side-lying work, upper-body rows, side planks |
| 4 | 🌼 Build & Progress | Reverse lunges, hip hinges, cardio intervals, full-body circuits |

---

## Features

- **Interactive week tabs** — switch between the four weeks instantly; the progress-journey dots double as quick navigation.
- **Exercise cards with full prescriptions** — each card has an exact dose (sets × reps / hold time), a detailed description, and a highlighted coaching tip.
- **Embedded video demonstrations** — privacy-friendly `youtube-nocookie.com` embeds. Hover to preview muted on desktop, tap to play on mobile, click to open the full video on YouTube.
- **Safety-first banner** — doctor clearance, diastasis recti awareness, pelvic-floor guidance, and a breastfeeding note, plus a prominent "stop immediately if…" checklist.
- **Fully responsive** — a fluid grid layout that adapts from wide desktop down to small phones.
- **Zero dependencies** — one HTML file with inline CSS and vanilla JavaScript. No frameworks, no bundler, and no external assets beyond the YouTube thumbnails.

---

## Usage

### View it locally
1. Download or clone the repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).

That's it — there is nothing to install and nothing to build.

### Publish it with GitHub Pages
1. Go to **Settings → Pages**.
2. Under **Source**, choose **Deploy from a branch**, then select the **`main`** branch and the **`/ (root)`** folder.
3. Save. The site goes live at:
   `https://palakpeshwani69428-del.github.io/postpartum-workout/`

### How to follow the program
- Begin with **Week 1, Session 1** and progress at your own pace.
- Aim for **3 sessions per week**, with rest days in between.
- Repeat a week if it still feels challenging — progression is not a race.
- Stop and consult your provider if you notice any of the warning signs listed in the safety banner.

---

## Safety Notes

> ⚠️ **This plan is for informational purposes only and is not a substitute for personalized medical advice.**

- **Get clearance first.** Obtain approval from your OB, midwife, or healthcare provider before starting — typically ~6 weeks after a vaginal birth and 8–12 weeks after a C-section.
- **Diastasis recti awareness.** Avoid traditional crunches, sit-ups, or any movement that causes abdominal "doming" or "coning." Prioritize deep-core breathing and gentle activation.
- **Pelvic floor.** If you feel leaking, heaviness, or pressure in your pelvis, stop and consult a pelvic floor physiotherapist.
- **Breastfeeding.** Relaxin remains elevated while breastfeeding, so joints are more mobile and injury-prone — avoid overstretching and prioritize stability.
- **Stop immediately and seek advice** if you experience: increased vaginal bleeding, pelvic pain or pressure, chest pain or shortness of breath, dizziness, urinary or bowel leakage, abdominal doming/coning, severe fatigue, or incision pain.

Always check in with a pelvic floor physiotherapist before progressing beyond this program.

---

## Tech

- **Single file:** `index.html` (inline CSS + vanilla JavaScript)
- **Styling:** hand-written CSS with custom properties, CSS grid, and a soft rose / lavender / sage palette
- **Media:** YouTube thumbnails (`img.youtube.com`) and `youtube-nocookie.com` embeds
- **Fonts:** system serif (`Georgia`) and sans-serif (`Arial`) stacks — no web-font downloads

## Attribution

Created as a personal wellness project. Video demonstrations are embedded from their original YouTube sources and linked to (not re-hosted). This page is not affiliated with the creators of those videos.
