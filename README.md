💻 Laptop Price Predictor App 🧠

This is a Streamlit web application that predicts the price of a laptop based on various features like brand, type, processor, RAM, storage, screen size, etc. The model is trained on a dataset obtained from Kaggle.

✨ Features

Interactive UI: Built with Streamlit for easy interaction

Input Parameters: Company, Laptop Type, CPU, RAM, GPU, OS, Weight, IPS Panel, Touchscreen, Storage (SSD/HDD), Screen Size, and Resolution

Real-time Prediction: Predicts laptop price instantly based on user inputs

⚙️ How It Works

Load the trained machine learning pipeline from pipe.pkl

Load the preprocessed DataFrame from df.pkl

Use user inputs from UI to format a feature vector

Make prediction using the model

Display predicted price in Indian Rupees

🚀 Installation and Running

🧾 Requirements

Make sure you have Python installed. Then install dependencies with:

pip install -r requirements.txt

▶️ Run the App

streamlit run app\ (3).py

Note: If running on Unix-like systems, rename the file to remove spaces.

📁 Files Included

app (3).py: Main Streamlit application script

pipe.pkl: Trained machine learning model pipeline

df.pkl: Preprocessed DataFrame used for feature values

requirements.txt: Python dependencies

📊 Dataset

The dataset used for training was sourced from Kaggle and includes a variety of laptop configurations and their respective prices.

⚠️ Disclaimer

The predicted price may not match real-world values exactly. It is intended for educational and demonstrative purposes only.
