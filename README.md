# 🛒 Unishop E-commerce Recommendation System API

A smart, scalable product recommendation system built for the Unishop E-commerce platform. This project uses Python and Flask to deliver personalized product recommendations via a lightweight REST API.

## 🚀 Features

- 🧠 **Content-Based & Collaborative Filtering** recommendation algorithms
- 🔌 **RESTful API** built with Flask for easy integration
- 📊 Real-time recommendations based on user behavior and product metadata
- 🗂️ Scalable architecture suitable for microservices deployment
- 🔐 Secure API endpoints (optional JWT authentication support)

---

## 🏗️ Tech Stack

- **Backend Framework**: Flask (Python)
- **Data Handling**: Pandas, NumPy
- **Recommendation Engine**: Scikit-learn, Surprise, or custom logic
- **API Testing**: Postman / cURL

---

## 📁 Project Structure
unishop-recommender/
│
├── app/
│ ├── init.py
│ ├── routes.py # API endpoints
│ ├── recommender.py # Recommendation engine logic
│ ├── models/ # Data models or ORM (if any)
│ └── utils/ # Helper functions
│
├── data/
│ ├── products.csv # Sample product dataset
│ └── user_behavior.csv # Sample user interaction data
│
├── tests/
│ └── test_api.py # Unit tests for endpoints
│
├── requirements.txt # Python dependencies
├── Dockerfile # (Optional) Docker config
├── config.py # Configuration settings
└── run.py # Entry point for the Flask app
---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/unishop-recommender.git
cd unishop-recommender
```
2. Create and activate a virtual environment
bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt

▶️ Running the Application
bash
Copy
Edit
python run.py
The API will be available at: http://127.0.0.1:5000/
