# NLP_Movie-Sentimental-Analysis-using-DeepLearning

Movie Sentimental Analysis based on Movie Reviews. The dataset choosen here is the IMDB dataset which is prebuilt in keras for faster execution. The dataset contains movie data along with genres. The dataset is of 10,000 movies reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed, and each review is encoded as a list of word indexes (integers). 
The pakages used here are numpy, keras, sklearn, nltk, netron

The Reviews of the dataset is trained and tested. And then the words are converted into vectors for processing. Then I have built a DeepLearning Model with dense and dropout layers. The dataset is passed to the model and the accuracy obtainted is 89%. Next, the user input is preprocesssed using nltk the text is tokenized. The stopwords are removed, converted the tokens to integers using the IMDb dataset's word index. And the input is taken from user, processed and predicts the sentiment of the review as Positive Review or Negative Review.
