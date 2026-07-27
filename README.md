# Articull

> A minimalist, client-side web application engineered for impromptu speaking practice, speech structuring, and real-time audio playback assessment.

![Deployment](https://img.shields.io/badge/Deployment-GitHub%20Pages-success)
![Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen)

---

## Overview

**Articull** is designed to help speakers, presenters, and interview candidates build spontaneous fluency. By combining high-frequency 60-second speech drills, randomized topic generation, and real-time audio recording, the tool facilitates structured self-evaluation without friction.

Built with a strict zero-dependency philosophy, the entire application operates locally in the browser—ensuring instant load speeds, complete data privacy, and offline capability.

---

## Live Application

Access the production deployment on GitHub Pages:
👉 **[https://sneha-pixel7.github.io/articull/](https://sneha-pixel7.github.io/articull/)**

---

## Key Features

* **Precision Speech Timer:** 60-second drill enforcement built to train concise, high-impact verbal delivery.
* **Dynamic Topic Engine:** Instant generation of randomized prompts, with full support for custom topic injection.
* **Native MediaRecorder Integration:** Leverages the Web Audio / MediaRecorder API for instant playback and self-critique.
* **Structural Frameworks:** Integrated guidance templates (e.g., PREP, STAR) to structure off-the-cuff arguments.
* **Zero Overhead Architecture:** Single-file deployment running purely on standard Web APIs with no external npm packages or build steps.

---

## Technical Stack

| Domain | Implementation |
| :--- | :--- |
| **Markup & Layout** | Semantic HTML5, Responsive CSS3 (Flexbox/Grid) |
| **Logic & State** | Vanilla JavaScript (ES6+) |
| **Audio Processing** | Native Browser `MediaRecorder` API |
| **External Libraries** | None (0 dependencies) |

---

## Getting Started Locally

Because **Articull** requires no compilation or build tools, running it locally takes only a few seconds:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Sneha-pixel7/articull.git](https://github.com/Sneha-pixel7/articull.git)
