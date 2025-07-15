# Youth-Fashion-Recommendation-System

In today’s fast-evolving digital fashion landscape, young consumers increasingly expect personalized and visually-driven experiences when exploring new clothing and accessories. To meet this demand, we present a Youth Fashion Recommendation System that leverages deep learning and computer vision to deliver real-time, image-based product suggestions. The system is designed to recommend fashion items—including shoes, accessories, and clothing for both men and women—based on visual similarity to an uploaded image.

Implemented as a user-friendly Streamlit web application, the system offers an intuitive interface where users can upload an image of a fashion product. Upon upload, a pre-trained ResNet (specifically, ResNet50) model is used to extract deep visual features from the image. These features are passed through a GlobalMaxPool2D layer to generate high-dimensional embeddings, which are then normalized and compared against a curated dataset of fashion items. This dataset, customized from publicly available sources, has its own precomputed feature embeddings. The system uses the Euclidean distance metric in conjunction with the Nearest Neighbors algorithm to identify and display the top five visually similar fashion items almost instantly.

Furthermore, the system eliminates the need to manually browse through countless products across various websites and apps. Instead, users can simply upload an image of interest and receive visually similar recommendations, each linked directly to the source website where the product can be found or purchased. This integration streamlines the shopping experience, saving time and improving relevance.

Although the similarity matching technique is implicit, it effectively enables content-based recommendations based on image features. This project demonstrates how deep learning and computer vision can be applied to youth-oriented fashion platforms, delivering intelligent, image-based personalization that reflects the user’s sense of style.

📌[app.py](https://drive.google.com/file/d/1V_86C1ezAGK-U6biMWPObJRGahY1TQUC/view?usp=drivesdk)

📌[Report](https://drive.google.com/file/d/1VMUJI-FXZFxXyQS6D9ftmS6FqVpoyvUx/view?usp=drivesdk)

## Collaborators

- [Suchismita Ghosh](https://github.com/suchi974)
- [Swastika Biswas](https://github.com/swastika-12-git)
- [Ankita Dubey](https://github.com/teammate3)
