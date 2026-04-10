# 🚀 VisionCaption AI – Image Caption Generator

🔗 GitHub Repository: https://github.com/Aditya00010/-AI-Image-Caption-Generator

---

## 📌 Project Overview

This project is an **AI-based Image Caption Generator** that generates meaningful captions for images using Deep Learning.

The system is based on a **CNN-LSTM architecture**, where:

* **CNN (VGG16 / MobileNetV2)** extracts features from images
* **LSTM** generates captions word-by-word

The model was trained using an existing implementation and dataset.

---

## 🧠 Key Features

* 📷 Upload any image
* 🤖 Automatically generates a caption
* 🌐 Interactive UI using Streamlit
* ⚡ Deep Learning-based approach

---

## 🏗️ Tech Stack

* Python 🐍
* TensorFlow / Keras
* CNN (VGG16 / MobileNetV2)
* LSTM
* Streamlit

---

🌐 Live Demo

🚀 Try the app here:
👉 https://visioncaption-aditya-2026.streamlit.app/

## ⚙️ How It Works

1. Image is uploaded by the user
2. CNN extracts important features from the image
3. Features are passed to the LSTM model
4. LSTM generates caption step-by-step
5. Final caption is displayed

---

## 📂 Project Structure

```
AI-Image-Caption-Generator/
│
├── app.py                  # Streamlit application
├── mymodel.h5              # Trained model
├── tokenizer.pkl           # Tokenizer
├── requirements.txt        # Dependencies
├── image-captioner.ipynb   # Training notebook
└── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/Aditya00010/-AI-Image-Caption-Generator.git
cd -AI-Image-Caption-Generator
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run the application

```
streamlit run app.py
```

---

## 📊 Model Details

* CNN: VGG16 / MobileNetV2
* RNN: LSTM
* Dataset: Flickr8k
* Architecture: Encoder-Decoder (CNN-LSTM)

---

## 📸 Sample Output

**Input:** Image
**Output:** *Generated caption describing the image*

---

## 🚀 Future Improvements

* Train on larger datasets (Flickr30k / MS COCO)
* Improve caption accuracy
* Add better UI/UX
* Deploy with GPU support

---

## 👨‍💻 Author

**Aditya Yadav**

---

## ⭐ Acknowledgement

This project is implemented using an existing deep learning approach for image caption generation.

---
