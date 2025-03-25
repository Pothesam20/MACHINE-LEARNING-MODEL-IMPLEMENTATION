# MACHINE-LEARNING-MODEL-IMPLEMENTATION
*COMPANY*:   CODE IT SOLUTIONS


*NAME*:      POTHE SAMANTHA



*INTERN ID*:  CT12UFO


*DOMAIN*:     PYTHON


*DURATION*:   8 WEEKS



*MENTOR*:    NEELA SANTOSH



### **Spam Detection Using Machine Learning in Python**

Automated spam detection is a machine learning task that classifies messages as spam or ham (not spam). This is useful for email filtering and text moderation.

#### **Steps to Implement Spam Detection**
1. **Data Collection** – We use a dataset containing labeled messages (`spam.csv`).
2. **Preprocessing** – Convert text into numerical format using `CountVectorizer`.
3. **Model Training** – Train a **Naïve Bayes** classifier (`MultinomialNB`).
4. **Evaluation** – Measure accuracy and generate a classification report.

#### **Key Python Libraries Used**
- `pandas`: Load and process dataset.
- `sklearn.feature_extraction.text.CountVectorizer`: Convert text to numerical format.
- `sklearn.naive_bayes.MultinomialNB`: Train a text classification model.
- `sklearn.metrics`: Evaluate the model performance.

#### **Expected Output**
The model predicts whether a message is spam with **~98% accuracy**, generating a classification report that includes **precision, recall, and F1-score**.
