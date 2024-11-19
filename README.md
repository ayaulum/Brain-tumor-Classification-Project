# Brain Tumor Classification Project

This project implements a ResNet-18-based deep learning model for classifying brain tumor images into four categories: Glioma, Meningioma, Pituitary, and Healthy.

## Project Overview
- **Baseline Model**: Fine-tunes the fully connected head.
- **Enhanced Model**: Fine-tunes `layer4` and the fully connected head, achieving 100% accuracy.

## Dataset
- The dataset is available on [Kaggle](https://www.kaggle.com/rm1000/brain-tumor-mri-scans).
- Download the dataset and place it in the `datasets/` folder.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
