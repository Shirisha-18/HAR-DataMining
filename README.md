# Human Activity Recognition

Human Activity Recognition (HAR) is a field with diverse applications, ranging from personal health monitors to fitness devices. This project involves the analysis of accelerometer data to determine whether an individual's activity can be accurately detected. The dataset, named Dataset-har-PUC-Rio-ugulino.csv, contains approximately 8 hours of accelerometer data for four individuals, captured from accelerometers worn on the waist, left thigh, right arm, and right ankle.

## Dataset
- **File: `Dataset-har-PUC-Rio-ugulino.csv`** <br>
- **Description:** The dataset comprises 3-axis acceleration measurements taken over 150ms time windows, presented in temporal order without timestamps. Each record corresponds to one of five activity classes: sitting, sitting-down, standing, standing-up, and walking. <br><br>
For more information, you can visit the HAR Dataset at PUC-Rio.

## Objectives
**1. Activity Detection:**
- Evaluate the feasibility of accurately detecting an individual's activity from the provided accelerometer data.

**2. Feature Engineering:**
- Derive features that leverage the temporal nature of the data. Compare these features with an instantaneous approach, which uses only the current instant's acceleration measures.

**3. Change-Point Detection:**
- Investigate the time it takes to detect a change from one activity to another. Explore the creation of new features to enhance change-point detection.

**4. Single Accelerometer Location Analysis:**
- Determine the optimal location (waist, left thigh, right arm, or right ankle) for a single accelerometer in terms of both activity classification accuracy and change-point detection.

## Tasks
**1. Exploratory Data Analysis (EDA):**
- Perform EDA on the dataset to gain insights into the distribution of activities and the characteristics of the accelerometer data.

**2. Feature Extraction:**
- Extract relevant features that capture the temporal patterns of the accelerometer data.

**3. Model Development:**
- Develop machine learning models for activity classification and change-point detection.

**4. Evaluation:**
- Evaluate the performance of the models, comparing the effectiveness of temporal features versus instantaneous features.

**5. Optimal Accelerometer Location:**
- Determine the best location for a single accelerometer, considering both classification accuracy and change-point detection.

## Summary and Recommendations

<!-- Notes - Points to remember -->
Summarize your findings and provide recommendations to your company based on the analysis. Consider aspects such as model performance, feature importance, and the practicality of using a specific accelerometer location for a personal activity monitor.
