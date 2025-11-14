# 📱 Mobile Price Range Prediction App

[![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-FF4B4B?logo=streamlit\&logoColor=white)]()
[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)]()
[![Machine Learning](https://img.shields.io/badge/ML-Classification-green)]()


---

## 🔗 Live App

🚀 Try the live model here:
👉 **[https://loanpredictionproject-tejasgholap.streamlit.app/](https://loanpredictionproject-tejasgholap.streamlit.app/)**
*(Replace with correct Streamlit link for this mobile project once deployed.)*

---

## 🧠 Project Overview

This web application predicts the **price range of a mobile phone** based on its internal specifications.
The machine learning model classifies mobiles into **four categories**:

| Value | Meaning        |
| ----- | -------------- |
| 0     | Low Cost       |
| 1     | Medium Cost    |
| 2     | High Cost      |
| 3     | Very High Cost |

This helps consumers, analysts, and sellers understand where a phone stands in the market based on hardware features.

---

## 🎯 Features

✔️ Predicts mobile price category instantly
✔️ Clean & modern Streamlit UI
✔️ 20+ hardware specifications supported
✔️ Uses a trained ML model stored as `best_ml.pkl`
✔️ Sidebar-based input form
✔️ Human-readable price category output

---

## 🧩 Input Parameters

The app uses the following 20 mobile features:

| Feature       | Description              |
| ------------- | ------------------------ |
| battery_power | Total battery capacity   |
| blue          | Bluetooth availability   |
| clock_speed   | Processor speed          |
| dual_sim      | Dual SIM support         |
| fc            | Front camera MP          |
| four_g        | 4G support               |
| int_memory    | Internal storage (GB)    |
| m_dep         | Mobile depth (cm)        |
| mobile_wt     | Weight of mobile (grams) |
| n_cores       | Number of CPU cores      |
| pc            | Primary camera MP        |
| px_height     | Pixel height             |
| px_width      | Pixel width              |
| ram           | RAM in MB                |
| sc_h          | Screen height            |
| sc_w          | Screen width             |
| talk_time     | Battery backup (hours)   |
| three_g       | 3G support               |
| touch_screen  | Touch screen support     |
| wifi          | WiFi availability        |

---

## 🖥️ Tech Stack

| Layer     | Technology                  |
| --------- | --------------------------- |
| Frontend  | Streamlit                   |
| Backend   | Python                      |
| ML Model  | RandomForest / XGBoost      |
| Libraries | NumPy, Pickle, Scikit-learn |

---

## 📂 Project Structure

```
Mobile-Price-Prediction/
│
├── app.py                # Main Streamlit application
├── best_ml.pkl           # Trained ML classification model
├── requirements.txt      # Dependencies
└── README.md             # Documentation
```

---

## 🏁 Running the App Locally

1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/Mobile-Price-Prediction.git
cd Mobile-Price-Prediction
```

2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

3️⃣ Run Streamlit

```bash
streamlit run app.py
```

4️⃣ Visit in your browser

```
http://localhost:8501
```

---

## 📦 requirements.txt

```
streamlit
numpy
scikit-learn
pickle5
```
---
```
```
---

## 👨‍💻 Developer

**Tejas Gholap**
MCA Student | ML & AI Enthusiast

🔗 GitHub: [https://github.com/tejasgholap45](https://github.com/tejasgholap45)
🔗 LinkedIn: [https://www.linkedin.com/in/tejas-gholap-bb3417300/](https://www.linkedin.com/in/tejas-gholap-bb3417300/)

---

## 🙏 Acknowledgements

* Streamlit for seamless deployment
* Open-source ML libraries
* Dataset providers
