# 🧹 Data Cleaning in Pandas

This repository contains my Python notebook for cleaning and preparing a customer contact dataset using **Pandas**. The project focuses on common data-cleaning tasks such as removing duplicates, dropping unnecessary columns, standardizing text fields, splitting address data, handling missing values, and filtering out unusable records.

---

## 📌 Introduction

This project demonstrates a practical data-cleaning workflow in Python using **Pandas**.

The notebook works with a customer call list dataset and applies step-by-step cleaning techniques to turn raw contact data into a more structured and usable format for further analysis or business use.

The project highlights practical skills in:

- Python data cleaning
- Pandas data wrangling
- string manipulation
- handling missing values
- filtering records
- restructuring columns

---

## 💡 Motivation

Raw customer data often contains duplicate rows, inconsistent formatting, missing values, and unnecessary columns. Before the data can be used for reporting, contact management, or analysis, it needs to be cleaned and standardized.

This project shows how Pandas can be used to solve these issues in a simple and efficient workflow.

---

## 📂 Dataset Description

The project uses a customer contact dataset loaded from:

- `Customer Call List.xlsx`

The notebook works with fields such as:

- `Last_Name`
- `Phone_Number`
- `Address`
- `Do_Not_Contact`

During the cleaning process, the address field is further split into:

- `Street_Address`
- `State`
- `Zip_Code`

This makes the dataset more structured and easier to use.

---

## 🧹 Data Cleaning Workflow

The notebook applies the following main cleaning steps:

### 1. Remove duplicate rows
Duplicate records are removed using:

```python
df = df.drop_duplicates()
