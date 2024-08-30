## MUSIC GENRE CLASSIFICATION WITH PCA AND LOGISTIC REGRESSION

## Objective 

The growing demand for categorizing and recommending music by genre, particularly in the age of digital streaming, has become a focal point of interest. In response to this trend, we conducted an in-depth analysis of various musical features extracted from a wide array of tracks. The primary objective of this project is to predict the genres of these unlabeled tracks.
While the dataset we're working with is substantial, it's important to note that a significant portion of the records lacks specific genre labels. This presents both a challenge and an opportunity, as we aim to accurately classify these tracks despite the incomplete data.

## Description of the project
Music tracks are inherently complex, consisting of numerous features that can capture different aspects of the audio. However, some of these features might be highly correlated, potentially leading to redundancy in the data. To address this, we will apply Principal Component Analysis (PCA) to reduce the dimensionality of the dataset. PCA will help us identify the most important features, streamlining the data for more efficient processing.
Following the dimensionality reduction, we will utilize a supervised machine learning approach, specifically logistic regression, to analyze the data further. This combination of PCA and logistic regression will allow us to build a model capable of predicting the genres of the unlabeled tracks, enhancing our understanding of their underlying patterns
