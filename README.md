# Real-Time Image Animation Using First-Order Motion Model

## Overview
This project explores real-time image animation by leveraging the <ins>First-Order Motion Model</ins> to animate static images based on motion transfer from a source video. This approach utilizes deep learning techniques, including <ins>Generative Adversarial Networks (GANs)</ins> and motion estimation, to synthesize realistic animations.

## Team Members
- <ins>Ankita Kiran Sonawane</ins>
- <ins>Vaishnavi Ganesh Chaudhari</ins>
- <ins>Neha Dinesh Sonawane</ins>
- <ins>Namrata Ambalal Navale</ins>

## Guide
<ins>Mr. A. K. Patil</ins> - Assistant Professor, AIML Department, R.C. Patel Institute of Technology, Shirpur

## Features
- <ins>Real-time image animation</ins> using motion transfer.
- Works with <ins>any static image</ins>.
- High-quality <ins>facial motion synthesis</ins>.
- <ins>Lip-syncing</ins> capabilities for talking face animation.
- Optimized model for <ins>efficient inference</ins>.

## Technologies Used
- <ins>Python 3.6+</ins>
- <ins>PyTorch</ins> (Deep Learning Framework)
- <ins>OpenCV</ins> (Image Processing)
- <ins>TorchAudio</ins> (Audio Processing)
- <ins>FFmpeg</ins> (Video Rendering)
- <ins>OpenFace</ins> (Facial Landmark Detection)

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo-name.git
   cd your-repo-name

2. Install dependencies:

   pip install -r requirements.txt

3. Install OpenFace:

   git clone https://github.com/TadasBaltrusaitis/OpenFace.git
   cd OpenFace
   ./install.sh

4. Install FFmpeg:

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

Run the script

python main.py --image path/to/image.jpg --audio path/to/audio.wav --output output.mp4

## Results

High-quality animations with realistic facial movements.

Adaptability to unseen speakers and expressions.

Real-time or near real-time inference on consumer-grade GPUs.

## Applications

Virtual Assistants: Creating realistic AI-driven avatars.

Education: Animating historical figures for digital learning.

Entertainment: Generating realistic animations for movies and games.

Accessibility: Assisting speech-impaired individuals through talking avatars.
## Real Time Image Animation

### **Front-End Interface**
![Front-End](https://raw.githubusercontent.com/vaishnavi976/Real-Time-Image-Animation/main/Front%20End.png)

### **Generated Video Output**
![Generated Video](https://raw.githubusercontent.com/vaishnavi976/Real-Time-Image-Animation/main/Output%20Image.png)


## Future Work

Improve real-time performance for mobile devices.

Enhance emotion recognition and expression mapping.

Integrate support for more diverse languages and accents.

## Acknowledgment

We extend our gratitude to our mentor Mr. A. K. Patil and R.C. Patel Institute of Technology for their guidance and support throughout this project.

## Contact

For any queries, feel free to reach out:

Email: vaishchaudhari976@gmail.com
