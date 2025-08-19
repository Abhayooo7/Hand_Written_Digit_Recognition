---
# 🧠 Hand-Written Digit Recognition


This project leverages machine learning techniques to recognize hand-written digits. Utilizing a dataset of handwritten digits, the model is trained to accurately classify digits from 0 to 9.

---

## 🔍 Project Overview

The goal of this project is to develop a machine learning model capable of recognizing hand-written digits. The dataset comprises images of digits, and the model is trained to classify these images into one of ten categories (0-9).

---

## ⚙️ Technologies Used

* **Programming Language**: Python
* **Machine Learning Framework**: TensorFlow
* **Data Handling**: NumPy
* **Image Processing**: OpenCV
* **Model Format**: `.model` file for saving the trained model

---

## 📁 Project Structure

```
Hand_Written_Digit_Recognition/
├── digits/               # Dataset of handwritten digits
├── handwritten.model     # Trained machine learning model
├── main.py               # Main script to run the digit recognition
└── README.md             # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following Python libraries installed:

```bash
pip install tensorflow numpy opencv-python
```

### Running the Model

1. Clone the repository:

   ```bash
   git clone https://github.com/Abhayooo7/Hand_Written_Digit_Recognition.git
   cd Hand_Written_Digit_Recognition
   ```

2. Execute the main script:

   ```bash
   python main.py
   ```

3. Follow the on-screen instructions to input hand-written digits for recognition.

---

## 📈 Model Details

* **Model Type**: Convolutional Neural Network (CNN)
* **Training Dataset**: Custom dataset of handwritten digits
* **Model Output**: Predicted digit class (0-9)

---
