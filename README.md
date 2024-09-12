# Phishing Email Detection using NLP
This project is part of an NLP course at the Industrial Engineering Faculty, Tel Aviv University. The goal of the project is to analyze phishing email datasets using advanced Natural Language Processing (NLP) techniques. The project is divided into two main parts: visualization of the datasets and modeling using pre-trained NLP models and compression techniques.

## Project Structure
### Part A: Data Visualization

This section focuses on visualizing various features and metrics within the phishing email datasets.
Some key visualizations include:
The number of URLs present in each email,
the number of recipients addressed within the email body,
and the distribution of spam vs. non-spam emails.
These visualizations provide insight into how phishing emails are structured and help in understanding the dataset’s underlying patterns.
### Part B: NLP Modeling

We used two pre-trained language models for classifying phishing emails: **BERTa and RoBERTa**, which are known for their high accuracy in text classification tasks.
After implementing the models, we explored three different compression methods to optimize the models for efficiency:
#### Quantization: Reducing the precision of weights and activations to speed up inference and reduce memory usage.
#### Pruning: Removing redundant weights to decrease the model size while maintaining its performance.
#### Knowledge Distillation: Training a smaller model to mimic the performance of a larger, pre-trained model.
These compression techniques were employed to ensure that the models maintain high accuracy while becoming more resource-efficient for real-world applications.
### Dataset
The dataset used in this project can be found on [Kaggle](https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset/data)

### Results
Visualizations provided clear insights into the structure of phishing emails and common characteristics that distinguish spam from non-spam.
BERTa and RoBERTa demonstrated high accuracy in phishing email classification.
Compression techniques helped reduce model sizes while maintaining competitive accuracy, making the models more efficient for deployment.
