# Audio to Text

A simple Python script that transcribes an audio file into text using OpenAI Whisper.

## Features

- Transcribes audio with the Whisper `base` model
- Saves the transcript to `transcript.txt`
- Prints the transcript in the terminal

## Requirements

- Python 3.8 or later
- [FFmpeg](https://ffmpeg.org/) installed and available in your system PATH
- The `openai-whisper` Python package

## Installation

Install Whisper:

```bash
python -m pip install -U openai-whisper