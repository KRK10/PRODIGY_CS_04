# PRODIGY_CS_04

Keystroke Logger
This Python script implements a basic keystroke logger that captures and records all keyboard input to a specified log file. It uses the pynput library to listen for keyboard events.

How It Works:

Logging Keystrokes: The script captures each key press and writes it to a log file (keylog.txt by default).

Special Keys Handling:

Spaces are recorded as ' '.

Enter is recorded as a newline.

Backspace, Shift, Ctrl, and Alt keys are recorded with their respective labels (e.g., [BACKSPACE]).

Stop Listener: The logging stops when the 'Esc' key is pressed.

Usage:

Install Requirements: Ensure pynput is installed (pip install pynput).

Run the Script: Execute the script to start logging keystrokes.

Stopping the Logger: Press 'Esc' to stop the logger.

Disclaimer:

This script is intended for educational purposes only. Unauthorized use of a keylogger may violate privacy laws and ethical guidelines. Ensure you have permission before using this tool on any system.
