# Smart-Invigilation-System
**Automated Invigilation System for Offline Exam  Monitoring using Deep Learning**
This repository contains code for object detection using YOLOv8 on a custom CCTV dataset obtained from BVRIT HYDERABAD. The project applies deep learning techniques to detect suspicious behaviors in an offline examination setting, leveraging a model trained on the xamDataSetv2 dataset. This model achieves high accuracy in identifying specific activities such as cheating and normal behavior in exam halls.

**Features******
Model: YOLOv8 for object detection
Dataset: Custom exam dataset (xamDataSetv2)
Preprocessing: Grayscale padding, adaptive anchor calculation, and mosaic augmentation
Training: TensorFlow and PyTorch on Google Colab, utilizing early stopping for optimal performance
Performance
Achieved 98% accuracy with precision, recall, and F1-score of 73%, 91%, and 80.6% respectively.

**Requirements**
Python 3.x
TensorFlow
PyTorch
Google Colab environment for GPU support


![val_batch2_labels](https://github.com/user-attachments/assets/7deace98-6eef-4a61-a8dc-a9e07b858848)
![val_batch1_labels (1)](https://github.com/user-attachments/assets/90191428-19f3-43a4-9ca6-e554e0666cf0)
![val_batch0_labels](https://github.com/user-attachments/assets/24d59ca0-259d-4c40-b665-67facefe4a42)

