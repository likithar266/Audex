# Audex

**Audex** is a project built with Flask that transcribes audio/video from local device or from YouTube and generates a downloadable PDF of the transcription. It leverages speech recognition and PDF generation libraries to provide a quick and simple media-to-text pipeline.

## Features

- Extracts audio from YouTube videos using `yt-dlp`
- Transcribes speech with `SpeechRecognition` and `MoviePy`
- Exports formatted transcripts to PDF using `ReportLab`
- Clean Flask API with CORS support for integration

## Setup Instructions

### Method 1: Direct Installation

```bash
git clone https://github.com/likithar266/Audex.git
cd Audex
pip install -r requirements.txt
python app.py
```
### Method 2: Using a Virtual Environment (Recommended)

```bash 
git clone https://github.com/likithar266/Audex.git
cd Audex
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

## Tech Stack (Terminal View)
- Flask
- yt-dlp
- SpeechRecognition
- MoviePy
- ReportLab

## Output
The application transcribes audio/video input and returns a formatted PDF document containing the transcript.