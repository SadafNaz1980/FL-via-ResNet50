# FL-via-ResNet50
Centralized and Federated Learning for COVID-19 Detection with Chest X-ray Images: Implementations and Analysis 

System requirements:
  GPU (i.e., NVIDIA-SMI, CUDA Version: 11.2 ) and GooglecolabPRO+
  
Dataset:
  An open source data 2nd update from https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database is used for the study. This dataset consists of 3616     COVID-19 positive cases along with 10,192 Normal, 6012 Lung Opacity (Non-COVID lung infection), and 1345 Viral Pneumonia images. We focused our analysis only on 
    three classes COVID-19, Normal and Lung Opacity.

Centralized learning source code:
  Deep learning souce code for scenario 3 using ResNet50 for 50 epochs is provided in the Python notebook https://github.com/SadafNaz1980/FL-via- 
  ResNet50/blob/main/S3_Centralized_ResNet50-Epochs50.ipynb
  Note: Parts of source code is taken from Kaggle notebooks.

Federated learning source code for IID cases:
  FL for IID cases source code is provided in the Python notebook https://github.com/SadafNaz1980/FL-via-ResNet50/blob/main/S2_10C10R_FL_ResNet50.ipynb

Federated learning source code for Non-IID cases:
  FL for Non-IID cases source code is provided in the Python notebook https://github.com/SadafNaz1980/FL-via-ResNet50/blob/main/FullData_10C10R_FedAug_ResNET50.ipynb
  Note: FL for Non-IID code is sourced from "Federated Augmentation Framework to improve FL in non-IID Settings" 
  https://github.com/alperctnkaya/FedAug/blob/main/FedAug.ipynb  
