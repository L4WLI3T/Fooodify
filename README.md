# Fooodify
## Introduction
A problem that many non-native people face when they visit India is food recognition. It will be fun if they can know the name of a dish very accurately by just uploading it’s picture. The problem with some famous platforms that do the same job is that they find it difficult to recognize some of the traditional Indian foods like Bisi Bele Bath, Ven pongal, etc. So we propose a model that can classify 14 dishes including few of the traditional indian foods and some fast foods too. We have used Convolutional Neural Network (CNN) as a feature extractor to train an image category classifier which gives above average accuracy. CNN’s can learn rich feature representations which often perform much better than other handcrafted features such as histogram of oriented gradients (HOG), Local binary patterns (LBP), or speeded up robust features (SURF). And we have deployed this model using flask. So a user can just take a picture of the food and upload on the web app and get the name of the dish.

## Model 
![Capture](https://user-images.githubusercontent.com/48093400/123222157-45e67180-d4ed-11eb-9f08-d2088865ee69.JPG)

### Metrics for model evaluation
Precision = TP/(TP+FP)
Recall = TP/(TP+FN)
F1 = 2*(Precision*Recall)/(Precision+Recall)
![m1](https://user-images.githubusercontent.com/48093400/123222908-08361880-d4ee-11eb-83f9-315c267caf55.JPG)
![m2](https://user-images.githubusercontent.com/48093400/123222941-0f5d2680-d4ee-11eb-9b3a-992d30b7bc4b.JPG)
