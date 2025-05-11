# Keylogger-Timestamps

## Introduction

Keylogger-Timestamps is a simple keylogger built using Python. It logs every key pressed on the keyboard along with a timestamp, saving the information to a text file named `simple_keylog.txt`. This tool is created for educational and ethical use only. Always ensure you have permission before running it on any machine.

## Features

* Logs every keystroke with a timestamp.
* Uses the `pynput` library for keyboard monitoring.
* Stores logs in a human-readable format.
  
## Problem Statement Solved

In environments where user activity needs to be monitored for security reasons, such as public computers or shared workspaces, there may be concerns about unauthorized usage when the device is left unattended. Additionally, in situations where physical peripherals (like the trackpad or mouse) are disabled or disconnected, monitoring keyboard usage can help track interactions.

This keylogger helps solve this problem by recording every keystroke along with a timestamp, allowing users to review activity and detect any unauthorized access. It can also serve as a lightweight monitoring tool when you leave your device unattended, giving you insights into whether the device was accessed during your absence.   
## Prerequisites

* Python 3.x
* `pynput` library (install using pip)

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/keylogger-timestamps.git
cd keylogger-timestamps
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
