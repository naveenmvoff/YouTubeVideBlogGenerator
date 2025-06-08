# YouTube Content Summarizer

Turn YouTube video into a structured blog-style article using Google Gemini AI and Streamlit.

---

## Overview

This app takes a YouTube video link, fetches its transcript, and generates a structured, readable blog-style summary using Google Gemini 1.5 Flash. The app handles various transcript formats, retries on failure, and provides download options for the summary as `.txt` and `.docx`.

> Ideal for content creators, bloggers, educators, or anyone who wants to repurpose video content into written form.

---

## Live App
  **Try it here**: [YouTube Blog Generator](https://youtubevidebloggenerator.streamlit.app/)
  
---

## Features

📌 Extracts transcripts directly from YouTube  
📌 Uses Google Gemini (via Generative AI API) for summarization  
📌 Blog includes:  
 - **The Video Heading**  
 - **Introduction**  
 - **Key Points**  
 - **Notable Quotes**  
 - **Conclusion**  
📌 Smart retry logic and caching for better performance  
📌 Download summaries in `.txt` or `.docx`  
📌 Simple and responsive UI using Streamlit

---
## Application Flow
![YouTube Content Summarizer](https://github.com/user-attachments/assets/c9bb24c3-3015-4ceb-95ea-25675b2d8343)

---
## Installation

**Clone the repo**
```bash
git clone https://github.com/naveenmvoff/YouTubeVideBlogGenerator.git
cd YouTubeVideBlogGenerator
```
**Set up a virtual environment**
```bash
python -m venv venv
venv\Scripts\activate    # On macOS/Linux source venv/bin/activate
```
**Install dependencies**
```bash
pip install -r requirements.txt
```

**Create a `.env` file**
```bash
GOOGLE_API_KEY=your_gemini_api_key_here
```

**Run the App Locally**
```bash
streamlit run app.py
```
