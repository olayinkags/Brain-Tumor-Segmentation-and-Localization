Brain Tumor Detection and Localization using ResNet50 and ResUNet (Transfer Learning)
📌 Project Overview

This project applies Artificial Intelligence (AI) and Deep Learning to improve the speed and accuracy of detecting and localizing brain tumors from MRI scans.

The aim is to:

Reduce the cost of cancer diagnosis

Enable early detection and treatment of brain tumors

Provide a scalable AI-assisted solution for healthcare

We leverage classification + segmentation models:

ResNet Classifier – detects whether an MRI contains a tumor.

ResU-Net Segmentation Model – localizes the tumor at the pixel level if present.

🧠 Why AI in Healthcare?

Early detection of diseases like cancer saves lives.

AI models can process thousands of images faster than human experts.

Deep learning enables pixel-level image understanding, useful in tumor localization.

Integrating AI reduces workload on radiologists while increasing accuracy.

📊 Dataset

3,900 Brain MRI scans provided.

Each MRI has an associated mask image that highlights tumor location.

Dataset is imbalanced:

~65% healthy (no tumor)

~35% tumor present

Example:

MRI Image: Patient brain scan

Mask Image: Shows tumor pixels (if present)

🔧 Project Workflow

Data Exploration & Visualization

Load MRI scans + masks

Analyze class distribution

Visualize healthy vs tumor samples

Stage 1 – Classification

Train a ResNet deep learning classifier

Predict whether a tumor is present

Stage 2 – Segmentation

If tumor detected, apply ResU-Net segmentation

Pixel-level tumor localization

Model Outputs

Tumor probability (classification)

Tumor mask overlay (segmentation)
