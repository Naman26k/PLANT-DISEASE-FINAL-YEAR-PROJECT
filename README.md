# Plant Disease Detection and Classification Using Deep Learning

A comprehensive end-to-end deep learning application designed to detect, classify, and diagnose crop leaf diseases from images. This project was developed as a Bachelor of Engineering (B.E.) Final Year Capstone Project in Computer Science and Engineering.

---

## 🚀 Overview
Agricultural productivity heavily relies on early and accurate detection of crop diseases. This project bridges the gap between deep learning research and practical deployment by implementing a convolutional neural network (CNN) model trained on agricultural datasets and integrating it into a responsive web application for real-time inference.

### Key Highlights:
* **Deep Learning Model:** Built using Python, TensorFlow, and Keras to classify plant health status and specific disease categories.
* **Dataset:** Trained and evaluated using standardized agricultural image repositories (such as PlantVillage).
* **Web Deployment:** Integrated into an interactive Flask/Web backend that accepts user image uploads and renders real-time diagnostic predictions.
* **Software Engineering Standards:** Developed following modular software architecture, version control practices, and structured exception handling.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Deep Learning Framework:** TensorFlow, Keras, NumPy, Pandas
* **Image Processing:** OpenCV, Pillow (PIL)
* **Web Framework:** Flask
* **Environment & Tools:** Git, Jupyter Notebook, Visual Studio Code

---

## 📂 Project Architecture

```text
PLANT-DISEASE-FINAL-YEAR-PROJECT/
│
├── dataset/              # Training, validation, and test image splits
├── models/               # Saved trained model weights (.h5 / .keras)
├── static/               # CSS, stylesheets, and uploaded asset directories
├── templates/            # HTML front-end views and UI templates
├── app.py                # Main Flask backend application server
├── train_model.py        # CNN architecture definition, training, and evaluation script
├── requirements.txt      # Project dependencies and package versions
└── README.md             # Project documentation
