# Spam Email Detection using Machine Learning

## Project Overview
This project uses Machine Learning to classify emails as **Spam** or **Ham (Legitimate)**. It uses TF-IDF for text feature extraction and the Multinomial Naive Bayes algorithm for classification.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF Vectorization
- Multinomial Naive Bayes

## Dataset
- Total emails: 5,171
- Ham emails: 3,672
- Spam emails: 1,499
- Target column: `label_num` (0 = Ham, 1 = Spam)

## Project Workflow
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Train-test splitting
5. Text feature extraction using TF-IDF
6. Model training using Multinomial Naive Bayes
7. Model evaluation
8. Testing with custom email examples

## Model Performance
- Accuracy: **88.79%**
- Spam Precision: **100%**
- Spam Recall: **61%**
- Spam F1-score: **76%**

## Confusion Matrix

| | Predicted Ham | Predicted Spam |
|---|---:|---:|
| Actual Ham | 735 | 0 |
| Actual Spam | 116 | 184 |

## How to Run

1. Clone this repository.
2. Install the required libraries:

   `pip install -r requirements.txt`

3. Open the Jupyter Notebook:

   `jupyter notebook`

4. Run `Detecting_Spam_Emails_.ipynb`.

## Project Files
- `Detecting_Spam_Emails_.ipynb` – Complete ML implementation
- `spam_ham_dataset.csv` – Dataset
- `requirements.txt` – Required libraries

## Future Improvements
- Improve spam recall.
- Compare Naive Bayes with Logistic Regression.
- Experiment with different TF-IDF settings.

## Author
Manish Kumar
