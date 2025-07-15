# Youth-Fashion-Recommendation-System

This project presents a youth-focused fashion recommendation system that delivers personalized, image-based product suggestions using deep learning and computer vision. Built as a user-friendly Streamlit web app, users can upload an image of a fashion item (e.g., shoes, accessories, clothing), and the system recommends five visually similar products with direct shopping links.

A pre-trained ResNet50 model extracts deep visual features, which are processed into normalized embeddings. These are compared using Euclidean distance against a curated dataset of fashion items with precomputed embeddings. The Nearest Neighbors algorithm identifies the closest matches in real time.

By eliminating the need for manual browsing, the system enhances the shopping experience with quick, visually-driven recommendations tailored to the user's style.
