[Armenian News Classification Dataset](https://www.kaggle.com/datasets/erantonyan/armenian-news-classification-dataset)

## 📚 Overview

This dataset comprises a collection of Armenian news articles categorized into multiple topics. It serves as a valuable resource for training and evaluating machine learning models in the field of Natural Language Processing (NLP), particularly for tasks such as topic classification, sentiment analysis, and language-specific NLP research.

## 🧠 Dataset Details

* **Languages**: Armenian
* **Number of Articles**: \[30.000]
* **Categories**: \[| Բանակ / Army | Military and defense-related news
                    | Քաղաքական / Political | Local political news
                    | Տնտեսություն / Economy | Financial and economic updates
                    | Մշակույթ / Culture | Arts, literature, and heritage
                    | Սպորտ / Sports | Sports events and commentary
                    |Միջազգային / International | International news]
* **Format**: \[CSV]

## 📥 Accessing the Dataset

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/erantonyan/armenian-news-classification-dataset)


## 🧪 Data Structure

The dataset is organized as follows:

```
/armenian-news-classification-dataset
│
├── armenian_news_dataset.csv

```

## 🔧 Usage

To load and preprocess the dataset, you can use the following Python code:

```python
import pandas as pd

# Load the training data
train_data = pd.read_csv('armenian_news_dataset.csv')

# Display the first few rows
print(train_data.head())
```



This will load the training data into a pandas DataFrame and display the first few rows.


## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, please fork this repository and submit a pull request.


