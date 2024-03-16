
# Tennis Analysis

## Introduction
This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints. This hands on project is perfect for polishing your machine learning, and computer vision skills. 

## Output Videos
Here is a screenshot from one of the output videos:


https://github.com/ihebakermi10/AI-ML-Tennis-Analysis-system/assets/90511874/985da38a-e234-400e-a5bb-2050e319c0de

1. Use ultralytics and YOLOv8 to detect objects in images and videos.
2. Fine tune and train your own YOLO on your own custom dataset.
3. Train a CNN with pytorch to extract keypoints.
4. Use object trackers to track objects across frames.
5. Use CV2 to read, manipulate and save a video.
6. Analyze detection data and take a data driven approach to develop features. 
7. Put all those ML/DL model output into one big project that have a concrete output. 

## Models Used
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
