# 📚 Book Recommendation System

A **machine learning-powered** personalized book recommender application built with **Python, Flask, and Scikit-learn**, using the [Book-Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/).
The system suggests books based on user preferences and reading patterns, leveraging advanced **collaborative filtering** techniques.

---

## 📖 Overview

This application uses collaborative filtering and machine learning algorithms to recommend books.
It preprocesses the dataset, filters low-interaction users to address the **cold-start problem**, and encodes categorical data for compatibility.

**Core Approach:**

* **Collaborative Filtering** for personalized suggestions.
* **Cosine Similarity** for book-to-book similarity measurement.
* **Singular Value Decomposition (SVD)** for dimensionality reduction and improved accuracy.
* **K-Nearest Neighbors (KNN)** for neighbor-based recommendations.
* **Label Encoding** to convert categorical data into numeric format.

---

## ✨ Features

* **Top Books Page** – Displays the most popular books.
* **Book Search & Recommendation** – Suggests similar books for a given title.
* **Interactive Web Interface** – User-friendly Flask web app.
* **Cold-Start Handling** – Removes low-interaction users for better accuracy.
* **Hybrid ML Approach** – Combines cosine similarity, SVD, and KNN.

---

## 🛠️ Tech Stack

**Programming Language:** Python
**Frameworks & Libraries:** Flask, Pandas, NumPy, Scikit-learn, SciPy
**Machine Learning Techniques:** Collaborative Filtering, Cosine Similarity, SVD, KNN
**Data Preprocessing:** Label Encoding, Data Cleaning
**Dataset:** [Book-Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/)
**Deployment:** Heroku

---

## 📂 Project Structure

```
book-recommendation45-master/
│
├── app.py                     # Main Flask app
├── requirements.txt           # Dependencies
├── setup.py                   # Setup config
├── setup.sh                   # Deployment script
├── Procfile                   # Heroku deployment config
├── data/                      # Dataset files
│   ├── BX-Books.csv
│   ├── BX-Book-Ratings.csv
│   └── BX-Users.csv
├── src/                       # ML pipeline and helpers
│   └── __init__.py
└── Books Recommender data analysis.ipynb   # Jupyter notebook (EDA + ML model)
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/piyushsharma0211/AI_Book-recommendation.git
cd AI_Book-recommendation-master
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Locally

```bash
python app.py
```

Visit: `http://127.0.0.1:5000`

---

## 📊 Dataset

* **BX-Books.csv** – Book details.
* **BX-Book-Ratings.csv** – User ratings (0–10 scale).
* **BX-Users.csv** – User demographics.

---

## 🚀 Deployment

This project can be deployed to **Heroku**:

```bash
git push heroku master
```

Ensure:

* `Procfile`, `requirements.txt`, and `setup.sh` are properly configured.
* Dataset is available in `/data` or cloud storage.

---

## 🔮 Future Enhancements

* Incorporate **content-based filtering** for hybrid recommendations.
* User authentication for personalized history.
* Larger and more recent book datasets.
* API for mobile integration.

---

## 📜 License

This project is licensed under the **MIT License**.

````

