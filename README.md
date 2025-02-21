## Real-Time-Image-Animation
Real-Time Image Animation Using First-Order Motion Model

# Overview

This project explores real-time image animation by leveraging the First-Order Motion Model to animate static images based on motion transfer from a source video. This approach utilizes deep learning techniques, including Generative Adversarial Networks (GANs) and motion estimation, to synthesize realistic animations.

# Team Members

Ankita Kiran Sonawane

Vaishnavi Ganesh Chaudhari

Neha Dinesh Sonawane

Namrata Ambalal Navale

# Guide

Mr. A. K. Patil - Assistant Professor, AIML Department, R.C. Patel Institute of Technology, Shirpur

# Features

Real-time image animation using motion transfer.

Works with any static image.

High-quality facial motion synthesis.

Lip-syncing capabilities for talking face animation.

Optimized model for efficient inference.

# Technologies Used

Python 3.6+

PyTorch (Deep Learning Framework)

OpenCV (Image Processing)

TorchAudio (Audio Processing)

FFmpeg (Video Rendering)

OpenFace (Facial Landmark Detection)

## Installation

# Clone this repository:

git clone https://github.com/your-repo-name.git
cd your-repo-name

# Install dependencies:

pip install -r requirements.txt

# Install OpenFace:

git clone https://github.com/TadasBaltrusaitis/OpenFace.git
cd OpenFace
./install.sh

# Install FFmpeg:

sudo apt install ffmpeg

## Usage

Preprocess the input image

Align and crop the face from the static image.

Detect facial landmarks using OpenFace.

Convert Audio to Phonemes

Extract phonemes using Torchaudio or PocketSphinx.

Map phonemes to facial movements.

Generate Facial Animation

Use the First-Order Motion Model to synthesize motion.

Apply facial expressions based on extracted features.

Render the Video

Merge the animated frames into a video using FFmpeg.

Sync the audio to the animated video.

# Run the script

python main.py --image path/to/image.jpg --audio path/to/audio.wav --output output.mp4

# Results

High-quality animations with realistic facial movements.

Adaptability to unseen speakers and expressions.

Real-time or near real-time inference on consumer-grade GPUs.

# Applications

Virtual Assistants: Creating realistic AI-driven avatars.

Education: Animating historical figures for digital learning.

Entertainment: Generating realistic animations for movies and games.

Accessibility: Assisting speech-impaired individuals through talking avatars.

# Future Work

Improve real-time performance for mobile devices.

Enhance emotion recognition and expression mapping.

Integrate support for more diverse languages and accents.

# Acknowledgment

We extend our gratitude to our mentor Mr. A. K. Patil and R.C. Patel Institute of Technology for their guidance and support throughout this project.

# Contact

For any queries, feel free to reach out:

Email: vaishchaudhari976@gmail.com
