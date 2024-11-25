# PALM_BONE_FRACTURE_DETECTION

This repository contains a deep learning-based system for detecting and classifying bone fractures using X-ray images. It also includes a Tkinter-based GUI for user-friendly interaction, allowing users to upload X-ray images and receive predictions in real-time.

---

## **Overview**

Bone fractures are a common medical issue requiring precise and timely detection. This project leverages a convolutional neural network (CNN) to:  
1. Detect the presence of a fracture.  
2. Classify the fracture into specific types, such as Impacted or Intra-articular.  
3. Highlight the fractured area using OpenCV-based visualization.  

The model is trained on a curated dataset of X-ray images and aims to achieve high accuracy (>92%) while maintaining explainability through visual overlays.

---

## **Features**
- **Fracture Detection:** Identify whether a bone fracture is present in the X-ray.  
- **Fracture Classification:** Categorize the fracture into its type.  
- **Visualization:** Highlight the fractured area for better interpretability using OpenCV.  
- **Interactive GUI:** A Tkinter-based interface for easy image uploads and output display.  

---

## **Technologies Used**
- **Deep Learning Frameworks:** TensorFlow / PyTorch  
- **Computer Vision:** OpenCV  
- **Frontend Interface:** Tkinter (for GUI)  
- **Programming Language:** Python  
- **Hardware:** GPU acceleration for model training  

---

## **Requirements**
- Python 3.8+  
- pip (Python package installer)  

Install the necessary dependencies using:  
```bash
pip install -r requirements.txt
