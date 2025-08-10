# 🐶🐱 Cat vs Dog Classifier

A fun **Deep Learning** project built using **TensorFlow & Keras** that can tell whether a given image is a **Cat** or a **Dog** 🖼️.  

It comes with:
- **Training script** (`train.py`) – to train your own model
- **CLI prediction script** (`main.py`) – to test from the terminal
- **Streamlit app** (`gui.py`) – to upload and get instant predictions from your browser

---

## 📂 Project Structure

cat-dog-classifier/
│
├── dataset/ # Dataset (Cats & Dogs images)
├── train.py # Train the CNN model
├── main.py # Command-line predictions
├── gui.py # Streamlit-based GUI app
├── cat_dog_model.h5 # Saved trained model
├── requirements.txt # Dependencies
└── README.md # Project documentation


---

## 🚀 How It Works
1. **Training** → A **Convolutional Neural Network (CNN)** learns from thousands of cat and dog images.
2. **Prediction** → The model predicts the probability of the image being a cat or a dog.
3. **GUI** → A user-friendly web interface allows you to upload an image and get results instantly.

---

## 🛠️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/cat-dog-classifier.git
cd cat-dog-classifier
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Get the Dataset
Download from Kaggle:


kaggle datasets download -d tongpython/cat-and-dog
unzip cat-and-dog.zip -d dataset
(Make sure you have kaggle.json API key set up in ~/.kaggle/)



📜 License
This project is licensed under the MIT License – you are free to use, modify, and share.

🙌 Acknowledgements
Dataset: Kaggle Cats and Dogs

Framework: TensorFlow

GUI: Streamlit
