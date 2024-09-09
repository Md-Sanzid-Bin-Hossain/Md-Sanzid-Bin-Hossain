---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: true
---


## **P4:** Whole Slide Image (WSI) Cadaver Tissue Patch Preparation and Classification
## Summary
In this project, we introduce a challenging dataset, which contains 15 organ classes for deep learning model development and validation. Our publicly available dataset addresses a crucial gap in digital pathology by providing a large, diverse, and annotated collection of whole slide histopathology images, following FAIR principles. It serves as a benchmark for medical imaging analysis tasks like disease classification, and cancer and pneumonia cell segmentation, enabling improved diagnostics and treatment strategies. With its diverse organ classes and a vast number of patches, it is an ideal resource for transfer learning, accelerating research progress. Crucially, by introducing substantial publicly available data into this field, the dataset overcomes a fundamental challenge, paving the way for more robust deep-learning models in digital pathology. Overall approach of our work is provided in the following Figure:

![Alt text](Images/overall_process.png)

<br>

## Dataset
Our dataset is available on the following [link](https://stars.library.ucf.edu/ucfnecropsywsi/). Dataset contains 15 organ classes. A sample WSI image of each Organ class is provided in the following Figure.

![Alt text](Images/WSI_all_organs.png)

<br>
 
- **P3:** Smartphone-Video Based Human Kinetics Estimation
  - Developed an innovative method for estimating knee adduction moment (KAM), knee flexion moment (KFM), and 3D ground reaction forces (GRFs) using only smartphone video data.
  - The method employs a two-step knowledge distillation and multi-modal fusion technique to achieve high accuracy in kinetics estimation.

- **P2:** Sparse IMU Sensor-Based Joint Angles, Joint Moments, and GRFs Estimation
  - Proposed novel methods for estimating joint angles, joint moments, and ground reaction forces (GRFs) using a sparse configuration of inertial measurement unit (IMU) sensors.
  - Leveraged a new technique called sensor distillation and multi-modal fusion to enhance the accuracy and reliability of the estimations, significantly outperforming state-of-the-art deep learning models while remaining computationally lightweight.
    
- **P1:** Prediction and Reconstruction of 3D Human Pose Using IMUs and Wearable Cameras
  - Collected data from 20 subjects using Vicon Motion Capture, Delsys IMUs, and two shank-mounted egocentric GoPro cameras, with subsequent processing in OpenSim.
  - Introduced an innovative approach that integrates whole-body IMUs with wearable camera features to accurately reconstruct current 3D poses and predict future movements.
