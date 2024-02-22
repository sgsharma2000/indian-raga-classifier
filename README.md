# indian-raga-classifier
IRC - neural network to classify certain Indian Ragas

We have a set of 20 Indian ragas: (Find out more about indian ragas at this link: _______)
We want to classify them based on a set of recordings that are passed in:

- Convert all of them to .wav
- get 30 second samples of each recording, balance it so that there are equal amount of samples for each recording (by creating pickle)
- gather all of the features based on those 30 second samples (also by creating pickle)
- create train and test split
- train and test on basic dense network using different features. (Each file is mapped to a certain feature)




