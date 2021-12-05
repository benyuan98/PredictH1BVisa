# PredictH1BVisa
 This is a course project for Cornell ORIE5741. We are using the previous h1b LCA dataset to predict the H1B visa conditions after the new policy.  



### Presentation Link

Please read the following content (also in the description of the video) which explain some points in the presentation before watching the video. 

[Presentation](https://www.youtube.com/watch?v=kcjxAQDWTu8)

**There might be some confusing point that we forget to explain in the video.**

- The metrics for autoGluon shown in the slide is accuracy. And the training data to pick the model is not down-sampled. We are using AutoGluon as a preliminary method to pick a proper method that can learn the mapping between the features and the labels for us in the following experiments. The models it picked perform best by accuracy on the whole data but not for the balanced accuracy. We decided to use balanced accuracy and down-sampled data after we picked the lightGBM. Thus the test score in the leaderboard of AutoGluon may not match the accuracy in the later experiments. 

**Since we have limited time on the presentation, we add our future work here and in the description of our Youtube video.**

#### Future work

- Try more models on it to deal with the imbalanced labels

- Find correlations between the features to make the model more accurate and reasonable. This is really hard since all the features are in different format and we have done multiple transformation to the original feature. 

- Dig into the interpretation of the models on this dataset.

  



