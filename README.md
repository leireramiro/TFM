# Boosting the recognition of emotions in songs with data augmentation

## Abstract

Emotional experience is an essential element in music creation, distribution and consumption. With the emergence of music streaming platforms as well as the massive data they provide, music emotion recognition (MER) has become a subject of high interest as it can facilitate music personalisation, context-aware music generation, music therapy and more. By adopting Russell’s valence-arousal (VA) continuous representation of emotion, this study delves into the data augmentation on the lyrics of songs. In particular, this study incorporates lyrics data to assess their contribution to MER performance and reduction of human subjectivity. Differnt type of regression models of Machine Learning (ML) are used to compere results for the task of predictin emotions from songs based on valence-arousal space in consideration as an alternative to the human annotated VA space. Finally, the "tcc\_ceds\_music" dataset is used to evaluate the performance of the models.

## Objectives

The elaboration of this work aims to find a regression model capable of predicting emotions of a set of songs. The beginning will be the search for a database, from which the characteristics used to train and test a ML model will be extracted, in this case these characteristics will be extracted from the song lyrics. These characteristics must be numerical, therefore a process of vectorization of text from the NLP field will be carried out. 

It is important to start from a good database, quite complete, with songs that present very specific nuances of that mood, but that there are also some that are a little more similar to those of their neighbors, in order to adjust the algorithm even more. For training, this can reduce uncertainty when identifying and predicting.

The modeling process can be somewhat more tedious. Like any study, it is essential to perform tests and adjustments of all parameters and hyper-parameters of which the model consists. Here, the models will be focused on different regressors, where special emphasis will be placed on the performance of these models when using different data augmentation techniques in the chosen database. Moreover, within the data augmentation techniques a hyper-parameter adjustment will also be performed with the aim of finding a combination of regression model and data augmentation technique, with adjusted hyper-parameters, which make the best performance when predicting emotions from the song lyrics.

