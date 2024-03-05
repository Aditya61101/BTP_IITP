
# Bachelor's Thesis Project (BTP) in Power System and its Protection

## Overview
This repository contains the code and documentation for my bachelor's thesis project conducted during my 7th and 8th semesters at IIT Patna. I am doing two projects in the whole year. The first project focused on shunt fault classification using machine learning, and the second project which is currently going focuses on fault detection using anomaly detection methods of machine learning.

## Overview of the 1st project
I successfully completed a fault classification project in the power system domain, utilizing machine learning techniques to enhance fault detection and analysis. The project aimed to improve the reliability and efficiency of power systems by accurately classifying different types of faults that can occur in transmission and distribution lines.

### Key Highlights
- Dataset Generation: I generated a comprehensive dataset using a 2-area, 11-bus system simulation model. The dataset included voltage and current measurements from strategically selected buses, covering various fault scenarios.
- Machine Learning Model: I employed a Random Forest Classifier to classify faults based on the dataset. The model was trained to classify faults into different categories, including single line-to-ground (S-L-G), line-to-line (L-L), and three-phase faults (L-L-L-G and L-L-L).
- Evaluation and Results: The model achieved a high accuracy of 93% on the training dataset and 86% on the testing dataset, demonstrating its effectiveness in fault classification.
- Contribution: The project contributes to enhancing the fault detection and classification capabilities of power systems, ultimately improving their reliability and reducing downtime.

Overall, the fault classification project demonstrates my proficiency in machine learning and data analysis, as well as my ability to apply these skills to real-world problems in the power system domain.

## Overview of the 2nd project
This project focuses on improving fault detection in power systems by leveraging machine learning (ML) algorithms. Traditional methods for detecting faults rely on manual parameter tuning, which can lead to inaccuracies. To overcome this, we are using an ML model trained on a dataset containing disturbance signals, disturbance levels, and center of inertia frequency to detect the occurrence time of faults without the need for manually set parameters. This approach improves the accuracy of fault detection in power systems.

### What has been done till now??
- Dataset generation: I have generated the dataset using a two-area system. I provided a step signal as a disturbance and varied its magnitude from 0.1 to 1 while taking the center of interia frequency of the whole system for each magnitude.

- ML model selection: I chose Density-Based Spatial Clustering of Applications with Noise (DBSCAN) as my model. For hyperparameter tuning I am using k distance plot according to the  [Research paper](https://www.khoury.northeastern.edu/home/vip/teach/DMcourse/2_cluster_EM_mixt/notes_slides/revisitofrevisitDBSCAN.pdf) to detect accurate epsilon value and for min_samples, 2*no_of_features is the best choice.

## Acknowledgement
Special thanks to Dr. Sanjoy Kumar Parida sir for providing guidance and support throughout the project.
