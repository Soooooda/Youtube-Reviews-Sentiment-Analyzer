## Structure
There are four jupyter notebooks here.
HAN.ipynb is using Hierarchical-attention-networks to train the corpus.
data_process and baselines.ipynb has basic handle on corpuses and run some regression and classification algorithms.
LSTM with torch embeddings.ipynb utilized pytorch embedding to train the corpus in LSTM.
LSTM with word vectors.ipynb utilized average word vectors to train the corpus in LSTM.

## Project Categories
1. Nature Language Processing
2. Computer Vision
## Problem Description
Predicting the popularity of online content has attracted much attention in the past few years. As we
all know, Youtube is one of the best popular video-sharing websites in the world. Lots of people become
Youtubers to share their life or for business purpose. They are keen to know, as soon as possible, whether
their videos will be popular or not. So given a video and its description, we want to predict the popularity
of it. Our project may shed some light on not only youtubers but also those who what to gain more trac
from videos and text. Therefore, we think it's an interersting and useful project.
## Dataset
Trending YouTube Video Statistics Dataset
This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is
included for the USA, Great Britain, Germany, Canada, France, Russia, Mexico, South Korea, Japan and
India respectively, with up to 200 listed trending videos per day.

Each region's data is in a separate le. Data includes the video title, channel title, publish time, tags,
views, likes and dislikes, description, and comment count.
## Algorithms and implementations
There're a number of approaches and algorithms to perform this prediction. Several popularity prediction
methods have been proposed in the last decade, from simple linear regression functions to complex frameworks
that cross-correlate information from dierent web sites. We are going to seperately extract feature vectors
from videos and languages. Then, videos can be trained using CNN and languages can be trained using
LSTM and combine them to train a regression model.
## Responsibilities and duties
Chenmei Li is responsible for video feature extraction and training using Computer Vision techonlogies.
Xia Gong is responsible for language feature extraction and training using NLP techonlogies. Then we will
combine them into a regression model together.