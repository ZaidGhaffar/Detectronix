# Detectronix:  Build Your Own Object Detector from Scratch

**Detectronix** is a fully-automated, notebook-based object detection pipeline. Upload as few as **30 images**, and this tool walks you through **data labeling**, **automatic annotation**, **data augmentation**, **model training**, and even **hyperparameter tuning** – all in one place!

---

## 🚀 Features

✅ Add your own dataset (even just 30 images)  
✅ Built-in labeling and auto-annotation tools  
✅ Data augmentation using `Albumentations`  
✅ Supports custom object detection training (YOLO/SSD/etc.)  
✅ Hyperparameter tuning & optimization  
✅ Visual training metrics: loss, accuracy, and more  
✅ Modular, readable code – all inside a Jupyter Notebook


## 🛠️ Pipeline Overview

### 1. 📸 Upload Images
Upload 30+ images to the `/data/images/` folder or directly via notebook cells.

### 2. 🏷️ Data Labeling & Annotation
- Use built-in manual labeling tools (like LabelImg or CVAT)
- Or opt for **Automatic Annotation** using pre-trained models (COCO, YOLOv8)

### 3. 🧪 Data Augmentation
Augment dataset using the powerful [Albumentations](https://albumentations.ai/) library with:
- Random crop
- Flip
- Color shift
- Rotation
- Noise injection

### 4. 🧠 Model Training
- Train a YOLO/SSD/Faster-RCNN-based model from scratch
- Customize layers, learning rate, batch size, optimizer, etc.
- Save and export your trained model with ease

### 5. ⚙️ Hyperparameter Tuning
- Use grid/random search to find optimal:
  - Learning rate
  - Optimizer type
  - Scheduler
  - Batch size

### 6. 📉 Loss & Metrics Tracking
- Visualize training/validation loss
- Precision, Recall, mAP, F1-score
- Confusion matrix and prediction overlay

---

## 🔧 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
