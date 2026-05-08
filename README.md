# Vibe Watcher 👀
The black-box recorder for AI coding sessions.

Watch exactly what Claude/Cursor changes in your files — live colored diffs, 
risky file alerts (.env, secrets, auth), and one-click revert to any previous version.

## Download
👉 [Download watcher.exe (Windows)](https://github.com/Talon212/vibe-watcher/releases/download/v1.0/watcher.exe)

## How to use
1. Double-click watcher.exe
2. Drag your project folder into the window and press Enter
3. Let Claude/Cursor do its things
4. Press Ctrl+C to stop — review what changed and revert anything you don't want

## Features
- Live colored diffs as files are saved
- Flags risky files (.env, secrets, auth, config) instantly
- Detects which functions/classes were changed
- Session summary on exit
- Revert any file to any previous save point from the current or past sessions
- Everything stays local — no code leaves your machine

## Run from source (optional)
pip install watchdog rich
python watcher.py
