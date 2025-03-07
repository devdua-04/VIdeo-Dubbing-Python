# Video Dubbing in Python

## 📌 Overview
This project provides a Python-based video dubbing solution that allows users to replace the original audio of a video with a new audio track. The tool ensures seamless synchronization between the video and the dubbed audio.

## 🚀 Features
- Extracts audio from a video file
- Allows replacing audio with a new dubbed version
- Supports common video and audio formats (MP4, AVI, WAV, MP3, etc.)
- Uses FFmpeg for efficient media processing
- Utilizes OpenAI's Whisper for automatic speech-to-text and dubbing
- Simple command-line interface for easy usage

## 🔧 Installation
Ensure you have Python installed (Python 3.7+ recommended). Then, clone the repository and install the dependencies:

```sh
git clone https://github.com/devdua-04/VIdeo-Dubbing-Python.git
cd VIdeo-Dubbing-Python
pip install -r requirements.txt
```

You also need to install FFmpeg if it's not already available on your system:

- Windows: Download from [FFmpeg official site](https://ffmpeg.org/download.html) and add it to your system PATH.
- macOS: Install via Homebrew:
  ```sh
  brew install ffmpeg
  ```
- Linux: Install via package manager:
  ```sh
  sudo apt-get install ffmpeg
  ```

Additionally, install OpenAI's Whisper for speech recognition:

```sh
pip install openai-whisper
```

## 🎬 Usage
Run the script with the required arguments:

```sh
python dub_video.py --video input.mp4 --audio new_audio.mp3 --output output.mp4
```

### Arguments:
- `--video`: Path to the input video file
- `--audio`: Path to the new audio file
- `--output`: Path to save the output video with the dubbed audio

## 🛠 Dependencies
- Python 3.7+
- FFmpeg
- MoviePy
- OpenAI Whisper

<!-- ## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! Feel free to open issues and submit pull requests.

## 📞 Contact
For any queries, reach out via GitHub issues or [TechMonkey](https://www.techmonkey.us/). -->
