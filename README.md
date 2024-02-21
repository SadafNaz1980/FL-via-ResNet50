# FL-via-ResNet50
Centralized and Federated Learning for COVID-19 Detection with Chest X-ray Images: Implementations and Analysis 

**System Requirements:**
---------------------
  
 GPU (i.e., NVIDIA-SMI, CUDA Version: 11.2 )
  
 GooglecolabPRO+
  
  Python
  
  Pytorch
  
  Torchvision

**Dataset:**
---------------------
  An open source data from https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database is used for the study. This dataset consists of 3616 COVID-       19 positive cases along with 10,192 Normal, 6012 Lung Opacity (Non-COVID lung infection), and 1345 Viral Pneumonia images. We focused our analysis only on 
  three classes COVID-19, Normal and Lung Opacity.

**Experiments**
---------------------

Centralized and federated learning implementations are provided in interactive python notebooks. 

**Centralized learning:**
  Deep learning code for scenario 3 using ResNet50 for 50 epochs is provided in the Python notebook https://github.com/SadafNaz1980/FL-via- 
  ResNet50/blob/main/S3_Centralized_ResNet50-Epochs50.ipynb
  
  Note: Parts of source code is taken from Kaggle notebooks.

**Federated learning:**
  FL for IID cases code is provided in the Python notebook https://github.com/SadafNaz1980/FL-via-ResNet50/blob/main/S2_10C10R_FL_ResNet50.ipynb
  
  FL for Non-IID cases code is provided in the Python notebook https://github.com/SadafNaz1980/FL-via-ResNet50/blob/main/FullData_10C10R_FedAug_ResNET50.ipynb
  
  Note: Part of the code is adapted from https://github.com/alperctnkaya/FedAug.

**Further Readings:**
---------------------

**Papers:**

[A comprehensive review of federated learning for COVID-19 detection](https://doi.org/10.1002/int.22777)

[Federated Learning: Challenges, Methods, and Future Directions](https://ieeexplore.ieee.org/document/9084352)

[A Communication Efficient Federated Learning Approach to Multi Chest Diseases Classification](https://ieeexplore.ieee.org/document/9558913)

[Improving Performance of Federated Learning based Medical Image Analysis in Non-IID Settings using Image Augmentation](https://ieeexplore.ieee.org/document/9654356)

**Blogs:**

[TensorFlow Federated](https://www.tensorflow.org/federated)

[Google AI-Federated learning](https://blog.research.google/2017/04/federated-learning-collaborative.html)

[Federated Learning: A Step by Step Implementation](https://towardsdatascience.com/federated-learning-a-step-by-step-implementation-in-tensorflow-aac568283399)
