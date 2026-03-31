# Traffic Sign Classification using K-Nearest Neighbors (KNN)

## Group Details
**Group:** F  
**Project Title:** Traffic Sign Classification

## Team Members
- Digvijay Dinkar Bhosale
- Omkar Ghanawat
- Mayank Rohilla
- Nidhi Prasad Ghume

## Project Overview
This project focuses on classifying traffic sign images into their respective classes using the **K-Nearest Neighbors (KNN)** algorithm. The goal of the project is to identify the correct traffic sign from an input image based on image preprocessing and machine learning classification.

## Objective
The main objective of this project is to build a traffic sign classification model that can:
- load and preprocess traffic sign images
- train a machine learning model using image data
- classify traffic signs into their corresponding classes
- predict the class of a new uploaded traffic sign image

## Dataset Description

Dataset Drive Link: https://drive.google.com/drive/folders/16Knz1W8VUR4ax133tOYf7PVUQ8wCGKsC?usp=sharing
The dataset used in this project contains traffic sign images organized into class folders.  
It includes:
- **58 traffic sign classes**
- training images stored in separate folders by class ID
- label mapping provided through a CSV file

> Note: Due to dataset size limitations, the full dataset is not uploaded to this repository.

## Workflow
The following steps were performed in this project:
1. Import libraries
2. Mount Google Drive in Google Colab
3. Load dataset paths and labels CSV
4. Explore dataset structure and class distribution
5. Load and resize images to 32x32
6. Convert images into arrays
7. Normalize image data
8. Flatten image arrays for KNN
9. Split data into training and testing sets
10. Train KNN model
11. Evaluate model using accuracy and confusion matrix
12. Predict traffic sign class for test and uploaded images

## Model Used
- **K-Nearest Neighbors (KNN)**

## Best Model Result
- **Best K value:** 1
- **Accuracy Achieved:** 95.92%

## Features of the Project
- Traffic sign dataset exploration
- Image preprocessing and resizing
- Class-wise distribution analysis
- KNN-based image classification
- Confusion matrix visualization
- Uploaded image prediction

## Tools and Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- PIL (Python Imaging Library)

## Files Included in This Repository
- `Traffic_Sign_Classification_KNN.ipynb`
- `README.md`
- `report.pdf` (if included)
- `presentation.pdf` or `presentation.pptx` (if included)

## Conclusion
The project successfully implemented traffic sign classification using the KNN algorithm. The final model achieved strong accuracy and demonstrated that machine learning can be effectively applied to image classification tasks in a syllabus-based academic project.

## Future Scope
This project can be improved further by:
- applying CNN for better image classification
- using larger real-world datasets
- building a real-time traffic sign detection system
- deploying the model in a web or mobile application