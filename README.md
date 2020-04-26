# Dog-Breed-Classifier
Udacity Data Science Capstone Project

# Libraries 
The Major Libraries used are:
1. Pandas : for reading and processing data frames
2. Numpy  : for covnerting list to array , mathmatical conversion and calulations
3. Matplotlib : for visualization of results to plot graphs
4. sklearn.model_selection : for making a linear regression model to predict future forcast
5. Keras : to train our CNN Model
6. PIL : python imaging library to display image
7.OpenCV :face detections for human

# File Descriptions 
dog_app.ipynb - Jupyter notebook file containing the whole code of the project
images - folder which contain all the images for the algorithum to use
saved_models - pre-trained model weights files
haarcascades - XML files for detections by OpenCV

#Process
1. Import Datasets
2. Detect Humans
3. Detect Dogs
4. Create a CNN to Classify Dog Breeds (from Scratch)
5. Use a CNN to Classify Dog Breeds
6. Create a CNN to Classify Dog Breeds (using Transfer Learning)
7. Write your Algorithm
8. Test Your Algorithm

# Conclusions
Using transfer learning is by far best technique to quickly build a model as compared to traditional methods, the model by far is more accurate as to be made from scratch plus its utilizes less computing power and quickly provides with the results.

Model Accuracy : Test accuracy: 79.5455%

For more better results ,the model can be trained with larger number of epochs , adding more layers to the CNN network and using much larger dataset to train model.

Article Link:
https://medium.com/@sammakhussain26_36791/computer-can-detect-dog-breeds-too-cfeb7aa3d3db

GitHub: https://github.com/Sammak215/Dog-Breed-Classifier
