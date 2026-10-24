# Snake Web

A responsive Snake arcade game served by a small Flask application. The game runs in the browser using Canvas and has no external game-asset dependency.

## Features

- Keyboard controls using **W/A/S/D** or the arrow keys.
- On-screen direction controls for touch devices.
- Fruit collection, growth, scoring, collision/game-over, pause, and restart.

## Technology

- Python and Flask
- HTML, JavaScript Canvas, and CSS

## Run locally on Windows

From the repository root in PowerShell:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install Flask
python -m flask --app app run --host 127.0.0.1 --port 5103
```

Open [http://127.0.0.1:5103](http://127.0.0.1:5103). Stop the server with **Ctrl+C** and leave the virtual environment with `deactivate`.

## Before publishing

Exclude virtual environments, caches, and local logs. No license is included; add one only after confirming ownership and license terms.
