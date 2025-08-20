# 🌿 Plant Disease Detection Web App

This project is a **Flask-based web application** for detecting plant diseases using a pre-trained Convolutional Neural Network (CNN) model built with TensorFlow/Keras. Users can upload plant leaf images to receive predictions of potential diseases.

## 🚀 Features

- Upload a plant leaf image via the web interface.
- View the prediction result with the image preview.
- Built using Flask, OpenCV, TensorFlow, and Keras.
- Supports image formats: `.jpg`, `.jpeg`, `.png`, `.bmp`, `.tiff`, `.gif`.

## 🧠 Model Details

- The model is trained using TensorFlow/Keras.
- The input image size is resized to **128x128** pixels.
- The model is stored in the file: `trained_plant_disease_model.keras`.

## 📂 Directory Structure

project-root/ │ ├── trained_plant_disease_model.keras # Pre-trained Keras model ├── templates/ │ ├── index.html # Home page │ ├── about.html # About page │ └── result.html # Prediction results ├── uploads/ # Uploaded images (auto-created) ├── app.py # Main Flask app └── README.md # Project documentation



## 🖼️ Dataset
- The class names for prediction are extracted from a validation dataset folder:
C:\Users\DELL\Downloads\valid

> 📌 You should update this path or make it configurable for other users.

## 🔧 Setup Instructions

1. **Clone the repository:**
 git clone https://github.com/SurajKumarpandey001/Plant-Disease-Detection-WebApp.git
 cd plant-disease-detector

Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate

Install the dependencies:
pip install -r requirements.txt

Add your trained model:

Place the trained_plant_disease_model.keras file in the project root.
Ensure the validation dataset exists in the path specified in the code.

Run the app:
python app.py

Open in your browser:
http://127.0.0.1:5000/


✅ Requirements
Python 3.7+
Flask
TensorFlow
NumPy
OpenCV
Werkzeug
You can generate a requirements.txt using:
pip freeze > requirements.txt


🙌 Credits
Developed by Suraj Kumar
Feel free to use, modify, and share!

📬 Contact
Linkedin:https://www.linkedin.com/in/suraj-kumar-0136522a6/
Email: surajkumarpandey.ds@gmail.com



---

Let me know if you want me to generate `index.html`, `result.html`, or `requirements.txt` too.
