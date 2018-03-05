# Predicting the best-liked photo from a time-series of photos 

This project was a part of a course project for the COMPSCI 689, advanced machine learning course at UMass Amherst . It is based on the princeton adobe-photo triage project. (http://phototriage.cs.princeton.edu/). 
The goal is to find the best image from a set of similar images.Usually people would take a lot of pictures of the same scene but it is an effort to manually sift through the album and find the best image.

Our proposed model (a team of 2) involves a *siamese neural network architecture* which uses a ranking loss function to rank two similar images based on the aesthetic quality. We experimented with two architecture for each siamese network, VGG19 and Inception v3. The model achieved an accuracy of 71 % on the test data. 

 + Used Pytorch.
 + The dataset can be obtained here. (http://phototriage.cs.princeton.edu/download.html)
