# RepeatAloud_Studio

[![License: GPL-2.0](https://img.shields.io/badge/License-GPL%202.0-blue.svg)](https://opensource.org/licenses/GPL-2.0)

Repeat Aloud Studio is a desktop application for creating language learning content packs for the [Repeat Aloud](https://github.com/RepeatAloud) mobile app.

This tool helps content creators prepare video materials with properly segmented subtitles for effective pronunciation practice.

## Features

- **Video Processing**:
  - Download videos from various sources using yt-dlp integration
  - Extract and synchronize subtitles (SRT, VTT formats supported)

- **Audio Analysis**:
  - Visual waveform display using Fourier transform
  - Automatic speech detection algorithms
  - Intelligent segmentation of audio into 3-7 second practice phrases

- **Content Packaging**:
  - Create structured language learning packs (videos + subtitles)
  - Organize content by language and topic (design, health, programming, etc.)
  - Export to GitHub-ready format for community sharing

## Why Repeat Aloud Studio?

Traditional language learning apps provide static content. Repeat Aloud Studio empowers:
- **Teachers** to create targeted pronunciation exercises
- **Polyglots** to build personal learning materials from favorite videos
- **Communities** to share specialized vocabulary collections (tech, business, etc.)

## Getting Started

### Prerequisites
- Python 3.9+
- FFmpeg
- yt-dlp (will be installed automatically)

### Installation
```bash
git clone https://github.com/RepeatAloud/RepeatAloud_Studio.git
cd RepeatAloud_Studio
pip install -r requirements.txt
```
