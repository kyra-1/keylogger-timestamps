# Keylogger-Timestamping

## Introduction

Keylogger-Timestamping is a simple keylogger built using Python. It logs every key pressed on the keyboard along with a timestamp, saving the information to a text file named `simple_keylog.txt`. This tool is created for educational and ethical use only. Always ensure you have permission before running it on any machine.

## Features

* Logs every keystroke with a timestamp.
* Uses the `pynput` library for keyboard monitoring.
* Stores logs in a human-readable format.

## Prerequisites

* Python 3.x
* `pynput` library (install using pip)

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/keylogger-timestamping.git
cd keylogger-timestamping
```

Install the required library:

```bash
pip install pynput
```

## Usage

Run the keylogger script:

```bash
python keylogger.py
```

## How It Works

1. The script uses `pynput.keyboard.Listener` to monitor key presses.
2. When a key is pressed, it records the key and the timestamp in `simple_keylog.txt`.
3. The log file will be created in the same directory as the script.

## Log File Format

The logs are stored in the format:

```
YYYY-MM-DD HH:MM:SS - key
```

Example:

```
2025-05-11 12:45:23 - a
2025-05-11 12:45:24 - [Key.enter]
```

## Disclaimer

This tool is intended for educational and ethical purposes only. Misuse of this tool is strictly prohibited and may be illegal. Always get explicit permission before using this tool on any system.

## License

MIT License
