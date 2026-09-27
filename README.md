# SprintFlow

A priority task planner with a built-in focus timer — built for **Hack Atlantic**.

Ranks your to-dos by urgency vs. time remaining, so you always know what to tackle next under a deadline.

## Live Demo

Open [`sprintflow.html`](./sprintflow.html) directly in any browser — no build step, no install, no dependencies.

## Features

- Add tasks with an estimated time and urgency level
- Automatic priority ranking (urgency weighted against time remaining)
- Built-in focus countdown timer per task
- Live countdown to your deadline
- Tasks persist locally in the browser (no backend needed)

## Built With

- HTML
- CSS
- JavaScript (vanilla, no frameworks)
- Claude (AI-assisted development)

## How It Works

Each task gets a priority score based on its urgency level and estimated time — shorter, more urgent tasks rank higher, so quick wins surface first when time is tight. Tasks are re-ranked automatically as you add or remove them.

## Running Locally

No setup required — clone the repo and open `sprintflow.html` in any modern browser.

```bash
git clone https://github.com/<your-username>/sprintflow.git
cd sprintflow
open sprintflow.html
```
