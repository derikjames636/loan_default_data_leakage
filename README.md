# Loan Default Prediction and Data Leakage Analysis

## About

This project investigates loan default prediction using Lending Club loan data and demonstrates how **data leakage can affect machine learning model performance**.

The analysis compares model performance under three different feature conditions:

- **Clean features**
- **Temporal leakage**
- **Strong leakage**

The purpose is to show how using information that would not have been available at the intended prediction time can significantly increase the apparent performance of a model.

---

## Dataset

The project uses the Lending Club accepted loan dataset covering **2007–2018**.

The dataset is not included in this repository because of its large file size.

The dataset can be downloaded from the following Google Drive folder:

[Download Dataset](https://drive.google.com/drive/folders/12HVT_dgOfKlx5J-1VRRT-djeGeY8BlQ5?usp=drive_link)

After downloading the dataset, the required file is:

```text
accepted_2007_to_2018Q4.csv.gz
