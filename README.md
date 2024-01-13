# MARKET BASKET INSIGHT PROJECT

**Project Documentation**

*Last Updated: 6/11/23*

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Getting Started](#getting-started)
4. [Project Structure](#project-structure)
5. [Data Preprocessing](#data-preprocessing)
6. [Association Analysis](#association-analysis)
7. [Discovered Association Rules](#discovered-association-rules)
8. [Business Implications](#business-implications)
9. [Conclusion](#conclusion)
10. [License](#license)

---

## 1. Project Overview

This repository contains the code and documentation for an association analysis project using the Apriori algorithm on a dataset sourced from Kaggle. The project's primary objectives were to explore patterns and relationships among items purchased by customers and analyze the potential business implications of these findings.

## 2. Dataset Description

The dataset used in this project is obtained from Kaggle and is provided in Excel format. It represents transaction data where each row corresponds to a customer's basket of items. The dataset was subjected to data preprocessing steps to ensure its suitability for association analysis.

Dataset Link: https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis

## 3. Getting Started

To explore and reproduce the results of this project, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed.
3. Open the Jupyter Notebook file (`AI_CODE.ipynb`) to review the code and findings.

## 4. Project Structure

The repository is organized as follows:

- `data/`: Contains the dataset used for analysis.
- `notebooks/`: Includes the Jupyter Notebook for data analysis.
- `README.md`: The document you are currently reading, providing a comprehensive overview of the project.
- `LICENSE`: This project is released under the [MIT License](LICENSE).

## 5. Data Preprocessing

Data preprocessing is a critical step in ensuring the quality of the data for association analysis. It involves the following tasks:

- Handling missing values.
- Encoding transactions into a binary format.
- Removing duplicate transactions.
- Filtering out low-support items.

## 6. Association Analysis

The Apriori algorithm was employed to identify frequent itemsets and generate association rules. The rules were generated based on the "lift" metric to capture the strength of associations between items.

## 7. Discovered Association Rules

A selection of association rules, each with associated metrics such as support, confidence, and lift, is provided in the Jupyter Notebook. These rules offer insights into item associations, which can be leveraged for business strategies and decisions.

## 8. Business Implications

The discovered association rules have significant implications for business strategies:

- They can guide product placement and promotions.
- Inform marketing strategies.
- Facilitate bundling of products for improved sales.
- Optimize inventory management.
- Enhance customer satisfaction.

## 9. Conclusion

In conclusion, this association analysis project equips businesses with actionable insights derived from customer transaction data. These insights can be harnessed to improve marketing strategies, customer experience, and operational efficiency. The generated association rules represent a valuable tool for optimizing business operations.

## 10. License

This project is licensed under the [MIT License](LICENSE).

For further information or inquiries, please contact ELANGO T.
