# 📝 Netflix Movies and TV Shows Recommendation System

This project is a personalized recommendation system designed for Netflix's movie and TV show catalog. By leveraging clustering algorithms and unsupervised learning techniques, the system groups similar titles and suggests content based on a user's preferred movie or TV show. It includes a web application built with Flask, HTML, CSS, and JavaScript for an interactive user experience.

---

## 🚀 Key Features

1. **Clustering-Based Recommendation System**:
   - Utilizes algorithms like BIRCH, K-Means, DBSCAN, and more for clustering.
   - Personalized recommendations based on content similarity.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizes trends in Netflix's dataset, including genre distribution, maturity ratings, and country-specific insights.

3. **Web Application**:
   - Built with Flask, offering features like movie search, auto-suggestions, and EDA visualizations.

4. **Interactive Frontend**:
   - A responsive interface built using HTML, CSS, and JavaScript.

---

## 🛠️ Tech Stack

- **Programming Language**: [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)

- **Frameworks & Libraries**: [![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)](#) [![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](#) [![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](#) [![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](#)

- **Visualization**: [![Matplotlib](https://img.shields.io/badge/Matplotlib-008080?style=for-the-badge&logo=python&logoColor=white)](#)

- **Frontend**: [![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

---

## 🏗️ Project Structure

- `Code_File.ipynb` → Jupyter Notebook containing the analysis and clustering implementations.
- `app.py` → Flask application for the recommendation system.
- `data.pickle` → Processed data for the recommendation engine.
- `model.joblib` → Trained BIRCH model for clustering.
- `movies.csv` → Processed dataset used in the recommendation system.
- `netflix_titles.csv` → Original dataset of Netflix's catalog.
- `requirements.txt` → File containing all the required Python dependencies.
- `static/` → Directory for static assets:
  - `Assets/` → Images and fonts used in the frontend.
  - `css/` → Stylesheets for the web interface.
  - `js/` → JavaScript files for frontend functionality.
- `templates/` → Directory for HTML templates:
  - `index.html` → Homepage for the recommendation system.
  - `result.html` → Displays the recommended movies or error messages.
  - `EDA.html` → Showcases the exploratory data analysis results.
  - `full_screen.html` → Displays full-screen images for EDA visualizations.