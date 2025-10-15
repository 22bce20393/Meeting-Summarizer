# Meeting-Summarizer

The Meeting Summarizer is a lightweight web app that takes in meeting audio recordings, converts them into text transcripts, and generates concise summaries with action items — all directly inside Google Colab.

This tool is perfect for summarizing long discussions, stand-ups, or client calls without deploying any external backend servers.

🚀 Features
✅ Audio Transcription — Uses Groq’s Whisper model (whisper-large-v3-turbo) for accurate speech-to-text conversion.
✅ Local Summarization — Uses a local BART summarization model (facebook/bart-large-cnn) via Hugging Face Transformers.
✅ Multi-file Uploads — Upload multiple meeting audio files in one go.
✅ Web Interface — User-friendly Bootstrap-based frontend served via Flask.
✅ Downloadable Results — Download transcripts and summaries as .txt files.
✅ Runs Fully in Google Colab — No separate backend or hosting required.
