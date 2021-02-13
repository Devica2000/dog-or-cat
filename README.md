# dog-or-cat
This code is the classic example to learn about image classification using neural networks. The dataset was taken from Kaggle. Refer to https://www.kaggle.com/chetankv/dogs-cats-images for dataset. 
I have used VGG 16 to classify. This means that the input image size is 224 x 224 x 3. The imagenet weights were used to classify since I had imported the VGG 16 model. I used the Sigmoid activation function in the last/output layer since this is a binary classification. For loss, binary cross entropy function was used and Adam was used as an optimizer. Ran the model for 10 epochs. The model gave a pretty decent accuracy of 96.56. 
For the test image, I took an unknown image of a cat. The model correctly classifies a dog and a cat. 
