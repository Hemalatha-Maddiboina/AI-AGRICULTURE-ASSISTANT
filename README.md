# AI-AGRICULTURE-ASSISTANT
🌾 AI Agriculture Assistant – Gradio Application Smart Crop Disease Prediction using Text, Voice, and Image Inputs  The AI Agriculture Assistant is an intelligent, user-friendly Gradio-based application designed to help farmers and agricultural students identify crop diseases and receive recommended solutions. 
A Smart Crop Disease Prediction System using Text, Voice & Image Inputs (Runs on Google Colab)
📌 Overview

The AI Agriculture Assistant is an AI-powered Gradio application designed to help farmers identify crop diseases and receive scientific solutions.
The model accepts three types of inputs:

📝 Text (typed symptoms)

🎤 Voice (spoken symptoms → speech-to-text → prediction)

📸 Image (leaf/crop photo for visual disease detection)

The project is fully executable in Google Colab with no local installation required.

🎯 Features
✔️ 1. Text-Based Disease Prediction

Users can type symptoms (e.g., yellow leaves with black spots) and get:

Disease name

Description

Causes

Control methods

Preventive measures

✔️ 2. Voice-Based Prediction

Supports real-time speech-to-text using Google SpeechRecognition API.
Useful for farmers who prefer voice input.

✔️ 3. Image-Based Disease Detection

Upload crop/leaf images to detect visual plant diseases using a pretrained transformer model.

✔️ 4. Multilingual Support (Optional)

Uses googletrans-py for translating symptoms to English if the user types in another language.

✔️ 5. Gradio Interface

Simple, mobile-friendly UI with 3 tabs:

Text Input

Voice Input

Image Input

🧠 Technologies Used
Component	Technology
UI	Gradio
Text prediction	HuggingFace Transformers
Image prediction	Vision Transformer (ViT) / HuggingFace model
Speech-to-text	SpeechRecognition
Translation (optional)	googletrans-py
Backend	Python
Platform	Google Colab
📂 Project Structure
AI-Agriculture-Assistant/
│
├── notebooks/
│   └── AI_Agriculture_Assistant.ipynb   # Main Google Colab Notebook
│
├── images/
│   └── sample_leaf.jpg
│
├── README.md
└── requirements.txt

🚀 How to Run the Project (Google Colab)
Step 1: Open the Notebook

Click the link below (replace with your notebook link):
👉 https://colab.research.google.com/your-notebook-link

Step 2: Install Dependencies
!pip install gradio==4.36.1 SpeechRecognition googletrans-py transformers pillow

Step 3: Run the Code

Simply run all cells until the last one.
At the end, Gradio will generate a public link:

Running on public URL: https://xxxx.gradio.live


Click the link → Your AI Assistant opens.

🧪 Model Details
🔤 Text Model

Type: Transformer-based text classification

Dataset: Agriculture symptom-description pairs

Output: Disease name + solution

🖼️ Image Model

Type: Vision Transformer (ViT)

Input: Crop/leaf image

Output: Predicted disease

🎤 Voice Model

Uses Google SpeechRecognition

Language: Auto-detect

Converts speech → text → prediction

📸 Screenshots

(Add screenshots here)
Example:

![](images/ui_preview.png)

🧩 Future Enhancements

Add fertilizer recommendation system

Add weather-based disease forecasting

Add Kannada/Telugu/Hindi voice support

Add mobile app integration

Add real-time drone image analysis

🛡️ License

This project is licensed under the MIT License.

💡 Contributions

Contributions are welcome!
Please create a pull request or open an issue.

👨‍🌾 Developed By

[MADDIBOINA HEMALATHA]
AI/ML Developer | Agriculture Technology Enthusiast
📧 Email: maddiboinahema@gmail.com

📍 India
