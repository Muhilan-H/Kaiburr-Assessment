# Kaiburr-Assessment
# **Consumer Complaint Categorization**  

## **Project Overview**  
This project aims to **classify consumer complaints** into different product categories using **Text Classification** techniques. We compare **Logistic Regression** and **BiLSTM** models to determine which performs better.  

## **Dataset**  
- The dataset used is the **Consumer Complaint Database** from [data.gov](https://catalog.data.gov/dataset/consumer-complaint-database).  
- It consists of consumer complaints related to different financial products.  

## **Project Workflow**  
1. **Exploratory Data Analysis (EDA) & Feature Engineering**  
   - Load the dataset.  
   - Select relevant columns (`Product` and `Consumer complaint narrative`).  
   - Remove missing values.  
   - Map product categories to labels for classification.  

2. **Text Preprocessing**  
   - Remove **stopwords and special characters**.  
   - Convert text to **lowercase**.  
   - Apply **lemmatization** to reduce words to their root form.  
   - Use **TF-IDF vectorization** for feature extraction.  

3. **Balancing the Dataset**  
   - Due to class imbalance, **SMOTE (Synthetic Minority Over-sampling Technique)** is applied to balance the dataset.  

4. **Model Selection & Training**  
   - **Baseline Model:** Logistic Regression  
   - **Deep Learning Model:** BiLSTM  

5. **Model Evaluation**  
   - Compare **accuracy, recall, and F1-score** of both models.  
   - Identify areas of improvement.

## **Conclusion**  
This project demonstrates **complaint categorization** using both **Logistic Regression and BiLSTM models**. BiLSTM outperforms Logistic Regression due to its ability to capture **long-term dependencies** and **contextual relationships** in text.

## **Installation & Setup**  
### **Requirements**  
Install the required libraries using:  
```bash  
pip install pandas numpy matplotlib seaborn nltk scikit-learn torch

## RESULTS
![Alt Text](![Screenshot 2025-02-28 195356](https://github.com/user-attachments/assets/b82cc714-ebc6-4178-b656-37402ad1d5bc)
)


