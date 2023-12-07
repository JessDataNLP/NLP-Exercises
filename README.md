# NLP-Exercises

1. ## Movie Recommendation System using NLP and Cosine Similarity Algorithm

🎥 Overview: Build a movie recommendation system that suggests movies to users based on their search query, leveraging NLP techniques and the Cosine Similarity algorithm.

    📊 Data Collection:
        Source dataset containing movie titles, plot summaries, etc.

    🔧 Data Preprocessing:
        Clean and prepare data by handling missing values, converting text to lowercase, removing stop words, and applying stemming.

    📝 Feature Extraction:
        Utilize CountVectorizer and TfidfTransformer from scikit-learn for text data feature extraction.

    🧮 Similarity Calculation:
        Employ the cosine similarity algorithm to measure the similarity between movie plot vectors.

    🎬 Recommendation:
        Generate movie recommendations based on similarity scores and user queries.

🛠 Tools & Libraries: Python, pandas, numpy, scikit-learn, nltk.

🎯 Outcome: A user-friendly movie recommendation system that intelligently suggests movies based on user preferences.

2. ## Hate Speech Detection in Tweets using embeddings and Logistic regression

🔍 Overview: Classify tweets into 'normal' and 'hate speech' categories using embeddings and logistic regression.

    📈 Data Preparation:
        Aggregate and process data from CSV files containing normal and hate speech tweets.

    🔧 Text Preprocessing:
        Clean tweets by removing special characters, tokenizing text, removing stopwords, and applying lemmatization.

    📊 Feature Extraction:
        Implement GloVe vectors for transforming text data into numerical format.

    🤖 Model Training:
        Split data into training and testing sets.
        Train a Logistic Regression model, optimizing parameters with GridSearch.

    📏 Evaluation:
        Assess model performance using accuracy, precision, recall, F1-score, and confusion matrix.

🛠 Tools & Libraries: Python, pandas, scikit-learn, nltk, GloVe.

🎯 Outcome: A robust system capable of accurately identifying hate speech in tweets.
