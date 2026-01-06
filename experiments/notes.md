- Created project structure folders.
- Next: choose a dataset and run first exploration notebook.
## Day 3
- Loaded SMS Spam dataset.
- Dataset has labels (spam / ham) and raw text.
- Initial exploration done.

## Day 4
- Analyzed text length as a simple numerical feature.
- Computed message length for each SMS.
- Compared spam vs ham messages using basic statistics (count, mean, min, max).
- Observed that spam messages tend to have different length characteristics.
- Learned that even very simple features (like text length) can carry useful information in NLP.

## Day 5
- Implemented basic text preprocessing (lowercasing, removing non-letter characters).
- Created a cleaned version of the original text suitable for machine learning models.
- Learned why raw text cannot be directly used by ML algorithms.
- Applied Bag of Words (CountVectorizer) to convert text into numerical vectors.
- Applied TF-IDF to understand how word importance is weighted across documents.
- Understood the difference between simple word counts and TF-IDF representations.
## Day 6
- Built the first end-to-end NLP classification pipeline.
- Split the dataset into training and test sets to simulate real-world evaluation.
- Converted text data into numerical features using TF-IDF.
- Trained a Multinomial Naive Bayes classifier on the training data.
- Evaluated the model using accuracy on unseen test data.
- Tested the model on a custom SMS example to observe real predictions.
- Learned the importance of avoiding data leakage by fitting vectorizers only on training data.
- Understood that Naive Bayes uses probabilistic assumptions rather than semantic understanding.


