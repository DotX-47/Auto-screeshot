# Auto Screenshot Taker — README.md

> **IMPORTANT:** This tool is for **ethical, consent-based, and legal** uses only (usability testing, personal time-lapse, debugging on machines you own or have explicit permission to test). Do **not** use for stealthy surveillance or on other people's devices without written consent.

---

## Project overview

A simple, configurable Python utility that captures desktop screenshots at regular intervals and saves them locally. This README documents safe usage, installation steps, system requirements, command-line options, and examples.

---

## Features

* Periodic screenshot capture to a local folder
* Configurable interval and total duration
* Option to limit total number of screenshots
* Visible mode that prints status to console (no stealth)
* Graceful stop on user interrupt (Ctrl+C)

---

## Requirements

* **Python 3.8+**
* `pip` package manager

Python packages (install with `pip`):

* `pyautogui` (captures screenshots)
* `pillow` (PIL imaging library used by pyautogui)

Optional (for Windows users):

* `pygetwindow` or `pywinauto` if you later add window-specific captures or GUI features.

---

## Installation (recommended)

1. Clone the repository (or place `safescreenshot.py` in a folder):

```bash
git clone https://github.com/DotX-47/auto-screenshot-taker.git
cd auto-screenshot-taker
```

2. Create and activate a virtual environment:

```bash
python3 -m venv venv
# macOS / Linux
source venv/bin/activate
# Windows (PowerShell)
venv\Scripts\Activate.ps1
```

3. Install dependencies:

```bash
pip install --upgrade pip
pip install pyautogui pillow
```

> On Linux, `pyautogui` may require additional system packages (for example, `python3-xlib`, `scrot` or `imagemagick`) depending on your distribution.



Tell me which of these you'd like next.
