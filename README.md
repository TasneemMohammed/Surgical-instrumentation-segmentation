# Surgical-instrumentation-segmentation

### Intro to the challenge

The Surgical Instrumentation Segmentation and Action Recognition on Robot-Assisted Radical Prostatectomy Challenge includes 3 different sub-challenges.

1- Action recognition

2- Surgical instrument segmentation

3- Joint estimation of Action recognition and surgical instrument segmentation

for more information see https://www.synapse.org/#!Synapse:syn27618412/wiki/616881

### Background information: 
This repo focuses on surgical tool segmentation, which is crucial in various computer-assisted intervention applications. This task involves processing RGB video frames and assigning semantic labels at the pixel level.

### Goal: 
Our objective in this repo is to solve the semantic segmentation task and generate masks of prominent objects, including surgical tool parts, as well as thin and small tools such as surgical clips, suturing threads, and needles.

### Dataset
• It is a video-based dataset

• You can access the dataset using the following link https://rdr.ucl.ac.uk/projects/SAR-RARP50_Segmentation_of_surgical_instrumentation_and_Action_Recognition_on_Robot-Assisted_Radical_Prostatectomy_Challenge/191091

# Project Structure and Usage
This project was prepared to run on Colab

1- Extract Frames 

ExtractFrames.ipynb

2- Rename Frames

rename_frames.ipynb

3- Build the UNet Arch

unet.ipynb
semantic_segmentation.ipynb
UpdatedMeanIoU.ipynb

4- Lib

FPN_ResNet_semantic_segmentation.ipynb

LinkNet_ResNet_semantic_segmentation.ipynb

Unet_ResNet_semantic_segmentation.ipynb




