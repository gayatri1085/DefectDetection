# Shoe Sole Defect Detection 🥿🔍

A computer vision project to automatically detect defects in shoe soles using YOLO-based deep learning models. The system supports real-time detection on camera feeds for quality control in manufacturing.

---

## 🚀 Features
- Manual dataset creation from shoe insole samples.
- Annotation of defects using [MakeSense.ai](https://www.makesense.ai/).
- YOLO-based object detection for defects like cracks, deformations, and misprints.
- Real-time camera feed defect detection.
- Achieved **82% accuracy** on the test dataset.

---

## 🎯 Motivation
Manual inspection of shoe soles is time-consuming and prone to errors. Automating defect detection ensures faster, consistent, and reliable quality control, reducing manufacturing errors.

---

## 🗂 Dataset
- Images captured manually from shoe soles.
- Annotated defect categories:
     - logo_peel_off        
     - double_printing_logo        
     - logo_dust         
     - logo_displacement   
- Dataset split: **80% training, 20% validation**
- Annotations saved in YOLO format (`.txt`) corresponding to images.

