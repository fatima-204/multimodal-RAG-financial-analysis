# Multimodal Financial Analysis of Starbucks

This project performs financial analysis of Starbucks using a multimodal RAG (Retrieval-Augmented Generation) approach. It processes financial PDFs (converted to images), audio explanations, and leverages the Gemini API for generative tasks.

## Features
- Extracts text from Starbucks financial PDFs (converted to images stored in `/images` folder)
- Processes audio explanations using OpenAI's Whisper model (transcripts stored in `/transcript/transcription.txt`)
- Uses cosine similarity for retrieving relevant chunks
- Generates analysis using Gemini API

## Setup
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Add your Gemini API key to `.env` file
4. Place PDFs in `/docs` and audio files in `/audio`
## File Structure
/images/ - Extracted images from financial PDFs

/transcript/ - Audio transcripts (transcription.txt)

/docs/ - Original PDF documents

/audio/ - Audio explanation files

requirements.txt - Python dependencies
## Dependencies
Gemini API for generative tasks

Whisper model for audio transcription

Cosine similarity for relevant chunk retrieval


This README covers all the components you mentioned (multimodal approach, PDF-to-images conversion, Whisper transcripts, Gemini API, and cosine similarity) while providing clear instructions for setup and usage. The requirements.txt includes all the likely dependencies needed for such a project.
