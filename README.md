# EMOUSIC- Music recommendation based to user's facial expression detection.

## Introduction

Music plays a very important role in everyday life of a human being. Music has always been known to change people’s moods. Capturing and recognizing a person’s emotion and displaying appropriate songs matching the person’s mood can gradually calm their mind and end up giving a pleasing effect.

## Installations Required

* streamlit
* numpy
* pandas
* opencv-python
* tensorflow
* keras
* collection

## Dataset

The data set used for the music recommendation system is the Last.fm dataset is a publicly available dataset that contains listening histories of Last.fm users. The dataset includes information such as the artist’s name and song title. This dataset can be used for music recommendation based on the listening history of a user.

## Methodology

* The web app is designed with the help of streamlit open sourcing that provide a strong connection for an machine learning algorithm to access all the web based features.
* The Haar Cascades are a type of pre-trained classifier in OpenCV that can be used for face detection. Haar Cascades are trained on thousands of positive and negative images of faces to detect the facial features and distinguish them from the background.
* OpenCV provides several pre-trained Haar Cascades for face detection, such as 'haarcascade_frontalface_default.xml' and 'haarcascade_frontalface_alt.xml'.
* This is used to classify the emotions detected on the web cam and give appropriate results to the model to work on.
* Then the music recommender will choose the random 30 songs out of 2513 classified songs to give the music according to the user’s mood. Hence with the use of classifier and a trained model we can get recommended songs as per the mood detected.



