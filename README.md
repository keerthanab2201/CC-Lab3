# Dockerized Spam Detection ML App

This project demonstrates a simple Machine Learning application deployed using Docker.
The application classifies input messages as Spam or Not Spam using a trained ML model.

## Technologies Used
- Python
- Flask
- Scikit-learn
- Docker

## Project Structure
- app.py – Flask application
- Dockerfile – Docker configuration
- templates/ – HTML frontend
- spam_classifier_model.pkl – Trained ML model
- tfidf_vectorizer.pkl – Text vectorizer

## How to Run
1. Build the Docker image:
   docker build -t spam-web-app .

2. Run the container:
   docker run -p 5000:5000 spam-web-app

3. Open browser:
   http://localhost:5000

## Author
Keerthana (PES2UG23CS273)
