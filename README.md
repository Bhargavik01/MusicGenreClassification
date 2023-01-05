# MusicGenreClassification

<img src="m.jpeg" width="1100" height="600">



The Music Genre Classification is a model for categorising songs or audio music into the appropriate genre based on a variety of features.Pop, Hip-Hop, Rock, Classical, Disco, Reggae, Jazz, Blues, Country, and Metal are the most common musical genres. As people’s lifestyles become more reliant on music, technology, and the internet become more affordable to end users, there is a greater need to develop an efficient and more accurate model for this classification.

Goal of this project is to create a model that can classify and organise audio music into genres. This is implemented by using Machine Learning techniques which have shown to be very effective at identifying patterns and trends in the vast amount of data. The classification is based on the acoustic characteristics of the audio music and the spectrogram of the audio.Hence model will be designed and developed to produce a better accuracy for Music Genre Classification.

<b> Data was downloaded from :</b> <a href="https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification"> Link </a>

Data set has:
Original genres: A set of 10 genres, each with 100 audio files that last for 30 seconds each. original pictures a graphic representation of each audio file. Two CSV files that include the attributes of the audio files. One file contains a mean and variance calculated over various features that can be extracted from an audio file for each song (30 seconds long). The songs were previously divided into 3 second audio files, but the other file has the same structure. It’s always better to have more data.


<b>Machine Learning Algorithms implemented</b>
<ul>
  <li> Random Forest with hyper parameter tuning </li>
  <li> K-Nearest Neighbor with hyper parameter tuning </li>
  <li> Support Vector Machine. with hyper parameter tuning </li>
  <li> K-Means Clustering with hyper parameter tuning </li>
  <li>Convolutional Neural Network</li>
</ul>

<b> Conclusion:</b>
For 3 sec feature data set, Support Vector machine with hyper parameters, K Nearest Neighbour with hyper parameters and CNN performed well.
For 30 sec feature data set, CNN outperforms other algorithms 

<b> Learnings</b>
As the size of the training data increases, the performance of the model improves. It is always beneficial to fine-tune the hyperparameters in order to achieve optimal performance.
  
