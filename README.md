# Image Caption Generator 

This project is done using TensorFlow and Keras API.

* The dataset can be downloaded from [here](https://www.kaggle.com/adityajn105/flickr8k).
* The architecture for this project follows an Encoder-Decoder approach.
* The Encoder model is a Convolutional Neural Network because the input is an image.
* It's output is then fed into the Decoder model which is a LSTM.
* The image preprocessing is reshaping the image. Transfer Learning is utilized to generate better predictions.
* The text preprocessing consists of cleaning the data by removing digits, converting to lowercase and then generating the mappings for each word to unqiue number and its reverse.
* Vocabulary is then created out of the words by including only the words that fall below the certain threshold. This discarded all the most frequently words like a, an, the.
* Then the word embedding matrix between the vocabulary is calculated by using the glove 6B 50D vector.


#### Generated Predictions
![](https://user-images.githubusercontent.com/74998474/122776459-bf514a80-d2c8-11eb-8402-9caa7509a8e8.png)
