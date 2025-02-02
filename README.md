# Text-to-Video Generation Using Stable Diffusion
**Overview**

This project demonstrates how to generate a video from a simple text prompt using the Stable Diffusion model. By leveraging the power of diffusion models and transformers, we convert text descriptions into a sequence of images, which are then compiled into a video. The project is implemented using Python with libraries like Transformers, Diffusers, and OpenCV.

**Model Explanation**

Stable Diffusion: A state-of-the-art text-to-image model capable of generating high-quality, photorealistic images from text descriptions.

Diffusers Library: Provides a simple interface to work with diffusion models like Stable Diffusion.

Transformers: Handles tokenization and model loading.

In this project, Stable Diffusion generates multiple frames from the same text prompt, creating slight variations in each frame to simulate motion when compiled into a video.

**Features**

Text-to-Image generation using Stable Diffusion.

Compiling generated images into a video using OpenCV.

GPU acceleration for faster processing.

**Requirements**

Ensure you have Python 3.8+ installed. Install the dependencies with:

pip install -r requirements.txt

**Installation**

Clone the repository:

git clone https://github.com/SriDharshana/stable-diffusion-video-generator.git
cd stable-diffusion-video-generator

Install dependencies:

pip install -r requirements.txt

Run the script:

python generate_video.py

