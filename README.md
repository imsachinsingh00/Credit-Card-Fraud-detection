# Credit Card Fraud Detection

This project focuses on identifying fraudulent credit card transactions using machine learning algorithms. The dataset contains transactions made by European cardholders in September 2013.

## 📁 Project Structure

- `Credit card Fraud Detection.ipynb`: Main notebook for data analysis, preprocessing, and model training.
- `README.md`: Project documentation.

## 📊 Dataset

The dataset used contains only numerical input variables which are the result of a PCA transformation due to confidentiality. It includes:
- 284,807 transactions
- 492 frauds (Class 1)
- 283,315 legitimate transactions (Class 0)

You can download it from: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## ⚙️ Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install with:
```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Clone the repo or unzip the files.
2. Download and place the dataset in the project directory.
3. Run `Credit card Fraud Detection.ipynb` to begin analysis and training.

## 📈 Algorithms Used

- Logistic Regression
- Decision Trees
- Random Forest
- XGBoost
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

## 🔍 Key Insight

Due to class imbalance, evaluation metrics like precision and recall are more important than overall accuracy.

## 📄 License

MIT License.
