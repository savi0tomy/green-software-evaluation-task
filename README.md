**MRI CLASSIFICATION WITH RESNET AND EFFICIENTNET**

This project analyzes the energy consumption and performance of two pre-trained models (ResNet-18 and EfficientNet-B0) on an MRI brain tumor classification task.

**Project Overview**

The goal of this project is to classify MRI images into 4 categories:

-meningioma

-no tumor

-glioma

-pituitary

**Models Used**

-ResNet-18

-EfficientNet-B0

**Energy Profiling Tool Used:Codecarbon**

https://codecarbon.io/

It is used to track energy consumption and CO₂ emissions during model training and evaluation.

**Dataset**

MRI Brain Tumor dataset (downloaded via Kaggle)

https://www.kaggle.com/api/v1/datasets/download/masoudnickparvar/brain-tumor-mri-dataset?dataset_version_number=1

**How to run the code**
1. clone the repository
2. setup the environment. Ensure that python and required packages are installed
3. Run the notebook

**Results**

| Model           | Test Accuracy | Energy Consumption (kWh) | CO₂ Emissions (kg) |
| --------------- | ------------- | ------------------------ | ------------------ |
| ResNet-18       | 96.72%        | 0.01298 kWh              | 0.004532 kg        |
| EfficientNet-B0 | 99.31%        | 0.02153 kWh              | 0.007520 kg        |



