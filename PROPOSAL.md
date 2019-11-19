# Domain and Context
## Description: 
Infer details from videos of cricket shots played by batsmen for analytical reference
## Domain: 
Cricket, a popular sport across globe and primarily so in India
## Context: 
A huge chunk of young population invest their energies at learning the game – many of them are unable to get their performance evaluated with professional support staff. The proposed solution works towards providing mobile applications that can infer player’s batting technique through supervised computer vision models to provide real-time performance insights as response

# Problem Statement
## Objective: 
Infer batsman’s position while playing a cricket shot and predict performance insights through supervised computer vision models
## Steps:
1. Extract required frames from each video
2. Image preprocessing techniques
3. Apply transfer-learning from pretrained models (VGG16, MobileNet, etc) to extract features
4. Train 5 DL models to predict inference from each frame - Direction, location, control, type and aerial
(WIP Updates: Direction classification 86% accuracy recorded)
5. Conclude most common prediction for required frames from videos to predict video class
## Example: 
Direction - Offside (covers), Control - Yes, Type - Aggressive, Aerial - Yes

# Dataset(s)
## Overview:
230 minutes of videos focusing on cricket shots played by the batsmen during training sessions downloaded from youtube
(equals approx. 2670 cricket shots and 168,600 frames)
## Batch #1: 15 minutes data extracted for quick POC verification of steps
1. 174 cricket shots extracted (12 shots per min of video footage)
2. 10991 frames extracted
3. Base model generated (VGG16/Mobilenet, all frames, no image augmentation generated video classification accuracy of around 63%)

# Folder structure used for the exercise
## Master folder
### xx_ClassN (Class-wise N number of video folders, example: A_OffSide, B_Legside, etc.)
### Dataframe_with_video_tag_location ("Lists.csv" format)
### Empty_folder_to_store_training_frames ("train_1")
### Empty_folder_for_prediction_frames ("temp")
