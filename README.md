
# Movie Review Generator

It is a straightforward deep learning project. It produces a rating for the chosen film or television show.

# Detailed Overview

In this project, we'll build an application that rates movies based on user input provided via movie reviews.

We must produce two datasets: input.csv for testing and reviews.csv for training. These datasets are present in the git repository. The reviews.csv dataset, which contains 40K reviews, is used to train the model. These datasets were gathered from tweets on Twitter using selenium-python. The input.csv file is used to test the model and contains reviews of the Snowdrop web series.

Pre-processing the data is necessary, and it is carried out during the coding phase. We'll create an LSTM model that's capable of NLP operations. A unique LSTM model was created and saved as model.h5.

We must now put this model to the test. The input.csv file contains ratings for the web series Snowdrop, which has an 8.2 imdb rating; according to our model, the rating should be somewhat closer to this.  And our models function accurately. 


## Deployment

To deploy this project follow the steps:

1. Clone this repository
2. Change the path of the dataset
3. Execute nlp_use_lstm_training.ipynb to create .h5
4. Now, execute nlp_model_testing_movie_review.ipynb

## Author

- [Sudhan Jee](https://github.com/sudhanRacharla)

