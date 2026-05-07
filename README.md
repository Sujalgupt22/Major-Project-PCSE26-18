# Monument Recognition from Satellite Images using Deep Learning with Explainable AI

## Project Overview
IndiSight++ is a Deep Learning and Explainable AI (XAI) based framework designed for recognizing historical monuments from satellite imagery. The system uses MobileNetV1 along with Grad-CAM, LIME, and SHAP to provide accurate and interpretable monument classification.

The framework helps address challenges such as:
- Background clutter
- Scale and rotation variations
- Illumination changes
- Environmental noise in satellite imagery

The proposed model achieved a test accuracy of **92.7%** on a custom monument dataset.

---

## Features
- Monument recognition using satellite images
- Explainable AI integration
- Grad-CAM visualization
- LIME and SHAP explanations
- Saliency-guided cropping
- Lightweight MobileNetV1 architecture
- User-friendly interface

---

## Technologies Used

### Programming Languages
- Python
- JavaScript

### Deep Learning
- TensorFlow
- Keras
- CNN (Convolutional Neural Networks)

### Explainable AI
- Grad-CAM
- LIME
- SHAP

### Backend
- Flask

### Frontend
- React.js

---

## System Architecture
The framework follows the following pipeline:

1. Satellite Image Input
2. Image Preprocessing
3. Data Augmentation
4. Saliency-Based Cropping
5. Feature Extraction using MobileNetV1
6. Monument Classification
7. XAI Visualization
8. Result Display

---

## Dataset
The dataset contains satellite images of multiple historical monuments collected from publicly available sources.

### Preprocessing Techniques
- Image resizing
- Normalization
- Rotation
- Flipping
- Brightness adjustment
- Zoom augmentation

---

## Model Performance
- Test Accuracy: **92.7%**
- Efficient inference using MobileNetV1
- Improved interpretability using XAI techniques

---

## Installation

### 1. Clone Repository
```bash
git clone https://github.com/Sujalgupt22/Major-Project-PCSE26-18.git
cd Major-Project-PCSE26-18
```

### 2. Install Backend Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Flask Server
```bash
python server.py
```

### 4. Run Frontend
```bash
cd frontend
npm install
npm start
```

---

## Usage
- Launch the application
- Upload a satellite image containing a monument
- The system predicts the monument class
- Grad-CAM, LIME, and SHAP explanations are generated
- Monument information is displayed to the user

---

## Explainable AI Integration

### Grad-CAM
Highlights important image regions responsible for prediction.

### LIME
Provides local explanations for individual predictions.

### SHAP
Measures feature importance contribution to the output.

---

## Future Scope
- Real-time monument detection
- GIS system integration
- Mobile deployment
- Higher-resolution satellite imagery
- Improved deep learning architectures
- Multi-modal learning

---

## Research Contribution
This project combines:
- Deep Learning
- Remote Sensing
- Computer Vision
- Explainable AI
- Cultural Heritage Preservation

The framework demonstrates how AI can assist in intelligent monument recognition and heritage preservation using satellite imagery.

---

## Acknowledgment
Special thanks to:
- Dr. Upendra Mishra
- KIET Group of Institutions

for their guidance and support throughout the project.

---

## License
This project is developed for educational and research purposes.
