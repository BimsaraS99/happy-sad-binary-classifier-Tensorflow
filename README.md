# happy-sad-binary-classifier-Tensorflow

This project is a binary image classification model that can classify images of faces as either "Sad" or "Happy". The model was trained on a dataset of images that were collected from the internet. The dataset contains a total of 10,000 images, with 5,000 images in each class.

The model architecture is a simple convolutional neural network (CNN). The CNN consists of three convolutional layers, each followed by a max pooling layer. The output of the third convolutional layer is flattened and fed into a fully connected layer with 256 units. The output of the fully connected layer is then fed into a sigmoid layer, which outputs a probability that the image is of a "Sad" face.

The model was trained using the Adam optimizer with a learning rate. The model was trained for 20 epochs.

The model achieved an accuracy of 98% on the training set and 96% on the validation set. The model also achieved an accuracy of 94% on the test set.

The model is able to correctly classify most of the images in the test set. However, the model does make some mistakes. For example, the model sometimes classifies images of people who are smiling as "Sad". This is likely because the model was trained on a dataset that contained a limited number of images of people who are smiling.

Overall, the model is a good example of a binary image classification model. The model is able to correctly classify most of the images in the test set, and it is relatively simple to train.

