# 📊 Data Analytics Practical

## Categorization of Data Based on Organization, Format, and Structure

------------------------------------------------------------------------

## 📌 Project Overview

This project focuses on understanding how data is categorized based on:

-   **Structure**
-   **Format**
-   **Organization**

The goal is to determine the **analytical suitability** of different
types of data in Data Analytics.

------------------------------------------------------------------------

## 🎯 Objective

To classify various types of data and evaluate whether they are directly
suitable for analysis or require preprocessing techniques.

------------------------------------------------------------------------

## 🏗 Data Classification

### 1️⃣ Based on Structure

-   **Structured Data**\
    Organized in rows and columns (e.g., CSV, Excel, SQL databases).\
    ✅ Highly suitable for analysis.

-   **Semi-Structured Data**\
    Contains hierarchy or tags (e.g., JSON, XML, API responses).\
    ⚠️ Requires preprocessing before analysis.

-   **Unstructured Data**\
    No predefined format (e.g., text, images, videos, emails).\
    ❌ Requires advanced techniques like NLP or Machine Learning.

------------------------------------------------------------------------

### 2️⃣ Based on Format

  Format   Example             Suitability
  -------- ------------------- ------------------------
  CSV      sales.csv           Highly Suitable
  Excel    data.xlsx           Suitable
  SQL      Database Tables     Highly Suitable
  JSON     api_response.json   Needs Preprocessing
  TXT      comments.txt        Requires Cleaning
  Image    photo.jpg           Requires ML Techniques

------------------------------------------------------------------------

### 3️⃣ Based on Organization

-   **Tabular** → Rows & Columns → ✅ Easy to Analyze\
-   **Hierarchical** → Parent-Child Structure → ⚠️ Needs Transformation\
-   **Network** → Graph-Based → ⚠️ Requires Graph Tools\
-   **Free Text** → Paragraph Format → ❌ Needs NLP

------------------------------------------------------------------------

## 🧪 Implementation

This project includes a simple Python example to demonstrate handling
structured and semi-structured data.

``` python
import pandas as pd

# Structured Data
structured_data = pd.read_csv("sales.csv")
print(structured_data.head())

# Semi-Structured Data
semi_structured_data = pd.read_json("sample.json")
print(semi_structured_data.head())
```

------------------------------------------------------------------------

## 📁 Project Structure

    Data-Analytics-Practical/
    │
    ├── README.md
    ├── practical_report.md
    ├── analysis.py
    └── sample_data/
        ├── sales.csv
        └── sample.json

------------------------------------------------------------------------

## 📊 Conclusion

Understanding data categorization is essential in Data Analytics.\
It helps in selecting the right tools, preprocessing steps, and
analytical techniques.

-   Structured data → Direct analysis\
-   Semi-structured data → Preprocessing required\
-   Unstructured data → Advanced ML/NLP required

------------------------------------------------------------------------

## 👨‍💻 Author

Feni Soni\
Data Analytics Practical Submission
