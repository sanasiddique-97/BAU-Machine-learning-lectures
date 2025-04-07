# Assignment 1: Image Classification with Pretrained Models
Task: Use pretrained AlexNet and ResNet to classify images and compare their performance.

import torch
from torchvision import models, transforms
from PIL import Image

# 1. Load and preprocess an image (use any image of your choice)
# 2. Load pretrained AlexNet and ResNet-18
# 3. Make predictions with both models
# 4. Compare the top-5 predictions from both models
# 5. Answer: Which model performs better? Why?



# For data you can download from the following links:

Cancer Imaging Datasets for Student Reference
1.	The Cancer Imaging Archive (TCIA):
Access the data here:
🔗 https://www.cancerimagingarchive.net/access-data/
2.	Blood Cancer (Acute Myeloid Leukemia - AML) Dataset:
This dataset contains 10,000 single-cell images (64x64 pixels) captured from peripheral blood smears of patients diagnosed with Acute Myeloid Leukemia (AML). The images are sourced from The Cancer Imaging Archive (TCIA).
🔗https://doi.org/10.7937/tcia.2019.36f5o9ld
Alternative Download Source:
🔗 https://www.kaggle.com/datasets/akhiljethwa/blood-cancer-image-dataset
4.	Cancer Imaging Data Commons (IDC):
Explore this platform for additional datasets and information:
🔗 https://portal.imaging.datacommons.cancer.gov/
Related article:
🔗 https://cloud.google.com/blog/topics/developers-practitioners/advancing-cancer-research-public-imaging-datasets-national-cancer-institute-imaging-data-commons
5.	Lung Cancer Dataset (Kaggle):
🔗 https://www.kaggle.com/datasets/adityamahimkar/iqothnccd-lung-cancer-dataset
6.	Skin Cancer Dataset (HAM10000 - Kaggle):
🔗 https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000



