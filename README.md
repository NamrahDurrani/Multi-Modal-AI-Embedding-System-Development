# Multi-Modal-AI-Embedding-System-Development
# Multi-Modal AI Search Engine

A natural-language search system across text, audio, and video files,
built on ChromaDB, Sentence-Transformers, Whisper, and BLIP, served via FastAPI.

## Features
- Ingests .txt/.md, .mp3/.wav/.m4a, and .mp4/.mov/.avi files
- Embeds content with all-MiniLM-L6-v2
- Transcribes audio/speech with faster-whisper
- Captions video frames with BLIP
- Voice-query search (speak or upload a recording)
- Web UI with filters, score bars, and file download/playback

## Architecture
[brief diagram or description — see docs/project_report.md]

## Setup
1. Open `notebook/multimodal_search.ipynb` in Google Colab
2. Run all cells in order
3. Upload `ui/index.html` to `/content/ui/`
4. Open the printed Colab proxy URL

## Usage
- Upload files via the sidebar
- Search with natural language queries
- Use the mic or upload a voice recording for spoken queries

## Tech Stack
Python, FastAPI, ChromaDB, Sentence-Transformers, faster-whisper, BLIP, HTML/CSS/JS
