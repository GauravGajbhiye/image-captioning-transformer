# image-captioning-transformer
Neural Image Captioning with Transfer Learning and Transformer

This repository contains three .ipynb files, along with our project presentation and report.
model1 - employs InceptionV3 Network for feature extraction, and RNN with GRUs and Attention for caption generation
model2 - employs Xception Network for feature extraction, and RNN with GRUs and Attention for caption generation
model3 - employs Xception Network for feature extraction and Transformer Model for caption generation

Description:
- developed a neural network model that automatically describes the contents of an image.
- involved efficiently extracting the image features with Transfer learning from 'Xception' deep CNN architecture that was pre-trained on ImageNet and generating captions using 'Transformer' - a mechanism based solely on self-attention layers
- achieved higher BLEU-1,2,3,4 scores on Flickr8k data set when compared with conventional captioning models that used VGG16 encoder and LSTM-based decoder
- used Python, TensorFlow, Keras, NLTK, OpenCV, NumPy, Scikit-learn
- part of the course 'CSE 676 - Deep Learning' at University at Buffalo, SUNY
