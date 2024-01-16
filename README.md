# 🥗 LivHealthy:  Diet Recommendation System

Welcome to the Diet Recommendation System - your personalized guide to a healthier lifestyle! 🌿 This web application employs a content-based approach, combining Scikit-Learn, FastAPI, and Streamlit to offer tailor-made diet recommendations.

## 📑 Table of Contents
1. [General Info](#general-info)
2. [Development](#development)
3. [Technologies](#technologies)
4. [Setup](#setup)

## 📜 General Info

### Motivation
In a world where health consciousness is on the rise, the Diet Recommendation System addresses the need for a balanced lifestyle. It leverages machine learning to provide personalized diet recommendations based on individual parameters such as height, weight, and age. The goal is to help users achieve and maintain a healthy weight, reduce the risk of chronic diseases, and improve overall well-being.

### Food Recommendation Engine
This system utilizes a content-based approach to recommend foods, considering nutritional content and individual preferences. It aids in promoting healthy eating habits, accommodating dietary restrictions, and suggesting diverse and nutritious options.

### Content-Based Recommendation Engine
The content-based recommendation engine analyzes the characteristics of food items, providing users with recommendations based on their preferences. This approach is user-centric, transparent, and eliminates the "cold start" problem often faced by collaborative filtering systems.

### Why Content-Based Approach?
- No reliance on user data for initial recommendations.
- Highly relevant and transparent suggestions.
- Mitigates the "cold start" problem.
- Easier system creation with fewer dependencies.

### Challenges
- Potential lack of novelty and diversity.
- Scalability challenges.
- Possible inconsistencies in attributes.

## 💻 Development

### Model Development
The recommendation engine employs the Nearest Neighbors algorithm for its unsupervised learning capabilities. By using the brute-force algorithm with cosine similarity, the system efficiently handles small datasets.

### Dataset
The project utilizes the Food.com Kaggle dataset, comprising over 500,000 recipes and 1,400,000 reviews. Check the [Kaggle link](https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions) for more details.

### Backend Development
FastAPI powers the backend, enabling the creation of fast and efficient web APIs. The API processes user requests and utilizes the recommendation model to generate personalized food recommendations.

### Frontend Development
Streamlit, an open-source app framework, forms the frontend. The web app consists of three pages: a welcome page, an automatic diet recommendation page, and a custom food recommendation page.

### Deployment using Docker
Docker ensures a consistent environment for deployment, preventing unexpected issues and simplifying scaling. Docker-compose orchestrates multiple containers for seamless deployment.

## 🚀 Technologies

- Python: 3.10.8
- FastAPI: 0.88.0
- Uvicorn: 0.20.0
- Scikit-Learn: 1.1.3
- Pandas: 1.5.1
- Streamlit: 1.16.0
- Numpy: 1.21.5
- BeautifulSoup4: 4.11.1

## 🐳 Setup

### Run Locally
1. Clone the repository: `git clone https://github.com/IshitaSingh2003/LivHealthy`
2. Run Docker Compose: `docker-compose up -d --build`
3. Open http://localhost:8501 and enjoy! 😃

### Hosted Version
Explore the hosted version on [Streamlit Cloud](https://diet-recommendation-system.streamlit.app/).


Elevate your well-being with LivHealthy! 🌱🏋️‍♂️
