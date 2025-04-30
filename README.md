# Efficient Object Detection Framework for Indian Road Scenarios Under Foggy Conditions Using YOLOv8

🚗 A real-time object detection system tailored for **Indian road environments**, optimized with **YOLOv8 Nano**, handling diverse challenges such as fog, low visibility, dense traffic, and erratic driving behavior.

---

## 📌 Project Overview

This project aims to enhance **road safety and navigation** by leveraging YOLOv8 Nano for **real-time object detection and classification** on Indian roads. Designed with **resource-constrained deployment** in mind (e.g., autonomous vehicles), it achieves high precision even under adverse weather and lighting conditions.

---




**Under the guidance of:** Dr. Prema T. Akkasaligar  
**Institute:** KLE Technological University, Belagavi

---

## 🎯 Objectives

1. Develop a YOLOv8-based detection system optimized for Indian roads.
2. Handle traffic density, varied road users, and adverse weather conditions.
3. Ensure performance in **real-time** and **low-resource** environments.

---

## 🧠 Model Architecture

- **Model Used**: YOLOv8 Nano
- **Key Steps**:
  - Load and normalize image data
  - Object detection using YOLOv8
  - Assign labels, bounding boxes, and confidence scores
  - Annotate and save output images

---

## 📊 Dataset

- **Name**: DATS_2022
- **Size**: 1,861 training images and 566 validation images
- **Classes**: 35 object categories (e.g., bike, car, bus, pedestrian, signboard, cattle, rickshaw, etc.)
- **Augmentations**: Rotation, flipping, brightness tuning for weather robustness

🔗 [Dataset Link](https://data.mendeley.com/datasets/nfc34n8svj/2)

---

## 🔍 Results

- **Precision**: 0.98 at confidence threshold 1.0
- **Observations**:
  - High accuracy in detecting large objects (e.g., buses, trucks)
  - Improvement needed for smaller, occluded objects
- **Loss Trends**:
  - Validation loss decreases steadily, indicating good generalization
  - Training loss shows overfitting in later epochs, requiring tuning

---

## 🌐 Use Cases

- Smart traffic monitoring
- Autonomous vehicle navigation
- Pedestrian safety systems
- Road safety analytics under poor visibility

---

## 🚀 Future Enhancements

- Expand dataset with nighttime and rain conditions
- Deploy on low-power embedded systems
- Explore integration with traffic control systems

---

## 📚 References

- Multiple studies comparing YOLOv5 vs YOLOv8 on Indian roads
- Use of CNNs, LSTMs, KNNs, and background subtraction for robust detection
- Evaluations using mAP, precision, recall, and Dice score

---

## 🖼 Sample Outputs

| Scenario      | Before Detection        | After Detection         |
|---------------|--------------------------|--------------------------|
| Daylight      | ![Daylight](sample_day.jpg) | ![Detected](detected_day.jpg) |
| Foggy Weather | ![Fog](sample_fog.jpg)     | ![Detected](detected_fog.jpg) |

*(Replace with actual images if available)*

---

## 📌 Note

All large files (e.g., `.zip` or video datasets) are excluded from this repository. Refer to the dataset link above to download the required files.

---

## 🤝 Acknowledgements

Special thanks to **Team Memebers Anurag Chougule And Mrunali Bennalkar ** for her continuous guidance and support throughout the project.

---

