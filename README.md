# Predicting-Prices-of-Taiwanese-Commercial-Real-Estate
Dataset
  Retrieved Real Estate Transaction data in Taipei and New Taipei city. 
  Utilized Heremap and Google APIs to add corresponding longitude, latitude, and nearby features.
Data preprocessing
  Numerical Dataset: One-Hot Encoding, Standardization
  Image Dataset: Typecast each RGB image to a tensor  (3*256*256)
Algorithm and Training
  Combined  numerical dataset and image dataset with Resnet50 + CNN and DNN model.
  Best Result:+- $13,000/sqm ($39,000/ping) (+-10%)
