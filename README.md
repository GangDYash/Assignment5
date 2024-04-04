# Data 1202: Data Analytics Tools - Lab 5

## This repository contains Python code from Lab 5 of the Data Analytics Tools course. The code demonstrates different techniques to encode categorical features into numeric quantities using the pandas library.

## Getting Started
To run the Python code provided in this repository, please make sure you have the following prerequisites installed on your system.

### Prerequisites
- Python 
- Pandas library

### Installing
You can install the required Python libraries using pip:
```bash
pip install pandas
```

# Running the Tests

The provided Python file [Lab5_week8.ipynb](https://github.com/GangDYash/Assignment5/blob/44f2afe6d30d9c3bf03eebcd7d0b850df7afc018/Lab5_week8.ipynb) demonstrates three different techniques for encoding categorical features: replacing values, label encoding, and one-hot encoding. Below is a breakdown of each technique used in the code.

## Breakdown of Tests

### Replacing Values:

This method replaces categories with desired numbers using the `replace()` function in pandas. It demonstrates how to assign numerical values to categories based on business use cases.

### Label Encoding:

This technique converts categorical values into numerical labels using the `cat.codes` method in pandas. It assigns numerical labels to each category.

### One-Hot Encoding:

One-hot encoding creates binary columns for each category and assigns a 1 or 0 to each column. It is implemented using the `get_dummies()` function in pandas.

# Deployment

This code can be used as a reference for data preprocessing tasks involving categorical data encoding in Python projects and data analysis pipelines.

# Author

This repository is maintained by **Yash Gangaram Dahibhate**.

# License

Open License

# Acknowledgement

Special thanks to **Omar Al-Trad** for providing the lab materials and guidance.
