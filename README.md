# 🕒 Pomodoro Timer | Python CLI

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

## 📌 Project Overview

A lightweight command-line **Pomodoro Timer** built in **Python**, designed to manage deep-work and rest intervals directly in the console with audio alerts between sessions.

This project demonstrates clean loop control, real-time countdown formatting, and native system audio feedback using Python's standard library.

## 🛠️ Tech Stack & Workflow Architecture

- **Language:** Python 3 (Standard Library — zero external dependencies).
- **Time Management (`time`):** Real-time second-by-second countdown logic and interval scheduling.
- **Audio Alerts (`winsound`):** Native Windows frequency-based sound notifications for session transitions.

```text
[ 25-Min Work Session ] ──► [ Audio Alert (winsound) ] ──► [ 5-Min Break Session ] ──► [ Repeat Cycle ]
```

## ✨ Key Features & Requirements
- ⏱️ Configurable Intervals: Standard 25-minute work sessions followed by 5-minute breaks.
- 🔊 Audio Notifications: Built-in acoustic alerts via winsound when switching between focus and rest states.
- 🖥️ Clean Console Display: Dynamic in-place countdown timer in the terminal.
- ⚠️ System Requirements: Python 3.x on Windows OS (required for the winsound module).

## 📁 Repository Structure
```text
├── pomodoro.py   # Main CLI timer script
└── README.md     # Project documentation
```

## 🚀 How to Run
1. Clone this repository to your local machine:
```bash
git clone https://github.com/renatosaldiviap/pomodoro-timer.git
```
2. Run the script from your terminal:
```bash
python pomodoro.py
```
3. Press Ctrl + C at any time to stop the timer cycle.
