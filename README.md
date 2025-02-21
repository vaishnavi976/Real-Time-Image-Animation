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



Install OpenFace:

git clone https://github.com/TadasBaltrusaitis/OpenFace.git
cd OpenFace
./install.sh

Install FFmpeg:

sudo apt install ffmpeg

 Usage
Preprocess the input image

<ins>Align and crop</ins> the face from the static image.
Detect <ins>facial landmarks</ins> using OpenFace.
Convert Audio to Phonemes

Extract phonemes using <ins>Torchaudio</ins> or <ins>PocketSphinx</ins>.
Map phonemes to <ins>facial movements</ins>.
Generate Facial Animation

Use the <ins>First-Order Motion Model</ins> to synthesize motion.
Apply <ins>facial expressions</ins> based on extracted features.
Render the Video

Merge the animated frames into a video using <ins>FFmpeg</ins>.
Sync the <ins>audio</ins> to the animated video.
Run the script

sh
Copy
Edit
python main.py --image path/to/image.jpg --audio path/to/audio.wav --output output.mp4
Results
High-quality <ins>animations</ins> with realistic facial movements.
Adaptability to <ins>unseen speakers</ins> and expressions.
<ins>Real-time</ins> or near real-time inference on consumer-grade GPUs.
Applications
Virtual Assistants: Creating realistic <ins>AI-driven avatars</ins>.
Education: Animating <ins>historical figures</ins> for digital learning.
Entertainment: Generating realistic animations for <ins>movies and games</ins>.
Accessibility: Assisting <ins>speech-impaired individuals</ins> through talking avatars.
Future Work
Improve <ins>real-time performance</ins> for mobile devices.
Enhance <ins>emotion recognition</ins> and expression mapping.
Integrate support for more <ins>diverse languages</ins> and accents.
Acknowledgment
We extend our gratitude to our mentor <ins>Mr. A. K. Patil</ins> and <ins>R.C. Patel Institute of Technology</ins> for their guidance and support throughout this project.

Contact
For any queries, feel free to reach out:

Email: <ins>vaishchaudhari976@gmail.com</ins>
