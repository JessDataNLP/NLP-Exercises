# NLP-Exercises

1. ## Movie Recommendation System using NLP and Cosine Similarity Algorithm

The goal of this project is to build a movie recommendation system that suggests movies to users based on their search query. This system uses Natural Language Processing (NLP) techniques to analyze the plot summaries of movies and identify the most similar movies using the Cosine Similarity algorithm.

The following are the main steps involved in building this system:

    **Data Collection**: We start by collecting data from a dataset of movies that contains various details such as movie title, plot summary, etc.

    **Data Preprocessing**: We preprocess the collected data by removing unnecessary data, handling missing data, and cleaning the text data by converting text to lowercase, removing stop words, and stemming the words.

    **Feature Extraction**: We extract features from the preprocessed text data using the CountVectorizer and TfidfTransformer methods from the scikit-learn library.

    **Similarity Calculation**: We calculate the similarity between movies using the cosine similarity algorithm. Cosine similarity calculates the cosine of the angle between two vectors and is used to determine the similarity between them.

    **Recommendation**: We then use the calculated similarity scores to recommend movies to users based on their search query.

This project uses Python programming language and various libraries such as pandas, numpy, scikit-learn, and nltk to preprocess the data and extract features. The final output is a movie recommendation system that suggests movies to users based on their search query.
