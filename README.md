# Malicious URL Detection Using Machine Learning

## Overview
This project aims to develop a robust and efficient system for detecting malicious URLs using machine learning techniques. It identifies whether a given URL is benign or malicious based on its lexical features. The project was developed as part of **CSP571 - Data Preparation & Analysis** under the guidance of **Prof. Oleksandr Narykov**.

## Team Members
- Aryan Nandu (A20583853)
- Rudra Patel (A20594446)

## Problem Statement
As digitalization grows, malicious URLs have become a significant cybersecurity threat. Hackers exploit these links to deceive users, leading to data theft, financial loss, and other forms of cybercrime. Traditional detection methods, like blacklists, often fail due to their static nature. This project leverages machine learning techniques to analyze URLs and predict their nature effectively.

## Key Features
- **Dataset**: A Kaggle dataset of 651,191 URLs (428,103 benign and 223,088 malicious) was used.
- **Lexical Feature Extraction**: Eighteen features, such as URL length, hostname length, and the count of specific characters, were analyzed.
- **Machine Learning Models**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gaussian Naive Bayes
  - Extra Trees
- **Best Model**: The Extra Trees Classifier achieved 97% accuracy and was selected as the final model.

## Methodology
1. **Data Preprocessing**: Extract lexical features from URLs.
2. **Model Training**: Train five classifiers on the dataset.
3. **Model Evaluation**: Compare classifiers using metrics like accuracy, precision, recall, and F1-score.
4. **Prediction**: Use the best model to classify new URLs.

## Results
- The Extra Trees Classifier outperformed other models in terms of accuracy and computational efficiency.
- Confusion Matrix:
  - True Negatives: 84,244
  - True Positives: 42,301
  - False Negatives: 2,373
  - False Positives: 1,321
- Accuracy: **97.16%**

## Future Scope
- Incorporate additional lexical features for improved accuracy.
- Balance the dataset for better generalization.
- Develop a user-friendly application for real-time URL analysis and QR code scanning.

## Installation & Usage
1. Clone the repository:  
   ```bash
   git clone https://github.com/Aryan2210/DPA_Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd DPA_Project
   ```
3. Run the project notebook:
   ```bash
   jupyter notebook Project.ipynb
   ```

## Outputs
- Comparative performance of classifiers.
- Heatmaps and bar charts for feature correlations.
- A classification system that predicts whether a URL is malicious or benign.


## Contact
For any questions or feedback, feel free to contact:
- **Aryan Nandu**: [anandu@hwak.iit.edu]
- **Rudra Patel**: [rpatel199@hawk.iit.edu]
