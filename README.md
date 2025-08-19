# Driver Drowsiness Detection System 🚗💤

A **machine learning-based real-time system** that monitors driver eye behavior to detect drowsiness and prevent road accidents. The system uses a pre-trained **SVM model** for eye state classification and triggers an alarm when drowsiness is detected.

---

## 📌 Features

* Real-time eye detection using **OpenCV** and **dlib**
* Eye state classification (Open/Closed) using **SVM model**
* Audio alert system (`alarm.mp3`) to wake up drowsy drivers
* Model training (`train_eye.py`) and evaluation scripts included
* Lightweight and works with a standard webcam

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Libraries & Tools:** OpenCV, dlib, scikit-learn, NumPy
* **Machine Learning Model:** Support Vector Machine (SVM)

---

## 📂 Project Structure

```
driver-drowsiness-detection-system/
│── detect_drowsiness.py        # Main script for real-time detection
│── train_eye.py                 # Train SVM model for eye state classification
│── parse_eye.py                 # Eye state parsing utility
│── evaluate_error_and_validation.py  # Model evaluation script
│── eye_predictor.dat            # Pre-trained model data
│── alarm.mp3                    # Alert sound
│── README.md                    # Project documentation
```

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/driver-drowsiness-detection-system.git
   cd driver-drowsiness-detection-system
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

*(If you don’t have a `requirements.txt`, create one with the libraries used: OpenCV, dlib, scikit-learn, numpy)*

---

## ▶️ Usage

Run the detection system:

```bash
python detect_drowsiness.py
```

* The webcam will open and start monitoring the driver’s eye movements.
* If drowsiness is detected, an **alarm sound** will play.

---

## 📊 Model Training

To retrain the eye state classification model:

```bash
python train_eye.py
```

Evaluate the model:

```bash
python evaluate_error_and_validation.py
```

---

## 🎥 Demo

👉 *(Add a screenshot or a short GIF of your system running — this impresses recruiters)*

---

## 🌍 Impact

This project contributes to **road safety** by reducing accidents caused by driver fatigue, providing **real-time warnings** to drowsy drivers.

---

## 📜 License

This project is licensed under the MIT License – feel free to use and modify.
