<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=6A11CB&text=Crop%20Prediction%20System&height=150&fontSize=48" />
</p>
<p align="center">
  <img src="https://github.com/hidayathulla1234/Crop_Prediction/blob/master/assets/background.png?raw=true "/>
</p>


🌾 Crop Prediction System

A Machine Learning based Crop Recommendation System built using Python, Flask, and Random Forest Algorithm.
This project predicts the most suitable crop based on soil and environmental conditions.

📌 Project Overview

The Crop Prediction System helps farmers and agricultural planners decide which crop to cultivate based on input parameters such as:

Nitrogen (N)

Phosphorus (P)

Potassium (K)

Temperature

Humidity

pH value

Rainfall

The system uses a trained Random Forest Classifier to make accurate predictions.

🚀 Features

Machine Learning based crop prediction

Web interface using Flask

Trained model saved using model.pkl

Dataset included (Crop_recommendation.csv)

User-friendly input form

Instant crop prediction output

🛠️ Tech Stack

Python

Flask

Pandas

NumPy

Scikit-learn

HTML, CSS (Templates + Static folder)

📂 Project Structure
Crop_Prediction/
│
├── app.py                     # Flask web application
├── model.py                   # Model training script
├── model.pkl                  # Trained ML model
├── Crop_recommendation.csv    # Dataset
│
├── templates/                 # HTML templates
│   └── index.html
│
├── static/                    # CSS, images
│
└── README.md

📊 Dataset

The dataset contains soil and environmental parameters along with crop labels.

Example columns:

N	P	K	Temperature	Humidity	pH	Rainfall	Label
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/hidayathulla1234/Crop_Prediction.git
cd Crop_Prediction

2️⃣ Install dependencies
pip install -r requirements.txt


(If requirements.txt is not available, install manually:)

pip install flask pandas numpy scikit-learn

3️⃣ Train the Model (Optional)
python model.py


This will generate model.pkl.

4️⃣ Run the Application
python app.py


Open in browser:

http://127.0.0.1:5000/

🧠 Machine Learning Model

Algorithm Used: Random Forest Classifier

Model trained using Scikit-learn

Model saved using Pickle (model.pkl)

Accuracy depends on dataset split

🖥️ How It Works

User enters soil and climate data in the web form.

Flask receives input.

Data is converted into model-ready format.

Loaded model.pkl predicts crop.

Predicted crop is displayed on the webpage.

🎯 Future Improvements

Add fertilizer recommendation

Deploy on cloud (Heroku / Render / AWS)

Improve UI design

Add real-time weather API integration

Add accuracy visualization

<img width="1894" height="927" alt="image" src="https://github.com/user-attachments/assets/f2dbd4ca-bbf8-4f3e-8131-699977e8923a" />

Input Form

Prediction Result

🤝 Contribution

Feel free to fork this repository and contribute.

📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Shaik Hidayathulla
GitHub: https://github.com/hidayathulla1234

