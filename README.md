# Keylogger Tool - Python Implementation

This project demonstrates the implementation of a basic keylogger in Python using the `pynput` library. The keylogger captures and logs keystrokes with timestamps, providing insights into user activity for educational and ethical purposes. The tool writes the captured keystrokes to a log file, which can be reviewed later.

## Features
- Logs keystrokes with timestamps.
- Recognizes and handles special keys such as Space, Enter, Backspace, Tab, Shift, Ctrl, Alt, and Escape.
- Writes keystrokes to a log file (`keylog.txt`).
- Stops logging when the Escape key is pressed.

## Requirements

- Python 3.x
- `pynput` library

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ShameelC/PRODIGY_TrackCode_4.git
    ```

2. Install the required Python packages:

    ```bash
    pip install pynput
    ```

## Usage

1. Open a terminal and navigate to the project directory.
2. Run the keylogger script:

    ```bash
    python keylogger.py
    ```

3. The keylogger will start running and log keystrokes to `keylog.txt`.
4. To stop the keylogger, press the `Escape` key.

## Example Log File

An example of the contents of the `keylog.txt` file might look like this:

