# Youtube Transcript Summarizer

This is a Python application that allows you to summarize the content of a YouTube video using Google Gemini model.

## Features
- Get the Transcription from Youtube
- Summarizes transcribed text using Google Gemini model
- Built with Streamlit for an easy-to-use web interface

## Prerequisites

Before you begin, ensure you have installed the following:

- Python 3.6 or above
- [Streamlit]
- [python-dotenv]
- [google-generativeai]
- [youtube-transcript-api]
- [pathlib]

## Installation 

1. Clone this repository:
```bash
https://github.com/ShravanJump/YT-Transcript-Summarizer.git
```
2. Change into the cloned repository:
```bash
cd YT-Transcript-Summarizer
```
3. Install all necessary packages:
```bash
pip install -r requirements.txt
```
4. Create a `.env` directory in your home directory (or any directory of your choice), and create in the directory `.env` a file called `GOOGLE_API_KEY` and add your Gemini API Key:
```bash
GOOGLE_API_KEY= your api key in " "
```
5. Change the `env_path` variable in the Python script to match the path of your `.env` file.

## Usage

1. Run the script:
```bash
streamlit run app.py
```
2. Once the web application starts, open it in your web browser.

3. Enter the link of the YouTube video you want to summarize in the provided text input.

4. Click the "Generate" button to begin the summarization process.
  
5. The summary will be presented in the form of an informative and factual overview of the video's content, including bullet points if possible. It will also include an introduction and conclusion phrase.

