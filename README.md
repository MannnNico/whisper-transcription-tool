# Whisper Transcription Tool

This repository contains a simple Python script that uses [OpenAI Whisper](https://github.com/openai/whisper) to transcribe `.m4a` or other audio files into timestamped text. It is designed for qualitative research workflows and produces output that is compatible with tools like MAXQDA.

## Features

- Transcribes audio files to text
- Includes timestamps for each speech segment
- Minimal setup using Python and Whisper
- Structured output for use in qualitative analysis

## Usage

1. Install the requirements:

```bash
pip install openai-whisper torch ffmpeg-python
