# News Intelligence NLP

NLP-based classification of news articles into four categories: World, Sports, Business, and Sci/Tech.

## Project Overview

This project uses Natural Language Processing and Machine Learning to automatically classify news articles into predefined categories.

## Dataset

- Dataset: AG News
- Training samples: 120,000
- Test samples: 7,600
- Categories: World, Sports, Business, Sci/Tech

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook
- Joblib

## NLP Workflow

1. Load the news dataset
2. Explore the data
3. Clean and preprocess text
4. Extract TF-IDF features
5. Train machine learning models
6. Evaluate model performance
7. Save the trained model
8. Predict categories for new articles

## Models Used

- Logistic Regression
- Linear Support Vector Machine (SVM)

## Model Performance

| Model | Validation Accuracy |
|---|---:|
| Logistic Regression | 92.00% |
| Linear SVM | 92.04% |

### Final Test Performance

The selected Linear SVM achieved:

- Accuracy: **91.84%**
- Precision: **91.83%**
- Recall: **91.84%**
- F1-Score: **91.83%**

## Project Structure

```text
News_Intelligence_NLP/
│
├── data/
├── models/
│   ├── news_classifier_svm.pkl
│   └── tfidf_vectorizer.pkl
│
├── notebooks/
│   └── 01_news_data_exploration.ipynb
│
├── outputs/
├── src/
├── README.md
└── requirements.txt
```

## How to Run

1. Install the required dependencies.
2. Open the Jupyter Notebook.
3. Run the notebook cells from top to bottom.
4. Use the prediction function to classify new news articles.

## Example Prediction

```python
predict_news("The company reported strong revenue growth and expanded its business operations.")
```

## Conclusion

This project demonstrates an end-to-end NLP classification workflow using text preprocessing, TF-IDF feature extraction, machine learning, model evaluation, model persistence, and prediction.
