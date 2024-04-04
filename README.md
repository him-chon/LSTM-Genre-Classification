# LSTM-Genre-Classification
An implementation of Long Short-Term Memory (LSTM) recurrent neural network for music genre classification based on lyrics.
This project shows how an Natural Language Processing (NLP) based approach to music classification can be implemented.
Dataset used is [Multi-Lingual Lyrics for Genre Classification](https://www.kaggle.com/datasets/mateibejan/multilingual-lyrics-for-genre-classification) from kaggle. Please download the dataset from the link, copy "train.csv" to the same working directory as the python notebook file, and rename it as "data.csv". Since the dataset file is larger than GitHub file size limit, alternatively, you can use GitHub LFS to track the dataset file. Refer to [Git Large File Storage Documentation](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-git-large-file-storage) to get started.

## Purpose of this project
Common approaches to music genre classification usually rely on audio features. Contexual information in song lyrics often get overlooked. We have taken an Natural Language Processing (NLP) path to musical genre classifcation. We have employed both LSTM and Bi-Directional LSTM neural network models, which specialize in dealing with extended dependencies of natural language, for musical genre classification with lyrical data as input.
We assessed the model on a 10-class and simplified 2-class classification tasks, testing model performance on 5 different lyrics transformations to find an optimal algorithm-transformation combination on both a simple and more complex classification task.

## About this project
- This project is presented in jupyter notebook with extensive use of text cells describing each steps so it's super easy to read.
- The LSTM models are written in PyTorch
- Pandas is used for data preprocessing
- The LSTM models implemented predicts musical genre of a song based on its lyrics
- Input to the model is preprocessed lyrics of a song
- Output of the model is musical genre of a song
- Both LSTM and Bi-Directional LSTM models were implemented and assessed on 10-classes and 2-classes music genre classifcation

