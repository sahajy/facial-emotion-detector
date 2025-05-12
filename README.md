# Facial Emotion Detection using IBM Cloud API
## 📌 Overview
This project detects human emotions from facial expressions in real-time or static images using **IBM Cloud's Facial Recognition API** and a **Flask-based web interface**. It classifies emotions into 7 categories: Happy, Sad, Angry, Disgust, Fear, Surprise, and Neutral.

## 🔍 Features
- **Real-time emotion detection** from webcam or uploaded images.
- **7-class emotion classification** using deep learning (CNN) via IBM Cloud API.
- **User-friendly Flask UI** for easy interaction.
- **Haar Cascade** for face detection.
- **Preprocessing pipeline** (grayscale conversion, resizing, normalization).

## 🛠️ Tech Stack
- **Backend**: Python, Flask, IBM Cloud Facial Recognition API
- **Frontend**: HTML, CSS, Bootstrap
- **Libraries**: 
  - `OpenCV` (face detection, image processing)
  - `Keras` (optional: local model training)
  - `NumPy`, `Pandas` (data handling)
- **Tools**: Anaconda, Spyder/VS Code

## 📂 Project Structure
```
facial-emotion-detector/
├── app.py                  # Flask backend
├── templates/              # HTML/CSS for UI
│   ├── index.html          # Homepage (upload image)
│   └── results.html        # Emotion prediction display
├── static/                 # CSS/JS files
├── haarcascade_frontalface_default.xml  # Haar Cascade model
├── requirements.txt        # Dependencies
└── README.md
```

## 🚀 How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/facial-emotion-detector.git
   cd facial-emotion-detector
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up IBM Cloud API**:
   - Sign up for [IBM Cloud](https://cloud.ibm.com/).
   - Get your API key and endpoint for the Facial Recognition service.
   - Replace placeholders in `app.py` with your credentials.

4. **Run the Flask app**:
   ```bash
   python app.py
   ```
   Open `http://127.0.0.1:5000` in your browser.

## 📊 Results
- Upload an image or use the webcam to detect faces and emotions.
- Example output:  
  ![Prediction: Happy](prediction_example.png) *(Optional: Add sample output)*

## ✅ Advantages
- **No expensive hardware** required (works with standard webcams).
- **HR/Managerial applications**: Monitor employee/customer moods.
- **Scalable**: Integrates with IoT (e.g., smart rooms adjusting ambience based on mood).

## ⚠️ Limitations
- **Dependency on image quality** (lighting, resolution).
- **Language barriers** in UI customization.
- **Cost**: High-accuracy systems may require premium APIs/hardware.

## 🌟 Applications
- **Human-Computer Interaction**: Adaptive UIs based on user emotion.
- **Mental Health**: Early detection of stress/depression.
- **Marketing**: Analyze customer reactions to products/ads.
- **Gaming/Social Robots**: Emotion-aware interactions.

## 📜 License
MIT License. See [LICENSE](LICENSE) for details.

## 🤝 Contributions
Contributions welcome! Open an issue or submit a PR for improvements.
