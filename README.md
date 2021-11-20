# LSTM-Text-to-Emoji
## About the Project
-This project aims to build efficient and light deep learning model that predicts the emoji from given input text.

## How to run the project ?
-virtualenv env

-env/scripts/activate

-pip install -r requirements.txt

-Download the embeddings file which needs to be present in emojifier_DeepLearningCode/embedding/ with name "glove.6B.50d.txt" -python manage.py runserver.

## Files Description

### emojifier_DeepLearningCode/
This folder contains the deep learning portion of the project.

emojifier_DeepLearningCode/dataset : this contains sample dataset which was used for training

emojifier_DeepLearningCode/embedding : this folder should contain the glove vector embedding.(refer readme.txt to download)

emojifier_DeepLearningCode/trainedModel : trained model weights and architecture get saved here![3](https://user-images.githubusercontent.com/43823465/142716902-ae91134f-ab3d-4509-97cc-d7cf77752dba.jpeg)


emojifier_DeepLearningCode/train.py : training code to train a deep learning model

emojifier_DeepLearningCode/predict.py : this is used to make predictions using trained model

### emojifierProject/
This folder contains the files which are needed to spin up django server

### main/
This contains the django application which contains the views and urls for our project

### templates/
It contains the frontend templates used in the project

## Adding Screenshots![Screenshot (95)](https://user-images.githubusercontent.com/43823465/142716707-cf237ff8-e836-4fde-a607-326f7cdb5d0c.png)
![Screenshot (97)](https://user-images.githubusercontent.com/43823465/142716711-3dd67a68-2db9-4d31-b075-e8d94f02afcd.png)![3](https://user-images.githubusercontent.com/43823465/142716908-e23ccc45-8d1a-4cca-99ed-1aafc0aac7e8.jpeg)


