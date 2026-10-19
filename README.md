# SMS Spam Detection Using Machine Learning

## Project Overview

This project uses machine learning to classify SMS messages as **Spam** or **Ham (legitimate)**. It demonstrates how text data can be converted into numerical features and used to train classification models.

## Objectives

- Load and explore a real-world SMS dataset.
- Check and handle missing values and duplicate records.
- Convert text messages into TF-IDF features.
- Train and compare two machine learning models.
- Evaluate performance using accuracy, precision, recall, F1-score and confusion matrices.
- Test the trained model on sample messages.

## Dataset

**Source:** [UCI SMS Spam Collection](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)

The dataset contains SMS messages labelled as `spam` or `ham`.
## Dataset
* [Link to Dataset](PASTE_YOUR_LINK_HERE) - Brief description of the dataset used.

## Setup Instructions
1. Clone this repository: 
   ```bash
   git clone https://github.com
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn jupyter
   ```
3. Open the notebook:
   ```bash
   jupyter notebook spam_sms.ipynb
   ```

## Results
* **Model 1 Accuracy/F1-Score:** [Insert Score]
* **Model 2 Accuracy/F1-Score:** [Insert Score]
* Brief comparison or performance summary here.

## Conclusion
* Summarize what you learned or which model performed best for SMS spam detection.


## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Machine Learning Models

1. **Multinomial Naive Bayes** — a probabilistic classifier commonly used for text classification.
2. **Logistic Regression** — a classification algorithm that estimates the probability of a message belonging to a category.

TF-IDF is used to represent message text numerically.

## Methodology

1. Load the dataset.
2. Explore the data and inspect missing values and duplicates.
3. Clean the dataset.
4. Split the data into training and testing sets.
5. Transform the message text using TF-IDF.
6. Train both models.
7. Compare evaluation metrics and confusion matrices.
8. Test predictions on example SMS messages.

## Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

The notebook reports the actual results obtained from the test set. The final conclusion should be based on those results, especially the model's ability to detect spam without incorrectly flagging legitimate messages.

## How to Run

1. Download or clone this repository.
2. Open `sms_spam_detection.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells in order.
4. Ensure an internet connection is available to download the dataset.

## Repository Contents

- `sms_spam_detection.ipynb` — complete analysis, model training and evaluation.
- `README.md` — project documentation.

## Conclusion

This project demonstrates how machine learning can help identify unwanted text messages. Comparing Naive Bayes and Logistic Regression shows how different classification algorithms perform on the same text dataset. The preferred model should be selected using the measured evaluation results, with particular attention to missed spam and false spam predictions.

## Disclaimer

This project is for educational purposes. Model predictions are not guaranteed to be correct.
