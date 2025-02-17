# Emotion-Reconization-and-Motion-Detection-model



This project utilizes **OpenCV**, **DeepFace**, and **Transformers** to perform face and emotion recognition on video frames. It leverages pre-trained models to analyze emotions efficiently.



## Features

- **Face Detection** using OpenCV

- **Emotion Recognition** with DeepFace

- **Pre-trained Transformers** for enhanced accuracy

- **Optimized Processing** to handle large video files



## Installation

To run this project, install the required dependencies:

```sh

pip install av opencv-python deepface numpy

```



## Challenges & Solutions

1. **High Resource Demand** → Used optimized pre-trained models.

2. **Face Detection Failures** → Disabled strict detection using `enforce_detection=False`.

3. **Slow Processing on Large Videos** → Limited analysis to key frames or reduced resolution for intermediate steps.



## Usage

Run the Jupyter Notebook and follow the instructions to process video frames for face and emotion recognition.



### Pre-trained model

https://huggingface.co/gautamtata/videomae-base-finetuned-kinetics-finetuned-lipsync-subset-1
