AI Trailer Generator

This project leverages advanced AI technologies to automatically generate engaging trailers from longer video files. It is designed to work with various video content such as movies, presentations, and tours.

Features

Automated Trailer Creation: Generates trailers with minimal manual effort.
Voice Cloning: Adds custom voice overs using Text-to-Speech (TTS).
Frame Ranking: Identifies the most representative frames using multimodal similarity models.
Customizable Parameters: Fine-tune trailer length, voice characteristics, and more.
Installation

Clone the repository:

git clone https://github.com/yourusername/ai-trailer-generator.git
cd ai-trailer-generator

Install the required dependencies:

pip install -r requirements.txt

Usage

Define your configurations in the configs dictionary in the script.
Place the input video in the videos directory.

Run the script:

python gemini_ai_trailer.py

Find the generated trailer in the output directory.

Dependencies

Python 3.8+
Google Generative AI API
Libraries: moviepy, librosa, sentence-transformers, Pillow, cv2

File Structure

videos/: Input videos.
voices/: Reference audio files for voice cloning.
output/: Generated trailers and intermediate files.
gemini_ai_trailer.py: Main script.

Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

License

This project is licensed under the MIT License.

