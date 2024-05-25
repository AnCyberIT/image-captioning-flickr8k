# **Overview**
This project implements an image captioning model using a combination of Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs) with attention mechanisms. 
The model is designed to generate descriptive captions for given images by leveraging pretrained ResNet-18 for feature extraction and an LSTM with attention for sequence generation.

# **Prerequisites**
Make sure you have the following dependencies installed:

- Python 3.x
- PyTorch
- torchvision
- spaCy
- PIL (Pillow)
- matplotlib
- pandas

# **Data**
https://www.kaggle.com/datasets/shadabhussain/flickr8k

captions.txt: A CSV file containing image filenames and their corresponding captions.

Images/: A directory containing all the images referred to in captions.txt.
