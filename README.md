# 🏠 Boston House Price Prediction Web App
A machine learning project that predicts house prices based on various features of a property. This application is built using Flask for the web interface and a pre-trained scikit-learn model.


🌟 Features
Web Interface: User-friendly web form to input house features.
Machine Learning Model: Utilizes a pre-trained regression model (e.g., Linear Regression, Random Forest, etc.) to estimate house prices.
Interactive Predictions: Get instant price predictions based on your inputs.
Clean & Modern UI: Styled with CSS for an attractive and responsive user experience.
Easy to Deploy: Simple Flask application structure.

🚀 Technologies Used
Python
Flask: Web framework for the backend.
Scikit-learn: For machine learning model training and prediction.
NumPy: Essential for numerical operations.
HTML/CSS: For the front-end web interface.


## 📊 Input Features

The user inputs the following attributes:

- `CRIM` — Per capita crime rate by town
- `ZN` — Proportion of residential land zoned for lots over 25,000 sq.ft.
- `INDUS` — Proportion of non-retail business acres per town
- `CHAS` — Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- `NOX` — Nitric oxides concentration (parts per 10 million)
- `RM` — Average number of rooms per dwelling
- `AGE` — Proportion of owner-occupied units built prior to 1940
- `DIS` — Weighted distances to five Boston employment centers
 - `RAD` — Index of accessibility to radial highways
- `TAX` — Full-value property-tax rate per $10,000
- `PTRATIO` — Pupil-teacher ratio by town
- `B` — 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents
- `LSTAT` — % lower status of the population


📋 Project Structure
house-price-prediction/
├── app.py                      
├── model.pkl                   
├── templates/
│   └── index.html              
└── README.md                   
└── requirements.txt            

⚙️ Setup and Installation
Follow these steps to get the project up and running on your local machine:

1. Clone the Repository
First, clone this GitHub repository to your local machine:
git clone https://github.com/<your-username>/house-price-prediction.git
cd house-price-prediction
2.. Create a Virtual Environment (Recommended)
It's highly recommended to use a virtual environment to manage project dependencies.
python -m venv venv
3.Activate the Virtual Environment
.\venv\Scripts\activate
4. Install Dependencies
Install all required Python packages using pip:
pip install -r requirements.txt
5. Run the Flask Application
Once all dependencies are installed, you can start the Flask development server:
python app.py
6. Access the Application
Open your web browser and navigate to the address provided in your terminal (usually http://127.0.0.1:5000/).

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
(If you haven't created a https://www.google.com/search?q=LICENSE file, you should! GitHub has a built-in tool to add one when you create a repo.)
