# Visual Pollution Detection Enhancement Using YOLOv5

This project focuses on enhancing an existing visual pollution detection system built on the YOLOv5 framework. Originally developed for the SDAIA Smartathon Visual Pollution Detection Challenge, the system identifies various types of urban visual pollution such as graffiti, potholes, damaged signage, and more from street images.

## Project Overview

- **Objective:** Improve detection accuracy, model stability, and generalization of the original YOLOv5-based visual pollution detector through targeted optimizations.
- **Dataset:** 6,663 annotated images across 11 categories of visual pollution.
- **Enhancements Applied:**
  - Increased input image size from 640×640 to 768×768 pixels for better feature detection.
  - Extended training duration up to 100 epochs.
  - Fine-tuned hyperparameters and controlled data augmentation for more robust training.
  - Tested and compared five YOLOv5 variants (n, s, m, l, x) to select the best trade-off between accuracy and resource use.

## Key Results

- Training on a sampled subset of 300 images at higher resolution (768×768) and longer epochs (80) outperformed baseline full dataset training.
- The enhanced YOLOv5m model achieved:
  - **mAP@0.5:** 0.389 (improved over baseline)
  - Balanced precision and recall, demonstrating effective detection performance.
- Shows that efficient training strategies and hyperparameter tuning can improve model performance under limited GPU resources.

## Conclusion

This work clearly **enhances** the original detection system by applying systematic optimizations that improve accuracy and efficiency. The results highlight the value of strategic training and model selection for practical deployment in resource-constrained environments.
