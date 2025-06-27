# 🛍️ AI-Based Clothing Recommender (Myntra Style Matching)

This project is a **content-based image recommendation system** that uses **computer vision and vector similarity** to recommend clothing similar to an uploaded image. Built using **OpenCV**, **NumPy**, and **cosine similarity**, the system identifies visual features of the input image and redirects the user to **Myntra** for similar fashion items.

---

## ✅ Features

- 🖼️ Upload an image of clothing (e.g., t-shirt, dress, shoes)
- 🔍 Automatically finds visually similar clothing items
- 🤖 Uses feature vectors and cosine similarity
- 🔗 Redirects user to the **Myntra** website for product viewing
- 💡 Real-time recommendation system using local dataset or pre-embedded vectors

---

## 🔧 Tech Stack

- **Python 3.x**
- **OpenCV** for image loading and processing
- **NumPy** for vector math and cosine similarity
- **tqdm** for progress bars
- **Webbrowser / URL Redirect** for opening Myntra

---

## 🧠 How It Works

1. **Preprocessing:** Load and preprocess dataset of clothing images.
2. **Feature Extraction:** Convert images into vector representations using OpenCV.
3. **Similarity Matching:** Use cosine similarity to compare uploaded image with dataset.
4. **Redirect:** Open the most similar product (or top-N) on Myntra.com in a browser.

---


