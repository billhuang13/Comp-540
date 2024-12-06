# Comp-540 Term Project
This project aims to classify and segment images with pneumothorax. 
The dataset was provided by “Society for Imaging Informatics in Medicine” (SIIM) and is a part of Kaggle competition, namely the SIIM-ACR Pneumothorax Segmentation competition.
- `dataexploration.py` includes the entire data cleaning and wrangling process.
- `classification.py` includes the code of the classification models. A total of three models were created for this task. The first one is a CNN model, the second one is a pre-trained ResNet-18 model, and the last one is a DenseNet-121 model.
- `segmentation.py` include the models used for segmentation. Two pre-trained models are created, where the first one is a UNet model with ResNet-18 as its encoder, and the second one is a UNet model with VGG-13 as its encoder
