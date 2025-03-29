# Dataset information
The dataset used to train the model can be found on kaggle. Here is the link: https://www.kaggle.com/datasets/landlord/handwriting-recognition.
# Instructions for downloading this dataset into the Colab environment
1) Create an API token. To do this, you need to:
- Register on kaggle (if you don't have an account)
- Go to Settings
- Scroll down to where the API label will appear
- Then click "Create new token".
- As a result, a json file will be downloaded
2) Transfer the resulting json to Colab
3) Install the kaggle package in the colab environment using the command !pip install kaggle
4) Create a folder using the command !mkdir ~/.kaggle
5) Transfer the json file to this folder !cp kaggle.json ~/.kaggle/<Name of your json file>
6) Set the file rights using the command !chmod 600 ~/.kaggle/<Name of your json file>
7) Download the dataset to the environment using the command !kaggle datasets download landlord/handwriting-recognition
8) A zip archive will be downloaded. It can be unzipped using the command !unzip handwriting-recognition.zip
