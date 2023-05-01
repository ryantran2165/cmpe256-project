# CMPE 256 Project

## Team Name
RXD (Received Data)

## Team Members
- Xinyu Li
- Derek Lilienthal
- Ryan Tran

## Notebook Explainations

### EDA

Some general exploratory code and graphs can be found in this notebook. Examples include investigating the distributions of continuous features, how many categorical features have unique values, and summary statistics. Additionally, there is code for cleaning and eliminating features that have a single value, duplicate features, or all missing values. The most popular artists, songs, and average play counts are presented, along with some additional exploration of using various queries. 

### Ensemble_SVD_NeuCF

The code used to generate the Matrix Factorization and Neural Collaborative Filtering Ensemble findings is included in this notebook. It includes feature pre-processing code as well as code for executing the Neural Architecture Search (NAS) and analyzing techniques for determining the best model using RMSE. 

### filter_train_triplets

This notebook includes some extra scripts for filtering the dataset so that each song has been listened to by at least 200 people and each user has listened to at least 20 songs. 

### genre

The code for producing predictions for users based on the genres they listen to is contained in this notebook. 

### joining_song_genres

The code for parsing and loading the music genres datafile is included in this notebook.

### loading_data

This notebook contains all the code for creating the song and artist metadata datasets (except genres)

### split_data

This notebook contains the code for creating training and testing

###

## Recreating Results

To recreate the results of the Matrix Factorization and Neural Collaborative Filtering Ensemble, run the notebook https://github.com/ryantran2165/cmpe256-project/blob/main/Ensemble_SVD_NeuCF.ipynb
