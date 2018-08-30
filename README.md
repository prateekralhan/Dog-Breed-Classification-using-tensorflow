# Dog-Breed-Classification-using-tensorflow

In this project,I build a model to identify dog breeds in an image.

We will use the Kaggle's Dog Breed Dataset dataset for training. With 120 breeds of dogs and a limited number training images per class, you might find the problem more, err, ruff than you anticipated.To speed things up, we will apply Transfer Learning by building new layers on top of the Xception model pre-trained on ImageNet to classify the top 10 dog breeds. 

Note: We have reduced the number of classes (i.e. dog breeds) to 10 to fit the model in a CPU machine.

We will:

    Preprocess images data for computer vision tasks
    Transfer Learning: build new layers on top of the pretrained Xception model using Keras and Tensorflow
    Evaluate our model on the test set
    Run the model on new dog images anywhere from the web! Just enter the image URL and you are good to go!!
