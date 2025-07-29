# 👗 Youth-Fashion-Recommendation-System

In today’s fast-evolving digital fashion landscape, young consumers increasingly expect personalized and visually-driven experiences when exploring new clothing and accessories. This project presents a **Youth Fashion Recommendation System** that leverages deep learning and computer vision to deliver **real-time, image-based fashion product suggestions**.

---

## 🧠 Project Overview

Implemented as a user-friendly **Streamlit web application**, the system allows users to upload an image of a fashion product—like shoes, clothing, or accessories. A pre-trained **ResNet50** model extracts deep visual features, followed by a **GlobalMaxPool2D** layer to produce normalized, high-dimensional embeddings.

These embeddings are compared using the **Euclidean distance** and the **Nearest Neighbors** algorithm against a curated dataset of fashion items with precomputed embeddings. The top 5 visually similar items are then displayed—each linked to its original source website for easy navigation and purchase.

This solution streamlines fashion discovery, saving users time while offering personalized recommendations tailored to their style.

---

## 🧰 Technologies Used

- **Python**
- **Streamlit**
- **TensorFlow / Keras (ResNet50)**
- **scikit-learn**
- **Pillow**
- **NumPy**

---

## 🚀 How It Works

1. 📤 Upload an image of a fashion product
2. 🧠 Extract visual features using ResNet50
3. 🔍 Compare features with dataset using Euclidean distance
4. 🖼️ Display top 5 visually similar fashion items with purchase links

---

## 🔗 Key Files

- 📄 [app.py](https://drive.google.com/file/d/1V_86C1ezAGK-U6biMWPObJRGahY1TQUC/view?usp=drivesdk) – Streamlit Web App Code  
- 📘 [Report](https://drive.google.com/file/d/1VMUJI-FXZFxXyQS6D9ftmS6FqVpoyvUx/view?usp=drivesdk) – Detailed Project Report

---

## 🤝 Collaborators

- [Suchismita Ghosh](https://github.com/suchi974)  
- [Swastika Biswas](https://github.com/swastika-12-git)  
- [Ankita Dubey](https://github.com/teammate3)

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
