## Image Classifier for Dogs

A program that classifies images as dogs with their 
corresponding breed.

#### Key tasks
1. Determines which image classification algorithm works 
best on classifying images as dogs or not dogs
1. Determines how well the best algorithm works on 
correctly identifying a dog's breed
1. Times how long each algorithm takes to solve the 
classification problem.

###### Notes
The application uses the deep learning model called a 
convolutional neural network (CNN).
[CNNs](https://www.tensorflow.org/tutorials/images/cnn) 
work particularly well for detecting features in images like 
colors, textures, and edges; then using these features to 
identify objects in the images

This project will be exploring the three different 
architectures
(AlexNet, VGG, and ResNet)

### Setup
1. Clone the project `git clone git@github.com:Ashaba/image-classifier.git`
1. `cd image-classifier`
1. Make sure to run project within the python virtual environment
1. Activate your virtualenv and
1. `pip install -r requirements.txt`

#### Running the application
1. Look out for the `uploaded_images` folder in the project directory
1. Add around four images you would want to classify

> first image of a real dog should be named Dog_01.jpg

> second image can be any random image eg car-image.jpg

> third image could be a pet image that's not a dog eg cat.jpg

> any other random image

The goal is to be able to identify the breed of the Dog_01.jpg 
to it's corresponding breed.

1. Upon adding those images run `sh run_models_batch_uploaded.sh`

1. This will classify the added images with the different CNN 
models and outputs results in text files.
eg for VGG, the output can be found in `vgg_uploaded-images.txt`

You should be able to view something like this:
