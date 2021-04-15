# DeepFake-Detection-Project
We are trying to detect deepfake videos. Here we are using a dataset from Kaggle where the annotations are stored in a json file in the train sample videos folder.

Steps:

* Reading the videos and taking images from it
* Reading the label in the json file and store the image in a folder according to it's label
* Converting the image to an array and splitting the data into train and test
* Customizing the InceptionResNetV2 and training the data on it
* Testing

Trained model : https://drive.google.com/drive/folders/1ipx5F9O7WG4GCvFtU5inu79OznYYElYv?usp=sharing
