# Amazon Sentiment Analysis: Review Polarity Classifier

## 📌 Project Overview

This project focuses on building a **Natural Language Processing (NLP)** pipeline to classify Amazon customer reviews. Using a dataset of millions of reviews, the goal is to develop a model that can accurately distinguish between **Positive** and **Negative** sentiment based purely on the text content.

## 🛠️ Technical Stack

* **Language:** Python 3.12
* **Environment:** Google Colab / Jupyter Notebooks
* **Libraries:** * `Pandas` & `NumPy`: Data manipulation and cleaning
* `Scikit-Learn`: Machine learning modeling (Random Forest, Logistic Regression)
* `Matplotlib` & `Seaborn`: Data visualization
* `Zipfile` & `Tarfile`: Handling compressed archives



## 📂 Dataset

The project utilizes the **Amazon Review Polarity Dataset**.

* **Labels:** 1 (Negative), 2 (Positive)
* **Features:** Review Title, Review Content
* **Scale:** High-volume text data used to train robust classification models.

Dataset & Data Access
Due to GitHub's file size limitations, the full Amazon Review Polarity Dataset (which contains millions of reviews) is not included in this repository.

1. The Full Dataset
If you wish to train the model on the complete dataset, you can download it from the original source:

Source: Amazon Reviews for Sentiment Analysis (Kaggle)

File Name: amazon_review_polarity_csv.tgz

2. The Sample Dataset
For quick testing and to see the code in action, I have provided a smaller file named amazon_reviews_sample.csv within this repository. This sample contains 10,000 random entries and is used by default in the provided notebook.

## 🚀 Workflow

1. **Data Extraction:** Programmatically unzipping and extracting `.tgz` files within the Colab environment.
2. **Exploratory Data Analysis (EDA):** * Checking for class balance between positive and negative reviews.
* Visualizing review lengths and common word distributions.


3. **Preprocessing:** * Cleaning text (removing special characters).
* Handling `UnicodeDecodeErrors` by using specific encodings like `latin-1`.


4. **Modeling:** * Vectorizing text data using techniques like Bag-of-Words or TF-IDF.
* Training and evaluating **Logistic Regression** and **Random Forest** classifiers.


5. **Evaluation:** Measuring performance using Accuracy, Precision, Recall, and F1-Score.

## 📊 Key Results

* Successfully handled binary classification of sentiment.
* Implemented a fix for bracket-logic errors in Python to allow for seamless data sampling.

## 📝 How to Use

1. Clone the repository.
2. Ensure your Amazon dataset is uploaded to your Google Drive.
3. Run the notebook cells to extract data and train the model.
