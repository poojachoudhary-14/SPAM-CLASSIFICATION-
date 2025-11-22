SMS Spam Classifier 📱🚫 This project implements a machine learning model to classify SMS messages as either Spam or Not Spam (Ham). It utilizes the Multinomial Naive Bayes algorithm, which is highly effective for text classification tasks, achieving a high level of accuracy in distinguishing between legitimate and unsolicited messages.

🚀 Key Features and Methodology

Data Preprocessing: The project starts by loading the SMSSpamCollection.csv dataset, cleaning it by dropping duplicate entries, and standardizing the category labels from ham/spam to Not Spam/Spam.

Train-Test Split: The dataset is split into training and testing subsets (33% for testing) to ensure the model's performance is evaluated on unseen data.

Feature Extraction (Vectorization): The raw text messages are converted into numerical feature vectors using CountVectorizer with English stop words removed. This creates a Bag-of-Words representation, which is suitable for the Naive Bayes model.

Model Implementation: A Multinomial Naive Bayes classifier from scikit-learn is trained on the vectorized training data.

✅ Performance and Results

The model's performance was evaluated using accuracy score and a detailed classification report on the test set

Accuracy--------->98.42% (0.98417) 5

SMS Spam Classifier 📱🚫 This project implements a machine learning model to classify SMS messages as either Spam or Not Spam (Ham). It utilizes the Multinomial Naive Bayes algorithm, which is highly effective for text classification tasks, achieving a high level of accuracy in distinguishing between legitimate and unsolicited messages.

🚀 Key Features and Methodology

Data Preprocessing: The project starts by loading the SMSSpamCollection.csv dataset, cleaning it by dropping duplicate entries, and standardizing the category labels from ham/spam to Not Spam/Spam.

Train-Test Split: The dataset is split into training and testing subsets (33% for testing) to ensure the model's performance is evaluated on unseen data.

Feature Extraction (Vectorization): The raw text messages are converted into numerical feature vectors using CountVectorizer with English stop words removed. This creates a Bag-of-Words representation, which is suitable for the Naive Bayes model.

Model Implementation: A Multinomial Naive Bayes classifier from scikit-learn is trained on the vectorized training data.

✅ Performance and Results The model's performance was evaluated using accuracy score and a detailed classification report on the test set.

Metric Value Overall Accuracy

98.42% (0.98417)

Detailed Classification Report The model demonstrates excellent performance, particularly in correctly identifying Ham (Not Spam) messages:

Category Precision Recall F1-Score Not Spam (Ham) 0.99 0.99 0.99 Spam 0.93 0.95 0.94

🛠️ Technologies and Libraries This project is built using Python and the following key libraries:

pandas: For data loading, manipulation, and cleaning.

scikit-learn (sklearn): For machine learning tasks, including model selection, feature extraction (CountVectorizer), and the classification algorithm (MultinomialNB).

matplotlib (plt): For data visualization (though not extensively shown in the provided script, it's typically included for analysis).

numpy: For handling numerical arrays (used internally by scikit-learn).

🏃 Getting Started Prerequisites You need a Python environment with the following packages installed:

Bash

pip install pandas scikit-learn matplotlib

Running the Code Dataset: Ensure the dataset (SMSSpamCollection.csv) is accessible. Note: The provided script assumes a local path: C:\Users\Ujjaini\Downloads\SMSSpamCollection.csv.

Execution: Run the Python script to load the data, train the Multinomial Naive Bayes model, and print the performance metrics.
