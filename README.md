# Smart_Waste_Management_Model

Purpose: 
Recycling waste material is a huge challenge globally. This is because waste is not only challenging to sort at the human level, but it is also time consuming and often hazardous. One promising area of research and innovation that could be used to address this problem is machine learning and artificial intelligence. The purpose of this project is to build a machine learning model using object detection and classification techniques to automate and optimize waste segregation.

Dataset taken from: https://archive.ics.uci.edu/dataset/908/realwaste'

Model Built:
Created a Convolutional Neural Network using PyTorch.
Implementing Support Vector Machine using Scikit-learn (sklearn)
Used TorchVision for datasets, models, and image transformations specific to PyTorch.

Conclusion:
The implemented system achieved an accuracy of 82.14% using CNN with learning rate=0.0001 and 86.97% using SVM in classifying waste into the defined categories, demonstrating its potential for real-world deployment in smart bins or industrial waste management settings. The lower accuracy for CNN is observed as it was not trained to its full capability due to trouble finding optimal hyperparameters.
