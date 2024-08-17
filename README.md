**Overview**

This project focuses on Sentiment Analysis, a technique used to understand and classify the emotions of a given text. The primary goal is to classify movie reviews from the IMDB dataset as either positive or negative using various machine learning and deep learning models. The models used in this project include:

1. Naïve Bayes (implemented from scratch and using MultinomialNB)
2. Support Vector Classifier (SVC)
3. Logistic Regression
4. BERT (Bidirectional Encoder Representations from Transformers)
   
**Experiment and Results**

The preprocessing steps involved:

 - Tokenization: Dividing the text into tokens.
 - N-Grams: Generating Unigrams, Bigrams, and Trigrams.
 - Stopwords Removal: Eliminating common words that carry little meaning.
 - Stemming and Lemmatization: Normalizing words to their base forms.
 - TF-IDF: Calculating the term frequency-inverse document frequency to identify important terms.

Data Splits
 - The dataset was split into training, development, and testing sets using an 80-20 ratio, ensuring proper model evaluation.

**Model Performance**

The performance of each model was evaluated using accuracy, precision, recall, and F1-score. The key findings include:

1. Naïve Bayes (from scratch): Accuracy of 0.71.
2. Multinomial Naïve Bayes: Accuracy of 0.78.
3. Logistic Regression: Default accuracy of 0.84, optimized to 0.83.
4. Support Vector Classifier: Default accuracy of 0.81, optimized to 0.84.
5. BERT: The uncased version outperformed all other models with an accuracy of 0.878.

**Conclusion**

The BERT model, particularly the uncased version, demonstrated the best performance on the IMDB dataset, confirming its capability to capture complex patterns in text data. Future work will focus on enhancing the model by optimizing hyperparameters further and exploring additional feature selection techniques.
