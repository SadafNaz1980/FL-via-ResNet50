# FL-via-ResNet50
Centralized and Federated Learning for COVID-19 Detection with Chest X-ray Images: Implementations and Analysis 

**System requirements:**
  GPU (i.e., NVIDIA-SMI, CUDA Version: 11.2 ) and GooglecolabPRO+

**Dataset:**
  An open source data 2nd update from https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database is used for the study. This dataset consists of 3616     COVID-19 positive cases along with 10,192 Normal, 6012 Lung Opacity (Non-COVID lung infection), and 1345 Viral Pneumonia images. We focused our analysis only on 
    three classes COVID-19, Normal and Lung Opacity.

**Centralized learning:**
  Deep learning code for scenario 3 using ResNet50 for 50 epochs is provided in the Python notebook https://github.com/SadafNaz1980/FL-via- 
  ResNet50/blob/main/S3_Centralized_ResNet50-Epochs50.ipynb
  Note: Parts of source code is taken from Kaggle notebooks.

**Federated learning:**
  FL for IID cases code is provided in the Python notebook https://github.com/SadafNaz1980/FL-via-ResNet50/blob/main/S2_10C10R_FL_ResNet50.ipynb
  
  FL for Non-IID cases code is provided in the Python notebook https://github.com/SadafNaz1980/FL-via-ResNet50/blob/main/FullData_10C10R_FedAug_ResNET50.ipynb
  
  Note: Code is sourced from the paper "Federated Augmentation Framework to improve FL in non-IID Settings" 
  "A. E. Cetinkaya, M. Akin and S. Sagiroglu, "Improving Performance of Federated Learning based Medical Image Analysis in Non-IID Settings using Image Augmentation,"   2021 International Conference on Information Security and Cryptology (ISCTURKEY), 2021, pp. 69-74, doi: 10.1109/ISCTURKEY53027.2021.9654356." 
