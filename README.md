# Plant_disease_detector
AI-powered Plant Disease Detector that identifies diseases from leaf images using deep learning. Features include real-time disease detection, chatbot assistance for crop recommendations, and a responsive UI. Built with Flask, TensorFlow, and a user-friendly web interface.

Plant Disease Detector

📌 Project Overview

The Plant Disease Detector is an AI-powered web application that identifies plant diseases from leaf images using deep learning. The system utilizes a trained model to classify diseases and provides crop recommendations, nutrient requirements, and water management guidelines through an integrated chatbot. This project is designed to assist farmers and agricultural experts in early disease detection and prevention, ultimately improving crop yield and quality.

🔑 Key Features

🌿 AI-Powered Disease Detection: Upload an image of a plant leaf to detect diseases with high accuracy.

💬 Chatbot Assistance: Provides crop recommendations, nutrient requirements, and water management guidelines.

🌍 Multilingual Support: Users can switch languages for accessibility.

📸 Image Upload & Preview: Automatically previews uploaded images before analysis.

📱 Responsive UI: A user-friendly interface optimized for both desktop and mobile users.

📊 Real-time Results: Displays disease detection results instantly with relevant recommendations.

📂 Project Structure

Plant-Disease-Detector/
│-- bomb_ai/ (Web Application Files)
│   │-- static/
│   │   │-- css/ (Stylesheets)
│   │   │-- js/ (JavaScript Files)
│   │   │-- images/ (Assets)
│   │-- templates/
│   │   │-- index.html (Main Webpage UI)
│   │-- server.py (Flask Backend)
│   │-- model/ (Trained Model Files)
│   │-- requirements.txt (Python Dependencies)
│-- README.md (This Documentation)

🚀 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-repository/Plant-Disease-Detector.git
cd Plant-Disease-Detector

2️⃣ Install Dependencies

Ensure you have Python installed, then run:

pip install -r requirements.txt

3️⃣ Run the Flask Server

python server.py

The backend will start running on http://127.0.0.1:5000/

4️⃣ Open the Web Application

Navigate to the project directory and open index.html in a browser.

🔥 Model & AI Pipeline

Dataset: Trained on the PlantVillage dataset.

Preprocessing: Image augmentation and normalization.

Model Architecture: Convolutional Neural Networks (CNNs) for high-accuracy classification.

Deployment: The model is served using Flask, and predictions are sent to the frontend.

📌 API Endpoints

Endpoint

Method

Description

/

GET

Loads the main webpage

/predict

POST

Accepts an image and returns disease results

/chatbot

POST

Provides crop and nutrient recommendations

🖥️ Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Python, Flask

AI Model: TensorFlow/Keras (CNN-based)

Database: JSON-based storage (for chatbot data)

🤝 Contributing

We welcome contributions! Feel free to fork the repo, create pull requests, and submit bug reports.

🚀 Let's revolutionize agriculture with AI! 🌿

