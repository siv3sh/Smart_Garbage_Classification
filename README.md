# Smart Garbage: AI-Driven Waste Classification

This project leverages AI to classify waste into 12 categories, promoting efficient sorting and recycling. Using clustering and deep learning models, it achieves high accuracy in waste classification, contributing to sustainable waste management and environmental conservation.

## Table of Contents

1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Methodology](#methodology)
4. [Results and Findings](#results-and-findings)
5. [Applications](#applications)
6. [Conclusion](#conclusion)
7. [How to Run the Project](#how-to-run-the-project)

## Introduction
Efficient waste management is crucial for environmental sustainability. Manual waste segregation is time-consuming and error-prone, leading to ineffective recycling processes. This project provides a robust solution by automating waste classification into predefined categories, evaluating the performance of AI algorithms on a diverse dataset.

## Problem Statement
Improper waste segregation remains a global challenge, resulting in inefficient recycling, environmental pollution, and higher waste management costs. Manual sorting is time-consuming, error-prone, and labor-intensive. With increasing volumes of waste generated daily, there is an urgent need for an accurate, scalable solution to classify waste into recyclable and non-recyclable categories. This project employs machine learning techniques to address these issues effectively.

## Methodology

1. **Data Preparation:**
   - Resized images to 128x128 pixels.
   - Normalized pixel values to [0, 1].
   - Encoded categories numerically.

2. **Data Splitting:**
   - Divided data into training (80%) and testing (20%) sets.

3. **Visualization:**
   - Displayed sample images and category distribution.

4. **Machine Learning:**
   - Applied K-Means clustering for exploratory analysis.
   - Computed silhouette scores to evaluate cluster quality.
   - Experimented with CNNs for better classification accuracy.

## Results and Findings

- **Dataset Insights:**
  - Total Images: 5000.
  - Categories: 5 (Plastic, Glass, Metal, Paper, Organic).
  - Training/testing split sizes: 4000/1000.

- **Performance Metrics:**
  - **Clustering:**
    - Optimal Clusters: 5.
    - Silhouette Score: 0.78.
  - **Model Accuracy:**
    - Initial Accuracy: 85.5%.

## Applications

1. **Waste Management Facilities:**
   - Automating garbage classification to streamline recycling processes and reduce manual labor.

2. **Smart Cities:**
   - Integrating garbage classification systems into IoT-enabled smart bins for real-time sorting and monitoring.

3. **Educational Use:**
   - Leveraging the model to teach sustainability practices and waste segregation in schools and institutions.

4. **Industrial Use:**
   - Assisting industries in sorting waste materials for recycling and ensuring compliance with environmental regulations.

5. **Community Projects:**
   - Deploying the system for local waste management initiatives, empowering communities to manage their waste effectively.

## Conclusion
This project demonstrates that machine learning can significantly enhance the efficiency of waste classification, reducing errors and minimizing manual intervention. Future improvements could include handling waste items rare in the dataset, expanding the classification scope, and integrating real-time advancements for broader adoption.

## How to Run the Project

1. Clone the repository.
2. Install the required dependencies using the command:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook or Python script provided in the repository.
4. Follow the instructions in the notebook to preprocess data, train models, and evaluate results.

---
Feel free to contribute or provide feedback to improve the system further!

