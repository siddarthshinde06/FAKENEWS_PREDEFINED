# FAKENEWS_PREDEFINED
A simple and fast Flask-based Fake News Detection system that uses a trained machine-learning model (Logistic Regression) to classify input news text as Real or Fake.
This web app allows users to input any news headline or paragraph and instantly check whether it is Real or Fake.

📌 Features

🔍 Detect whether a news statement is Real or Fake
🧠 Machine Learning model (Logistic Regression)
📝 TF-IDF text vectorizer
🌐 Simple Flask web UI
🎨 Customizable frontend (CSS friendly)
⚡ Lightweight and easy to deploy

📁 Project Structure
.
├── app.py
├── vectorizer.jb
├── lr_model.jb
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── README.md

🚀 How to Run the Project

1. Clone the repository
git clone https://github.com/siddarthshinde06/FAKENEWS_PREDEFINED.git
cd FAKENEWS_PREDEFINED

2. Run the Flask app
   
python app.py

4. Open the App

Go to:
👉 http://127.0.0.1:5000/

🧠 Model Details

Algorithm: Logistic Regression
Vectorizer: TF-IDF
Training Data: Fake vs Real news dataset
Prediction Output:
Real News → Green color
Fake News → Red color

🖥 How It Works

User enters news text
Text is transformed using TF-IDF (vectorizer.jb)
Logistic Regression (lr_model.jb) predicts the label
Output is shown on the webpage

📸 Screenshots

Add screenshots of your UI here after you upload the project.

🛠 Technologies Used

Python
Flask
HTML / CSS
Scikit-learn
Joblib

📌 Future Improvements

Add BERT model
Add API version
Add database logging
Improve UI with animations

🤝 Contributing

Pull requests are welcome!

📜 License

This project is open-source and free to use.
