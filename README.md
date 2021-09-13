# In this tutorial we will be building facial expression classifiers for a labelled dataset FER2013. 

We will be first using two basic classifiers, Multi-Layer perceptron model (MLP) and CNN-based model to perform the classification. Then we will use transfer learning (ResNet50 pretrained on VGGFace2 dataset) to achieve better performance over the basic classifiers.

## Install necessary python packages 

Run the below commands if these packages are not installed in your system. 

- pip install pandas
- pip install torch
- pip install -U scikit-learn

For visualisation

- pip install matplotlib
- pip install seaborn

You can also use conda to install the packages.

## Obtaining the data 

Download the data from the below link (icml_face_data.csv) and save it in the project folder </br>  
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data?select=icml_face_data.csv

## Project structure

    .
    ├── A basic example FER                   # MLP and CNN model notebook
    ├── Transfer_learning_example.ipynb       # Transfer-learning notebook
    ├── icml_face_data.csv                    # Data, download from the link given above
    ├── resnet50_scratch_weight.pkl           # Pre-trained weights for transfer learning, download from the link given
    └── README.md

## Running in colab (For the transfer learning part)

This code uses GPU and can be ran on Google Colab. Steps:

- Upload the project folder to your Google Drive.
- Open this project with Google Colaboratory
- At Runtime option, click on Change Runtime type and Change it from None to GPU.

You are good to go! Start implementing the code below.


## Credits

- https://www.kaggle.com/alinaspasskaya/lab-2-face-emotion-classification-with-mlp
- https://www.kaggle.com/sharadhaviswanathan/imageclassification-facialexpression
- https://github.com/cydonia999/VGGFace2-pytorch/