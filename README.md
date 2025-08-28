# Spam-Email-Classifier

A machine learning-based system to classify emails as spam or ham, built in Google Colab using scikit-learn.
Overview

Purpose: Detects spam emails and extracts non-spam (ham) emails in a structured format for enterprise use cases.
Tech Stack: Python, scikit-learn, Pandas, NumPy, Matplotlib, Seaborn.
Dataset: Spam Email Classification Dataset from Kaggle (~5,000 emails).

Setup

Clone the repository:
git clone https://github.com/yourusername/Spam-Email-Classifier.git
cd Spam-Email-Classifier


Install dependencies:
pip install -r requirements.txt


Download the Spam Email Classification Dataset from Kaggle (https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-combined) and place it as data/spam.csv.


Usage

Open notebooks/spam_email_classifier.ipynb in Google Colab or locally with Jupyter.
Upload spam.csv via the Colab file upload prompt when running the first cell.
Run all cells sequentially to train the model, evaluate, visualize, and save ham emails to ham_emails.csv.
Download ham_emails.csv for further analysis.

Results

Achieved ~95-98% accuracy on the test set (varies by run).
Visualizations include class distribution and a confusion matrix.
ham_emails.csv contains predicted ham emails with structured columns (email_text, predicted_label).

Files

notebooks/spam_email_classifier.ipynb: Main project notebook.
data/spam.csv: Input dataset.
data/ham_emails.csv: Output file with predicted ham emails in CSV format.
requirements.txt: Dependency list.

Future Improvements

Add email header parsing for better preprocessing.
Integrate with a database for scalable storage.
Support PDF email attachments using PyPDF2.

Contact

GitHub: yourusername

Email: [your.email@example.com]
