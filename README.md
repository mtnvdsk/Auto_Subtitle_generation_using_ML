# AI Hackathon Video Transcription and Subtitling

This project involves converting video speech to text using the Whisper ASR model and generating subtitles. The code is designed for a specific use case and includes features such as splitting the text into lines, creating captions, and overlaying them on the original video.

## Table of Contents
- [Setup](#setup)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Setup
1. Clone the repository: `git clone <repository-url>`
2. Install the required dependencies using the provided pip installations and apt-get commands.
3. Mount Google Drive to access video files: `drive.mount('/content/drive')`

## Usage
1. Provide the path to the input video: `input_video_path = "/content/drive/MyDrive/video/sample.mp4"`
2. Run the notebook to convert the video to text, split it into lines, and generate subtitles.
3. Adjust parameters such as `MaxChars`, `MaxDuration`, and `MaxGap` in the code as needed.
4. The final output video with subtitles will be saved as `output.mp4` in the specified Google Drive location.

## Dependencies
- [faster-whisper](https://pypi.org/project/faster-whisper/)
- [moviepy](https://pypi.org/project/moviepy/)
- [imageio](https://pypi.org/project/imageio/)

Make sure to install these dependencies before running the code.

