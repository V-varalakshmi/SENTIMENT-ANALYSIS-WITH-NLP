# SENTIMENT-ANALYSIS-WITH-NLP

*COMPANY*:CODETECH IT SOLUTIONS

*NAME*:RAVAVARAPU VENKATA VARALAKSHMI DEVI

*INTERN ID*:CT06DL1153

*DOMAIN*:MACHINE LEARNING

*DURATION*:6 WEEKS

*MENTOR*:NEELA SANTOSH

DESCRIPTION:

This Python script performs sentiment analysis on a dataset of movie reviews using natural language processing (NLP) and machine learning techniques. It begins by importing essential libraries such as `pandas` for data handling, `re` for regular expressions, `matplotlib` and `seaborn` for visualization, and modules from `sklearn` for building and evaluating the model. The script also uses the Natural Language Toolkit (`nltk`) to download and utilize English stopwords, which are commonly used words that do not contribute significant meaning to text classification. The dataset, containing textual movie reviews and their corresponding sentiments (positive or negative), is loaded using `pandas.read_csv()` and the columns are appropriately named.

To prepare the data for analysis, the script defines a `preprocess` function that cleans each review by converting text to lowercase, removing HTML tags and non-alphabetic characters, and filtering out stopwords. The cleaned reviews are stored in a new column called `cleaned_review`. Next, the sentiment labels are mapped to binary values: 'positive' is converted to 1 and 'negative' to 0. The cleaned data is then split into training and testing subsets using an 80-20 split. Since machine learning models require numerical input, the script uses the `TfidfVectorizer` to transform the text data into numerical feature vectors, capturing the importance of each word across the corpus.

A logistic regression classifier is trained on the TF-IDF-transformed training data. Once the model is trained, it makes predictions on the test set. The performance of the model is evaluated using several metrics: accuracy score, which indicates the percentage of correctly predicted reviews; a classification report that provides precision, recall, and F1-score for both sentiment classes; and a confusion matrix, which visually summarizes the model's correct and incorrect predictions. The confusion matrix is plotted as a heatmap using Seaborn, allowing for easy interpretation of the results.

Overall, the script provides a clear and structured pipeline for performing sentiment analysis—from data loading and cleaning, through model training, to performance evaluation and visualization. It offers a practical example of how machine learning and NLP can be applied to real-world text classification problems.

#OUTPUT

