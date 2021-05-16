# PRML-CSL2050 Course Project
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/harsh-ux/PRML-project/blob/main/Pill_Recommendation.ipynb)

## Built With
* [Scikit-learn](https://scikit-learn.org/stable/) - ML library used
* [Tensorflow Keras](https://www.tensorflow.org/guide/keras/sequential_model) - ML library used
* [Pytorch](https://pytorch.org/) - ML library used
* [ReactJS](https://reactjs.org/) - Javascript framework used
* [Pandas](https://pandas.pydata.org/) - Python Data Manipulation library used
* [Seaborn](https://seaborn.pydata.org/) - Data Visualization library used

## Code Structure 
1. Pill_Recommendation.ipynb - This is the main file with all the preprocessing, EDA and Machine learning and Deep Learning Models.
   a. Installing libraries and Dependencies
   b. Importing dataset
   c. Exploratory Data analysis
   d. Data preprocessing - Basic data information, cleaning up the data
   e. Dividing into test and train and transforming using Count Vectorise
   f. Applying Machine Learning models
   g. Applying Deep learning Models
   h. Applying Harvard Sentiment Dictionary Analysis
   i. Classifier Combination - Voting
2. Emotional_Analysis.ipynb - This contains the emotional analysis done on the reviews using NRC Lexicon Library.
   a. It contains the same preprocessing as the above file.
   b. Post that NRC Lexicon library is explored.
   c. Reviews are passed to the library functions to get the emotion scores.
   
## How to run
1. Run the Pill_Recommendation.ipynb file first.
   a. The SVM code keeps crashing hence those cells should be avoided while running.
   b. LSTM takes about 1.5 hrs to complete running. 
   c. The predictions from all the models are collected and stored in a .csv file.
   d. The final prediction scores calculated are also stored in a .csv file at the end.
2. Run the Emotional_Analysis.ipynb file after that.
   a. It is a completely separate entity from the Pill_Recommendation.ipynb file. The results from both the files are used to predict data based on the reviews and rating as shown on the deployed website.
   b. It takes 6 hours to run. 

## Collaborators
|Name|Year|Branch|
|--|--|--|
|[Harsh Agarwal](https://github.com/harsh-ux)|Sophomore|EE|
|[Aditi Goyal](https://github.com/gaditi123)|Sophomore|EE|
|[Darshit Jain](https://github.com/DarshitJain04)|Sophomore|EE|
