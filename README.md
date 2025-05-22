# MoviesRatingPrediction
# 🎬 Movie Rating Prediction using IMDb Dataset

This project focuses on building a machine learning model to predict IMDb movie ratings based on textual reviews. It uses natural language processing (NLP) techniques to extract meaningful patterns from review texts and make predictions about sentiment and rating levels.

## 📂 Project Structure

- `movie-predict.ipynb` – Jupyter Notebook containing all preprocessing, model training, and evaluation steps.
- `IMDbDataset.csv` – Dataset containing movie reviews and their associated sentiment labels.

## 🔍 Features

- Data cleaning and preprocessing
- Text vectorization using TF-IDF
- Model training with classification algorithms (e.g., Logistic Regression, Naive Bayes, etc.)
- Evaluation using accuracy and confusion matrix
- Visualization of model performance

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## 📊 Dataset

The dataset contains the following fields:

- `review` – Text review submitted by users.
- `sentiment` – Binary label indicating whether the review is positive or negative.

Dataset source: IMDb large movie review dataset.

## 🚀 How to Run

1. Clone this repository.
2. Make sure you have Python 3.x installed.
3. Install the required libraries:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn jupyter
