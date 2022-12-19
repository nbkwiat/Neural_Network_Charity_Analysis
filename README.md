# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis is to predict whether or not a charity will recieve funding based on previous successes and failures. We are using a neural network to predict these outcomes.

## Results

  - The targets for our model are to determine whether a charity will be succesful or not
  - The number of features are 50 and are deterimine by APPLICATION_TYPE, AFFILIATION,CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and SPECIAL_CONSIDERATIONS.
  - the EIN and NAME column were dropped and were neither a target or feature.
  - for my model I ultimatly went with three hidden layers with 150 nodes. I did this because the general rule of thumb is 3x the amount of nodes to features. 
  - I was unable to achieve higher than 75% accuracy.
  - I tweaked the number of layers and nodes multiple times and the highest percentage I got to was 72.2% with the setup in the image below 
![image](https://user-images.githubusercontent.com/109539205/208474407-469440cc-5b8b-4385-8118-87b82f8a0d3e.png)

## Summary

The results could be achieved with a little more manuvering of nodes and layers. I also believe that when you are unable to achieve a higher rating than 75% that is a tell of not enough data. With some more research and some tweaking I believe it is possible to predict whether a charity will recieve funding or not. 
