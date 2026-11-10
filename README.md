# SMS Spam Message Detection Using Machine Learning

## Project Overview
This project uses Machine Learning and Natural Language Processing (NLP) to classify SMS messages as Spam or Ham (Legitimate).

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Extraction (Bag of Words and TF-IDF)
5. Model Training
6. Hyperparameter Tuning
7. Threshold Optimization
8. Model Evaluation
9. Model Saving
10. Real SMS Testing

## Machine Learning Algorithms
- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Machine (SVM)

## Best Performing Model
Linear SVM with TF-IDF and Optimized Threshold.

## Final Model Performance

| Metric | Score |
|---|---:|
| Accuracy | 98.65% |
| Precision | 95.35% |
| Recall | 93.89% |
| F1 Score | 94.62% |

## Confusion Matrix
- True Negatives: 897
- False Positives: 6
- False Negatives: 8
- True Positives: 123

## Model Files
- spam_detection_model.pkl
- tfidf_vectorizer.pkl
- threshold.json

## How to Run
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook.
4. Run the cells to train and test the model.

## Conclusion
The optimized Linear SVM model achieved 98.65% accuracy and successfully classifies SMS messages into Spam and Ham categories.