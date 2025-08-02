# 🌾 Crop and Weed Detection Using YOLOv8

This project uses a YOLOv8 deep learning model for precision agriculture to detect crops and weeds from aerial images.

## 🔍 Model Performance
- **mAP@0.5**: 93.1%
- **Recall**: 86.1%
- **Precision**: 85.5%
- **mAP@50–95**: 68.9%

## 🧪 Highlights
- Trained with high-recall augmentation strategies (mosaic, copy-paste, mixup)
- Optimized for minimal false negatives in agricultural scenarios
- Custom prediction script and confusion matrix evaluation included

## 🛠️ Tech Stack
Python, PyTorch, Ultralytics YOLOv8, OpenCV

## 📁 Folder Overview
- `yolo_high_recall_attempt/`: project code and training config
- `predict7/`: prediction results on test data
