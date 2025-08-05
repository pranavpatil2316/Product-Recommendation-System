This project is a Content-Based Recommendation System that suggests similar products based on their textual descriptions. It leverages TF-IDF vectorization and cosine similarity to understand and compare the content of product descriptions, enabling accurate and personalized suggestions.
# 🛍️ Product Recommendation System

This is a simple **Content-Based Product Recommendation System** using TF-IDF and cosine similarity. It recommends similar products based on their textual descriptions.

---

## 📌 Features

- Takes user input for a product name
- Supports **partial matching** (e.g., type "camera" to find related items)
- Recommends similar products based on TF-IDF + Cosine Similarity
- Lightweight and runs perfectly in **Google Colab**

---

## 🧠 How it works

- Product descriptions are vectorized using **TF-IDF**.
- **Cosine similarity** is calculated between the products.
- Based on your input, the most similar products are recommended.

---

## 🗂️ Files Included

- `recommendation_system.ipynb` – Jupyter Notebook (Colab-compatible)
- `large_product_data.csv` – Sample product dataset
- `README.md` – Project documentation

---

## ▶️ Getting Started

1. Open [`recommendation_system.ipynb`](recommendation_system.ipynb) in Google Colab
2. Upload the `large_product_data.csv` when prompted
3. Enter a product name (full or partial), and get recommendations!

---

## 📦 Dataset

A sample dataset of 15 tech-related products with their names and descriptions.

---

## 🧰 Requirements

- Python 3.x
- pandas
- scikit-learn

All dependencies are pre-installed on Google Colab.

---

## 📸 Demo

```bash
Enter a product name to get recommendations:
> camera

Top 5 recommendations:
➡ 4K Action Camera - Waterproof 4K action camera with image stabilization...
➡ Smartphone Gimbal Stabilizer - 3-axis gimbal stabilizer for smartphones...
...
