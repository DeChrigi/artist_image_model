# Project Goal and Motivation

The aim of this project is to develop a Convolutional Neural Network (CNN) model capable of predicting the artist of a given artwork. 
This project seeks to explore the application of deep learning techniques in the field of art history and digital humanities, 
providing a tool that can assist in the classification and identification of artists based on their unique styles and techniques.

Art identification and authentication have traditionally relied on the expertise of art historians and experts who analyze the style, 
technique, and material composition of artworks. However, with the advent of digital technology and the availability of large datasets of digitized artworks, 
there is an opportunity to leverage machine learning to automate and enhance these processes.

Convolutional Neural Networks (CNNs) are particularly well-suited for image classification tasks due to their ability to capture features within images. 
By training a CNN model on a diverse dataset of artworks attributed to various artists, the model can learn to recognize patterns and features specific to each artist's style (in theory). 
This not only aids in artist identification but also provides insights into stylistic influences and the evolution of artistic techniques over time.

The development of such a model has significant implications for art conservation, curation, and academic research. 
It can serve as a valuable tool for museums, galleries, and collectors in verifying the authenticity of artworks and understanding their provenance. 
Additionally, it can support educational initiatives by offering a technological perspective on art analysis, complementing traditional methods.

# Data Collection 

The image dataset was sourced from the following URL: https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time.

This dataset comprises paintings from 50 renowned artists, with each artist contributing between 24 and 877 artworks. A detailed analysis of the dataset can be found in the notebook titled "dataset_analysis."

The downloadable file, "archive.zip," contains all the paintings organized into folders corresponding to each artist. I extracted and cleansed the data to correct naming errors in the folder structure, as detailed in the script "renameData.py."

Subsequently, the paintings were divided into training and testing sets. The training set was exclusively used to train the models, while the test set was reserved for validating the models with previously unseen paintings.

# Modeling


