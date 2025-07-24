# mp4-transcriber
A local, python-based app that transcribes audio from .mp4 video files and converts it to text using OpenAI;s Whisper speech recognition. The tool is designed to run entirely offline, for privacy purposes, but it also runs with regards to your machine's specifications, optionally, it uses GPU acceleration when present.

## Features
- Transcribes '.mp4'and '.mp3' files into plain text using Whisper speech recognition models.
- Supports Whisper: 'tiny', 'base', 'small', 'medium', 'arge'
- Uses GPU acceleration (CUDA) for faster transcription.

## Requirements

- Python 3.8+
- ffmpeg(https://ffmpeg.org/), make sure this is installed in your system.
- pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121 (If you choose to use GPU Acceleration, install the CUDA-enabled pytorch)

There are some dependencies, check out requirements.txt, use pip install -r requirements.txt in a command prompt on your machine after downloading/cloning the mp4-transcriber.

