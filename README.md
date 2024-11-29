# Chest-X-Ray-Classification-Using-Swin-Transformer

**Overview**

This repository contains an implementation of a deep learning pipeline for classifying chest X-ray images using the Swin Transformer model. The project aims to accurately diagnose conditions like Pneumonia using advanced image classification techniques and efficient model fine-tuning.

**Key Features**

Pretrained Swin Transformer: Fine-tuned on the chest X-ray dataset for image classification.
Custom Data Augmentation: Includes resizing, cropping, normalization, and random horizontal flips to improve model generalization.
Evaluation Metrics: Accuracy, confusion matrix, and classification report for detailed performance analysis.
Visualization Tools: Random test set examples and confusion matrix displays for interpretability.
Saved Model: Supports model saving and reloading for predictions on new data.
Dataset

The dataset includes augmented X-ray images categorized into labels such as Normal and Pneumonia. It is preprocessed and split into training, validation, and test sets.

Dataset Location: [Google Drive Link]([https://www.linkedin.com/in/rifhath-aslam-j-791a6a21b/](https://drive.google.com/drive/folders/1kmkWMi8AcTOAhlAvrNDQ-hLCf67GceSx?usp=sharing))

**Technologies and Tools**

**Programming Language:** Python

**Libraries:**
**Transformers:** Model and feature extractor
**Datasets:** Data loading and preprocessing
**PyTorch:** Model training and evaluation
**Scikit-learn:** Evaluation metrics and confusion matrix
**TensorFlow:** Model saving and reloading
**Matplotlib:** Visualization tools

**Results**

**Accuracy:** Achieved high classification accuracy on test data.
**Evaluation Metrics:** Detailed classification report and confusion matrix for model performance assessment.
**Visualization:** Examples of correctly and incorrectly classified images.

**Future Enhancements**

Integrate transformer-based models like Vision Transformers (ViT) for comparison.
Extend classification to include additional chest conditions.
Implement model deployment using Flask or FastAPI for real-time diagnosis.

**Contact**

**Author:** Rifhath Aslam Jageer Hussain
**Email:** rifhathaslam.jr.162@gmail.com
**LinkedIn:** [Rifhath Aslam](https://www.linkedin.com/in/rifhath-aslam-j-791a6a21b/)
