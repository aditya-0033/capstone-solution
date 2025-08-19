📘 Capstone Project: Comparative Analysis & Vision Transformers
📌 Overview

This capstone project demonstrates:

✅ Comparative analysis of Keras vs PyTorch models

✅ Implementation of a CNN + Vision Transformer hybrid in Keras

✅ Unit testing for API, models, and logging

✅ Dockerized setup for reproducibility

It covers both Module 2 (Comparative Analysis) and Module 3 (Vision Transformers in Keras).

🚀 Getting Started
1. Clone the repository
git clone https://github.com/aditya-0033/capstone-solution.git
cd capstone-solution

2. Install dependencies
pip install -r requirements.txt

3. Run Jupyter notebooks
jupyter lab


Open and run:

notebooks/module2_comparative_analysis.ipynb

notebooks/module3_vision_transformers.ipynb

4. Run Unit Tests
pytest tests/

5. Run API (Flask)
python src/api.py


Test in browser:
👉 http://127.0.0.1:8000/predict?country=India

Expected output:

{"country": "India", "prediction": "dummy_result"}

🐳 Docker Usage
Build image
docker build -t capstone-solution .

Run container
docker run -p 8000:8000 capstone-solution

📊 Features

Model training & evaluation (Keras & PyTorch)

Hybrid CNN + Vision Transformer architecture

Unit tests for API, model, logging

Automated data ingestion function

Docker containerization

✨ Author

👤 Aditya Chauhan
"Together, we build better ideas."
