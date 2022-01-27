# Masters-app
This repository contains all the code created in the process of performing analysis on human-object relation. 

Data used:
- ntu120
- our own film dataset

A research paper is being written based on this thesis and will be available soon.

# Single person joint position
Using the code from this repository. Software using mediapipe is not suitable for joint position detection when there are several people in the camera view.

# Multi person joint position
Using zed-sdk camera software for multi-person detection. The problem is that the detection accuracy is much lower than the joint position detection for a single person, which resulted in the need for additional filtering of the results.

# Denoising multi-person joint positions
Run files written for this part:
- ntu120/seq_transformation.py
- ntu120/get_raw_skes_data.py
- ntu120/get_raw_denoised_data.py
- ntu120/statistics/gen_available_skes_name.py
- ntu120/statistics/gen_setup_index.py

# Object detection
Using labelImg + ImageAI - result is a bounding box with pixel coordinates of the box corners.

# Object position in 3D coordinates based on bounding box position
Solved

# Neural Network
Competitive NN - Solved

# Person-Object relationship
Solved
