# Naive Bayes – SMS Spam Classification

## Project Overview
This project implements the **Naive Bayes classification algorithm** to classify SMS messages as **Spam** or **Ham (Not Spam)**. The model is trained on a real-world text dataset and demonstrates how probabilistic classifiers can be effectively used for text classification problems.

## Dataset
- **Name:** SMS Spam Collection Dataset
- **Source:** Kaggle
- **Total Records:** ~5,500 messages
- **Columns Used:**
  - `label` – Target variable (0 = Ham, 1 = Spam)
  - `message` – SMS text content

## Tools and Technologies
- **Programming Language:** Python
- **Platform:** Google Colab
- **Libraries Used:**
  - pandas
  - scikit-learn
  - matplotlib (optional for analysis)

## Methodology
1. Dataset uploaded and loaded into Google Colab.
2. Unnecessary columns removed and data cleaned.
3. Text labels converted into numeric form.
4. Data split into training and testing sets.
5. Text vectorization performed using **Bag of Words (CountVectorizer)**.
6. **Multinomial Naive Bayes** model trained on the training data.
7. Model evaluated using accuracy, classification report, and confusion matrix.
8. Model tested with custom SMS messages.

## Results
The Naive Bayes model achieved **high accuracy** in classifying spam and non-spam messages. The results show that Naive Bayes is highly effective for text-based classification tasks such as spam detection.

## Files in This Folder
- `spam.csv` – Original dataset
- `spam_predictions.csv` – Model predictions on test data
- `naive_bayes_spam.ipynb` – Implementation notebook
- `README.md` – Project documentation

## Conclusion
The Naive Bayes algorithm successfully classified SMS messages with strong performance. Due to its simplicity and efficiency, it is well-suited for real-time spam filtering and other text classification applications.

## Author
Afifa Taskeen
