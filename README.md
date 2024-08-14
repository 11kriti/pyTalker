# pyTalker

**pyTalker** is a lightweight text-to-speech (TTS) program written in Python. It allows you to type in text and have it spoken aloud using your computer's built-in speech synthesis capabilities on Windows.

## Features

- Converts text input into speech.
- Simple and easy-to-use command-line interface.
- Exit the program by typing `stop`.

## Prerequisites

- **Python 3.x** installed on your system.
- Windows operating system with PowerShell.


## How It Works

RoboSpeaker uses Python's `os` module to execute a PowerShell command that utilizes the `System.Speech.Synthesis.SpeechSynthesizer` class. This allows the text input to be converted into audible speech directly through the system's speakers.

