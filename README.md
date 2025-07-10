# 🚗 Automatic Number Plate Recognition (ANPR) System

This project implements an end-to-end **Automatic Number Plate Recognition (ANPR)** system using image processing and deep learning techniques.

## Objective

To detect and recognize vehicle number plates from images using computer vision and OCR-based deep learning models.

## Dataset

- **Source**: Collected from Roboflow (public number plate dataset)
- **Contents**: Annotated vehicle images with bounding boxes around number plates

## Technologies Used

- **Python**, **OpenCV**, **TensorFlow / Keras**
- **EasyOCR** / **Tesseract** for text recognition
- **Matplotlib**, **NumPy** for preprocessing and visualization

## Key Features

- Preprocessing: grayscale, thresholding, contour detection
- Number plate detection using bounding boxes
- Character recognition using OCR (EasyOCR/Tesseract)
- Evaluation metrics: **Character Accuracy**, **Edit Distance**, **Precision**, **Recall**

## Sample Output

```
 Ground Truth     : MH12AB1234  
 Model Prediction : MH12AB1234  
 Exact Match      : Yes  
 Char Accuracy    : 100.00%  
 Edit Distance    : 0  
 Normalized ED    : 0.00  
```

## Future Work

- Improve detection under low lighting and occlusions  
- Train a custom YOLO-based plate detector  
- Deploy as a real-time web app or mobile app

##  Repository Structure

```
Number_Plate_Recognition/
├── Number_Plate_Recognition_System.ipynb   # Main notebook
├── README.md                               # Project documentation
├── images/                                 # Sample test images
├── outputs/                                # Recognized results, cropped plates
└── models/                                 # (Optional) Trained model files
```
