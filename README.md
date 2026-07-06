# 🍅 Let's Pomodoro

A lightweight, browser-based Pomodoro timer to help you stay focused and manage your work/break sessions effectively.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Tech Stack](#tech-stack)
- [Contributing](#contributing)
- [License](#license)

---

## About

**Let's Pomodoro** is a simple, no-install Pomodoro timer built with vanilla HTML, CSS, and JavaScript. It follows the [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) — a time management method that alternates focused work sessions with short breaks.

---

## Features

- **Customizable durations** — set your own Pomodoro and Break lengths using `+`/`-` controls
- **Full timer controls** — Pause, Resume, Restart, and Stop at any time
- **Audio alert** — plays a repeating beep when a session completes, with a dismissible "Stop Alert" button
- **Confetti celebration** — festive confetti burst fires on session completion
- **Session tracking** — save completed sessions and view them listed below the timer
- **Test Mode** — toggle between seconds (for quick testing) and minutes (normal use)
- **Responsive design** — works on desktop and mobile browsers

---

## Demo

> Open `index.html` directly in your browser — no build step or server required.

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- No Node.js, package manager, or server needed

### Installation

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/PomodoroCounter.git
   ```
2. Open the project folder:
   ```bash
   cd PomodoroCounter
   ```
3. Open `index.html` in your browser:
   - Double-click the file, **or**
   - Drag it into an open browser window, **or**
   - Use a local server extension (e.g. VS Code Live Server)

---

## Usage

1. **Set the duration** — use `+` and `-` to choose how many minutes (or seconds in Test Mode) for your Pomodoro or Break.
2. **Start a session** — click **START** under either *Pomodoro* or *Break*.
3. **Control the timer** — use the Pause, Resume, Restart, and Stop buttons as needed.
4. **Dismiss the alert** — when the timer ends, click **🔔 Stop Alert** to silence the beep.
5. **Save sessions** — click **Save** to record the completed session(s) in the log below.
6. **Toggle Test Mode** — click the **Test Mode** button at the bottom to switch between seconds and minutes.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling & responsive layout |
| JavaScript (ES6+) | Timer logic, DOM manipulation |
| [canvas-confetti](https://github.com/catdad/canvas-confetti) | Celebration animation (CDN) |
| Web Audio API | Beep alert sound |

---

## Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please keep changes focused and include a clear description in your PR.

---

## License

This project is open source and available under the [MIT License](LICENSE).
