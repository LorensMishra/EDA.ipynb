---

# 📱 Google Play Store Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Google Play Store applications dataset** to uncover insights related to **app categories, ratings, reviews, installs, pricing, and popularity trends**.
The analysis helps understand **user behavior**, **market trends**, and **factors influencing app success** on the Play Store.

The project uses **Python, Pandas, NumPy, Matplotlib, Seaborn**, and includes a **Streamlit web app** for interactive visualization.

---

## 🎯 Objectives

* Analyze distribution of apps across different categories
* Study rating patterns and user reviews
* Compare free vs paid applications
* Identify top installed applications
* Understand relationships between price, ratings, and installs
* Build an interactive dashboard using Streamlit

---

## 📊 Dataset Information

* **Dataset Name:** Google Play Store Apps
* **File:** `googleplaystore.csv`
* **Source:** Public GitHub Dataset
* **Records:** ~10,000 apps
* **Features:**

  * App
  * Category
  * Rating
  * Reviews
  * Size
  * Installs
  * Type (Free / Paid)
  * Price
  * Content Rating
  * Genres
  * Last Updated
  * Android Version

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Streamlit
* **Tools:**

  * Jupyter Notebook / VS Code
  * GitHub

---

## 📂 Project Structure

```
PlayStore-EDA/
│
├── googleplaystore.csv        # Dataset
├── eda_playstore.ipynb           # EDA Python script
├── requirements.txt           # Required libraries
└── README.md                  # Project documentation
```

---

## 🔍 Data Cleaning Steps

* Removed duplicate app entries
* Handled missing and null values
* Converted:

  * Reviews → Integer
  * Installs → Integer
  * Size → Numeric (MB)
  * Price → Float
* Standardized categorical values

---

## 📈 Exploratory Data Analysis Performed

* Apps count per category
* Rating distribution analysis
* Free vs Paid app comparison
* Top 10 most installed apps
* Price vs Rating analysis
* Correlation heatmap between numeric features

---

## 🌐 Streamlit Web App

An interactive dashboard was developed using **Streamlit** to visualize:

* App category distribution
* Rating trends
* Dataset preview

### ▶ Run the App Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## 🧠 Key Insights

* Majority of apps on Play Store are **Free**
* **Family, Game, and Tools** categories dominate the store
* Higher installs generally correlate with higher reviews
* Paid apps do not necessarily have better ratings
* App size has minimal impact on ratings

---

## 🚀 Future Enhancements

* Sentiment analysis on user reviews
* Time-based analysis on app updates
* Machine learning model to predict app ratings
* More interactive visualizations

---

## 📌 How to Use

1. Clone the repository

```bash
git clone https://github.com/LorensMishra/PlayStore-EDA.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run EDA script

```bash
python eda_playstore.ipynb
```

---

## 📄 Resume Description

> *Performed Exploratory Data Analysis on Google Play Store dataset using Python, Pandas, Seaborn, and Streamlit to extract insights on app categories, ratings, installs, and pricing trends.*

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.
Feel free to fork the repository and submit a pull request.

---

## 📬 Contact

**Author:** Lorens Mishra MCA
**Field:** Computer Science & Engineering

* **GitHub:** [https://github.com/LorensMishra](https://github.com/LorensMishra)
* **LinkedIn:** [https://www.linkedin.com/in/lorens-mishra](https://www.linkedin.com/in/lorens-mishra)

---

⭐ *If you like this project, don’t forget to star the repository!*

---
