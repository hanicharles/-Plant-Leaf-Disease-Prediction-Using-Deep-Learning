

# 🍅 Haniscan: Tomato Leaf Disease Prediction

![Image](https://ag.purdue.edu/department/arge/swpap/_media/early-blight-of-tomato-6.jpg)

![Image](https://homesteadgardens.com/wp-content/uploads/late_blight_tomato_leaf5x12001-1.jpg)

![Image](https://content.ces.ncsu.edu/media/images/IMG_5369.jpeg)

![Image](https://gardenbetty.com/wp-content/uploads/2020/07/edible-tomato-leaves.jpg)

## 📌 Project Overview

Haniscan is a **deep learning–based web application** that detects and classifies diseases in tomato plant leaves using **image processing and transfer learning models**.
The system helps farmers and agricultural experts **identify diseases at an early stage**, reducing crop loss and improving productivity.

---

## 🎯 Objectives

* Detect tomato leaf diseases from uploaded images
* Classify diseases using **pre-trained deep learning models**
* Provide a **simple web interface** for real-time prediction
* Assist in **early diagnosis** to prevent disease spread

---

## 🧠 Diseases Covered

* 🍂 Early Blight
* 🍃 Late Blight
* 🦠 Yellow Leaf Curl Virus
* 🌱 Healthy Leaf

---

## 🛠️ Technologies Used

### 🔹 Machine Learning & Deep Learning

* Python
* TensorFlow / Keras
* Transfer Learning

### 🔹 Models Implemented

* **InceptionV3**
* **ResNet50**

### 🔹 Web Development

* Flask
* HTML5, CSS3, JavaScript

---

## 📂 Project Structure

```bash
haniscan/
│
├── app.py                       # Flask application
├── requirements.txt             # Required Python libraries
├── Transfer Learning Inception V3.ipynb
├── Transfer Learning Resnet 50.ipynb
│
├── static/
│   ├── css/
│   │   └── main.css
│   └── js/
│       └── main.js
│
├── templates/
│   ├── base.html
│   └── index.html
│
├── uploads/                     # Uploaded leaf images
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/haniscan.git
cd haniscan
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
python app.py
```

### 4️⃣ Open in Browser

```
http://127.0.0.1:5001/
```

---

## 🚀 How It Works

1. User uploads a tomato leaf image
2. Image is preprocessed
3. Deep learning model predicts the disease class
4. Result is displayed on the web interface

---

## 📊 Model Highlights

* Uses **transfer learning** for better accuracy
* Reduces training time and overfitting
* Suitable for real-world agricultural use

---

## 📈 Future Enhancements

* Support for more crop diseases
* Mobile application integration
* Disease treatment recommendations
* Accuracy comparison dashboard

---

## 📄 Research Relevance

This project aligns with **AI in Agriculture**, focusing on:

* Crop health monitoring
* Precision farming
* Sustainable agriculture

---

## 👨‍💻 Author

**Chalukya Nayaka B K**
🎓 M.Tech (Cybersecurity) | AI & ML Enthusiast
🌐 Portfolio: [https://chalukyanayakabk.netlify.app](https://chalukyanayakabk.netlify.app)
🔗 LinkedIn: [https://linkedin.com/in/chalukya-nayaka-b-k-131b232aa](https://linkedin.com/in/chalukya-nayaka-b-k-131b232aa)

---

## ⭐ Acknowledgements

* Open-source datasets
* TensorFlow & Keras community
* Research contributions in plant disease detection

---

### 🌟 If you find this project useful, don’t forget to **star the repository**!
