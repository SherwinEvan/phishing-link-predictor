# Phishing Link Detector: Project Overview

### Developed a machine learning-based tool to detect phishing URLs with high accuracy (95%), aiming to improve online safety and prevent cyberattacks.


## Dataset and Features

- Dataset of **10,000+** labeled URLs, including phishing, malware, defacement and benign examples.
- **Engineered features** based on URL lexical properties (length, special characters, etc.), HTML structure, and domain-specific attributes (SSL certificate, WHOIS info).

---

## Exploratory Data Analysis (EDA)

- Analyzed the distribution of key attributes like URL length, top level domain, directory etc.
- Visualized correlations between features and the likelihood of phishing.

---

## Model Building

- Transformed categorical features into numeric formats and split the data into training and testing sets (80%-20%).
- Evaluated multiple machine learning models using precision, recall, and F1-score to handle the class imbalance effectively:
  - **Random Forest Classifier**  
    Accuracy = 88.8%  
  - **XGBoost Classifier**  
    Accuracy = 91.3%  
  - **LightGBM Classifier**  
    Accuracy = 95.9%

---

## Code and Resources Used

### Python Version: 3.9  
**Packages**:  
- pandas
- matplotlib
- wordcloud
- tld
- seaborn
- scikit-learn

---

**Requirements File**:  
```shell
pip install -r requirements.txt
