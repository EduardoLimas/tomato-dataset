# Datasets utilizados no estudo

### Dataset 01:

Source: Rahaman, Tohidur ; Sarkar, Tanmay (2024), “TOMATO”, Mendeley Data, V1, doi: 10.17632/hfyth5t3gg.1

Avaiable on: https://data.mendeley.com/datasets/hfyth5t3gg/1

--Copyright on dataset 01: We did some data cleaning and modified the dataset. To check the original dataset, please visit the link above. 

--The dataset was licenced under CC BY 4.0

--To cut the images borders we did some in manual mode (native editor in Windows) and some using the batch feature from https://pt.imgtools.co/crop-image

### Dataset 02:

--Images were captured using a Samsung S24+ mobile camera. We used daylight in field conditions.

--The dataset was separated into folders in a random 80% training, 20% test ratio, maintaining balance between classes using the ScikitLearn library, generating a .csv template for each dataset for reproducibility purposes.

-- Classes were classified by a specialist 

### Dataset 03: Dataset 01 + Dataset 02

--The dataset was created by merging the two datasets.

### About the train and test split:

[train_testsplit.py](train_testsplit.py)--> split train and test samples and create the labels for the images


#### Labels:

1 = Good, 0 = Bad
