# YouTube-Transcription
Convert YouTube audio to text using OpenAI Whisper.
This Python script allows you to download audio from a YouTube video, transcribe it using OpenAI's Whisper API, and return the transcription text. It leverages yt-dlp for audio extraction and OpenAI's Whisper for accurate audio transcription.

Features
Downloads audio from YouTube videos via a simple URL input.
Transcribes the downloaded audio using OpenAI's Whisper API.
Cleans up temporary audio files after the transcription process.
Requirements
yt-dlp: For downloading and extracting the best available audio from YouTube videos.
OpenAI API: To transcribe the audio using Whisper. Ensure you have your OpenAI API key set as an environment variable (OPENAI_API_KEY).
Usage
Clone the repository and install the dependencies.
Run the script, providing a YouTube video URL when prompted.
The script will output the transcription of the audio.
bash
Copy code
python youtube_to_text.py
Example
bash
Copy code
Enter YouTube video URL: https://www.youtube.com/watch?v=example
Transcription:
...
Dependencies
yt-dlp
requests
openai
