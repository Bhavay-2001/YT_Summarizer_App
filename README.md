# YouTube Video Summarizer

## Overview
The **YouTube Video Summarizer** is a Streamlit-based application that provides detailed summaries of YouTube videos. By leveraging the Google Gemini Pro LLM model and extracting transcripts from YouTube videos, the app generates concise, point-based summaries to help users quickly understand the video content.

[**Live Application**](https://yt-video-summarer.streamlit.app/)

---

## Features
- **Transcript Extraction**: Automatically extracts the transcript from the provided YouTube video link.
- **AI-Powered Summarization**: Uses the Google Gemini Pro LLM model to generate a detailed summary of the video.
- **Thumbnail Preview**: Displays the thumbnail of the YouTube video for easy identification.
- **Interactive Interface**: Simple and user-friendly UI built using Streamlit.

---

## How It Works
1. **Input Video Link**: Users provide the URL of a YouTube video.
2. **Transcript Extraction**: The application retrieves the transcript of the video using the `youtube-transcript-api` library.
3. **AI Summarization**: The transcript is processed by the Google Gemini Pro LLM model with a predefined summarization prompt.
4. **Output Summary**: The app displays a concise and structured summary of the video content.

---

## Tech Stack
- **Programming Language**: Python
- **Framework**: Streamlit
- **Libraries**:
  - `streamlit`
  - `dotenv`
  - `google-generativeai`
  - `youtube-transcript-api`
- **Model**: Google Gemini Pro LLM
- **Deployment**: Streamlit Cloud

---

## Installation
To run this project locally, follow these steps:

### Prerequisites
- Python 3.8+
- A Google Cloud account with access to the Gemini Pro API
- YouTube Transcript API support for the desired video

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yt-video-summarizer.git
   cd yt-video-summarizer
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   - Create a `.env` file in the project directory.
   - Add your Google Gemini Pro API key:
     ```env
     GOOGLE_API_KEY=your_google_api_key
     ```

5. Run the application:
   ```bash
   streamlit run app.py
   ```

6. Open the application in your browser at `http://localhost:8501`.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request.

---

## Author
[Bhavay Malhotra](https://github.com/Bhavay-2001)

