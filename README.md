# Bedform-Inference-Using-CNNs based on Free Surface Images ([Interactive Code & visuals](https://github.com/sakshamg94/Bedform-Inference-Using-CNNs/blob/master/Conv2D_code.ipynb))
CNNs for Underwater bedform inference

- **Introduction:** In this notebook, I capture the details for my multi-class classifcation project based on a Convolutional Neural Network. This analysis is for a project listed on <a href="https://web.stanford.edu/~sakshamg/portfolio/bathymetry_inversion">my website</a>. I strongly recommend a quick reading of the introduction there to get an overview of what's to follow. If you are interested in more details, you can see <a href="https://web.stanford.edu/~sakshamg/assets/docs/JFM1_R1.pdf">my publication</a> which is under review. 


- **Happy to provide Data access:** The data for the following work was acquried by me in Stanford's Bob and Norma Street Environmental Fluid Mechanics Lab as part of a proof-of-concept study. **I am all for open science**, so please contact me if you would like to access the full data and we can work something out. It's not being publicly circulated *yet* becasue I haven't hashed out the format for circulation.


- **Background knowledge for CNN**: Going forward I will also be assuming that the reader is familiar with basic NN theory and the convolutional framework. If not, don't worry and <a href="https://developers.google.com/machine-learning/practica/image-classification/convolutional-neural-networks">refresh your understanding here </a>. There are exercises there which were helpful to me. 

## Contents of the notebook:
1. Introduction to muticlass classification framework and data
    1. Data organization
    2. Visualize the image data
3. Building a Small Convnet from Scratch
4. Compiling the model
5. Training the net
6. Saving the model for future usage
7. Plotting the model Loss and Accuracy
8. Test Set Predictions, Confusion Matrix, Errors in Predictions
    1. Predict on the test set
    2. Save test set accuracy
    3. Function for making confusion matrix
