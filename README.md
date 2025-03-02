# Object Detection and Image Processing

## Description
This repository contains Jupyter Notebooks and scripts for **object detection** and **image processing**, specifically designed for RGB, TIR (Thermal Infrared), and RGB-TIR fused datasets. The notebooks include tools for:
- Installing dependencies and setting up the environment.
- Mounting Google Drive for data access.
- Applying various image processing filters (e.g., Gaussian blur, edge detection, etc.).
- Visualizing processed images and comparing results.
- Training custom object detection models using YOLOv7.

The repository is designed for researchers and developers working on multi-modal (RGB + TIR) object detection tasks.

---

## Features
- **Image Processing**: Tools for applying filters like Gaussian blur, edge detection, and more.
- **Custom Dataset Support**: Scripts to process and fuse RGB and TIR images.
- **Visualization**: Preview windows to compare processed images.
- **YOLOv7 Integration**: Notebooks for training custom object detection models using YOLOv7.
- **Google Drive Integration**: Easy integration with Google Drive for data storage and retrieval.

---

## Notebooks Overview
### 1. **Copy_of_RGB_LWIR_image_processor.ipynb**
- **Dependencies Installation**: Installs necessary libraries like `matplotlib`, `pandas`, `numpy`, `opencv`, and `tensorflow`.
- **Google Drive Mounting**: Connects the notebook to Google Drive for data access.
- **Image Processing**: Applies filters like Gaussian blur, edge detection, and more.
- **Visualization**: Previews processed images for comparison.

### 2. **Copy_of_RGB_LWIR_image_processor.ipynb**
- **File Path Setup**: Defines paths for RGB, TIR, and fused datasets.
- **Image Processing Script**: Reads and saves processed images from Google Drive.
- **Filter Customization**: Allows users to enable/disable filters by commenting/uncommenting code.

### 3. **Copy_of_VOLOv7_train_test_left.ipynb**
- **YOLOv7 Setup**: Clones the YOLOv7 repository and installs dependencies.
- **Custom Training**: Trains custom object detection models on RGB, TIR, and RGB-TIR fused datasets.

---

## Installation
To use the notebooks in this repository, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/afrahshah/Object-Detection-and-Image-Processing.git
   cd Object-Detection-and-Image-Processing
2. **Install dependencies**:
   ```bash
   !pip install matplotlib pandas numpy opencv-python tensorflow
 ## Usage
## **Image Processing**:
 - Open the notebook (`Copy_of_RGB_LWRB_image_processor.ipynb` or `Copy_of_RGB_UMR_image_processor.ipynb`).
- Mount Google Drive and set the file paths.
- Run the image processing script to apply filters like Gaussian blur, edge detection, etc.
- Preview the processed images using the visualization tools.
##  **Training Custom Models**:
 - Open the notebook (`Copy_of_VOLOv7_train_test_left.ipynb`).
- Clone the YOLOv7 repository and install dependencies.
- Train custom models on your RGB, TIR, or RGB-TIR fused datasets.
## Examples
## **Fused Image Detection**:
![image](https://github.com/user-attachments/assets/bb26cf1d-0f6e-41e4-999e-a5ca20cac476)

    
