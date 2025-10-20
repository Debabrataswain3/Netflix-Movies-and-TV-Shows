## 📊 **Netflix Data Analysis Project**

### 🎯 **Project Objective**

The main objective of this project is to clean and analyse the Netflix dataset to uncover meaningful insights such as duration patterns, season distributions, and data consistency.
Key goals include:

* Cleaning and transforming raw data for accurate analysis
* Handling missing or duplicate records
* Correcting data types (e.g., converting “42 min” → `42`, and “Season 2” → `2`)
* Performing exploratory data analysis (EDA) to understand trends in Netflix shows and movies

---

### 📁 **Dataset Used**

**Dataset Name:** Netflix Dataset
**Source Link:** [Netflix Dataset on Kaggle](https://github.com/Debabrataswain3/Netflix-Movies-and-TV-Shows/blob/main/Netflix.csv)

The dataset contains information such as title, type, director, cast, country, release year, rating, duration, and description.

---

### 🧹 **Data Cleaning and Transformation**

Performed in **Jupyter Notebook (Python)** using libraries like `pandas`, `numpy`, and `matplotlib`.

**Key cleaning steps:**

* Removed duplicate and null values
* Standardised data types
* Extracted numeric values from *duration* (e.g., `"42 min"` → `42`)
* Converted *season* values to integers (e.g., `"Season 2"` → `2`)
* Verified unique and consistent entries for key columns

---

### 🧠 **Technologies Used**

* **Python 3**
* **Jupyter Notebook**
* **Pandas**

---

### 📈 **Results**

* Clean dataset with all numeric duration and season values correctly formatted.

---

### 📂 **Repository Structure**

```
📁 Netflix-Data-Analysis/
│
├── 📘 Netflix_Data_Analysis.ipynb     # Jupyter notebook with code
├── 📄 Netfix Dataset.html             # HTML export of notebook
├── 📄 README.md                       # Project documentation
└── 📊 cleaned_netflix_dataset.csv     # Final cleaned dataset
```

---
