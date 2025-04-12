🌿 Plant Disease Detection using CNN

A deep learning-based web application that allows users to upload images of plant leaves, detects the disease (if any) using a Convolutional Neural Network (CNN), and provides recommendations including supplements and protective measures to cure or prevent the disease.

---

🧠 Features

- 📷 Upload leaf images directly via the web interface
- 🧪 Predicts plant diseases using a trained CNN model
- 💊 Suggests fertilizers/supplements
- 🛡️ Recommends protective measures to minimize crop damage
- 🔁 Easy-to-use interface with fast, accurate results

---

🚀 Tech Stack

- **Frontend**: HTML, CSS, JavaScript (or React if applicable)
- **Backend**: Flask / MySql
- **Machine Learning**: TensorFlow / Keras CNN model
- **Dataset**: PlantVillage or custom collected dataset

---

## 📸 Sample Usage

1. Upload a clear image of a plant leaf.
2. The model analyzes the image to detect the disease.
3. Get instant feedback with:
   - ✅ Disease Name
   - 🧪 Required supplements
   - 🛡️ Preventive measures

---

## 🧪 Model Details

- CNN architecture trained on thousands of labeled leaf images.
- Achieves high accuracy on a wide range of common plant diseases.

---

## 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/plant-disease-detection-cnn.git
   cd plant-disease-detection-cnn
   python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
