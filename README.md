# 🧵 Fabric Pattern Classification Web App (Flask + TensorFlow)

This project is a **Flask-based web application** that classifies fabric patterns from uploaded images using a **trained TensorFlow/Keras CNN model**.  
Users can upload a fabric image, and the app predicts the pattern type such as floral, geometric, polka dot, or stripes.

---

## 🚀 Features

- Upload fabric images through a web interface
- Preprocess images automatically
- Predict fabric pattern using a trained deep learning model
- Display predicted class along with uploaded image
- Simple and clean Flask UI

---

## 🧠 Fabric Classes

The model predicts the following fabric patterns:

- Floral  
- Geometric  
- Polka Dot  
- Stripes  

---

## 🛠 Tech Stack

- **Backend:** Flask (Python)
- **Deep Learning:** TensorFlow, Keras
- **Frontend:** HTML (Jinja templates)
- **Image Processing:** PIL, NumPy

---

## 📂 Project Structure

├── app.py
├── fabric_model.h5
├── templates/
│ ├── index.html
│ ├── predict.html
│ └── results.html
├── static/
│ └── uploads/
├── README.md
├── requirements.txt

yaml
Copy code

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/fabric-pattern-classification.git
cd fabric-pattern-classification
2️⃣ Create Virtual Environment (Optional)
bash
Copy code
python -m venv venv
source venv/bin/activate    # macOS/Linux
venv\Scripts\activate       # Windows
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
📦 Required Python Packages
nginx
Copy code
flask
tensorflow
keras
numpy
pillow
▶️ Run the Application
bash
Copy code
python app.py
Then open your browser and go to:

cpp
Copy code
http://127.0.0.1:5000/
