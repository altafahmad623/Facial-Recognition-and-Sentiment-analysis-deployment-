# Facial-Recognition-and-Sentiment-analysis-deployment-
Sentiment analysis of a live video stream or a recorded video. Categorises into 7 different sentiments like happy, sad, angry etc.
We built and trained a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

The pretrained model has already been saved in "model_weights.h5"
 # Usage
 Run the main.py file
  If you want to check it on a Video, change the source in camera.py from "self.video = cv2.VideoCapture("/home/altaf/fin2al/project_fl/videos/pk.mkv")" to self.video = cv2.VideoCapture(0)
