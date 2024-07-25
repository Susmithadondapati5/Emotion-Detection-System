# FacialRecognitionUsingCNN

Emojis or avatars are ways to indicate nonverbal cues. These cues have become an essential part of online chatting, product review, brand emotion, and many more. It also lead to increasing data  science research dedicated to emoji-driven storytelling.

With advancements in computer vision and deep learning, it is now possible to detect human emotions from images. In this deep learning project, we will classify human facial expressions to filter and map corresponding emojis or avatars.

About the Dataset
The FER2013 dataset ( facial expression recognition) consists of 48*48 pixel grayscale face images. The images are centered and occupy an equal amount of space. This dataset consist of facial emotions of following categories:

0:angry
1:disgust
2:feat
3:happy
4:sad
5:surprise
6:natural

We will build a deep learning model to classify facial expressions from the images.In the below steps will build a convolution neural network architecture and train the model on FER2013 dataset for Emotion recognition from images.

1. Download the dataset from the above link.
2. Imports.
3. Initialize the training and validation generators
4. Build the convolution network architecture
5. Compile and train the model
6. Save the weights
7. Using openCV haarcascade xml detect the bounding boxes of face in the webcam and predict the emotions

we have built a convolution neural network to recognize facial emotions. We have trained our model on the FER2013 dataset.Using OpenCV’s haar cascade xml we are getting the bounding box of the faces in the webcam. Then we feed these boxes to the trained model for classification.
