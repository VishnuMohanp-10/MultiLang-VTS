# MultiLang-VTS

A web application that allows users to upload YouTube video and it process the video amd generate transcripts and summaries in preferred language. The app processes the video, converts its audio into text, and returns a summarized version of the content in the selected language — capturing key insights from the video.

---

## Key Features

- Video processing and Transcription + Summarization a unified pipeline .
- Upload a video file and it process and gives transcription and summarization efficiently.
- Multi-language support
- Summarized output with key points
- Supports YouTube video URLs and live video links
- Fast, responsive interface using WebSockets

---

## Technologies Used

- Python
- FastAPI – backend API framework
- Whisper – for speech recognition and transcription
- HTML/CSS/JavaScript – frontend

---

## How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/YOUR-USERNAME/multilang-tvs.git
   cd multilang-tvs

2. Install dependencies
Create a virtual environment and install the required packages:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt


3. Run the server

uvicorn main:app --reload


4. Open your browser and go to:

http://localhost:8000




---
