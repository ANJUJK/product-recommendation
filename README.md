# product-recommendation
Recommending products based on visual similarity

Given an image of any object , we recommend the most similar objects. 

## Required Libraries

numpy,keras,pandas,matplotlib,pillow,sklearn

##  Dataset
self made dataset of various outfits.

## Approach

A pre-trained CNN model from keras is used for feature extraction.
Similarities between the different products using the previously extracted image features are computed.
