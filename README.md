# Chicken-Disease-Classification

## Problem Statement
To detect diseases in chickens at an early stage using deep learning techniques, preventing mortality in chickens, farmers loss due to mortality among chickens and ultimately keeping us healthy too. The aim of this project is to develop a very intelligent system for the early identification of various diseases in chickens. VGG16 from Keras Applications was implemented for the categorical classification of "Coccidiosis" and "Healthy."


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml


## How to run this in local
Before you run the project, make sure that you are configuring your AWS S3 Bucket called as chicken-fecal-images, that contains a zip file named chicken-fecal-images.zip that in turn has a folder named chicken-fecal-images which has two folders, namely coccidiosis and healthy. Now within each of these aforementioned folders contains the fecal images of coccidiosis infected chicken and a healthy chicken respectively.


### STEPS:
Clone the repository
https://github.com/Sujata2017/Chicken-Disease-Classification.git


### STEP 01- Create a conda environment after opening the repository
conda create -n cnncls python=3.8 -y
conda activate cnncls

### STEP 02- install the requirements
pip install -r requirements.txt

### Finally run the following command
python app.py
