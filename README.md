# Sarcasm-Detection-on-NLP-and-Deep-Learning

What is Sarcasm?

Sarcasm is the caustic use of words, often humorously, to mock someone or something. Sarcasm may employ ambivalence although it is not necessarily ironic. Most noticeable in spoken word, sarcasm is mainly distinguished by the inflection with which it is spoken or, with an undercurrent of irony, by the extreme disproportion of the comment to the situation, and is largely context-dependent.

Sarcasm Detection

Import necessary Python libraries such as pandas, numpy, etc.

Load the dataset of Reddit sarcasm data.

Preprocess the dataset by removing null comments, converting the timestamp into a DateTime object, removing duplicate values, converting uppercase letters to lowercase, removing punctuation, and removing numbers.

Perform exploratory data analysis (EDA) to analyze and investigate the dataset, summarizing its main characteristics using data visualization methods. This includes the distribution of classes on sarcasm status, the length of sarcastic comments, the length of normal comments, a word cloud, the score of subreddits (sarcastic score vs neutral score), comparing the length of comments, and subreddits vs the total number of comments.

Define a CNN to detect sarcasm, including hyperparameters. Train the CNN, then test and predict the sarcasm in the given data.

Define a bidirectional LSTM to detect sarcasm, including hyperparameters. Train and test this algorithm, then predict sarcasm.

Define a vanilla LSTM to detect sarcasm, adding hyperparameters. Train and test this algorithm, then predict sarcasm.

Analyze the best algorithm by evaluating accuracy, recall, precision, and F1 score.
