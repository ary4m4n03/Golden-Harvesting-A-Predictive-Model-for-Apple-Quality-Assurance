

# 🍎 Golden Harvesting – Predictive Model for Apple Quality Assurance

A machine learning project that evaluates apple quality as 'good' or 'bad' based on various features such as size, weight, sweetness, crunchiness, juiciness, ripeness and acidity, helping automate and enhance quality control processes in agriculture.

---

## 💡 Overview

Golden Harvesting is a predictive model designed to:

* Take input of various quality features of apples.
* Classify apples based on quality grade.
* Assist farmers and suppliers in automating the sorting and inspection process.

---

## 🧠 Tech Stack

* **Python**
* **Sklearn**
* **Flask** for backend deployment
* **Jupyter Notebooks - Google Colab** for model building

---

## 📂 Folder Structure

```
📁 Golden-Harvesting-A-Predictive-Model-for-Apple-Quality-Assurance/
├── 📁 static/              # Assets, Demonstration and Output Screenshots
├── 📁 templates/           # HTML Pages
├── Golden_Harvesting_A_Predictive_Model_for_Apple_Quality_Assurance.ipynb             # Script to train the model
|── README.md              # Readme
├── app1.py                # Inference code
├── apple_quality.csv      # Dataset
├── best.pkl               # Best Model saved using Pickle
├── requirements.txt       # Requirements
```

---

## ⚙️ How to Run

1. **Clone the repo**

   ```bash
   git clone https://github.com/ary4m4n03/Golden-Harvesting-A-Predictive-Model-for-Apple-Quality-Assurance.git
   cd Golden-Harvesting-A-Predictive-Model-for-Apple-Quality-Assurance
   ```

2. **Install requirements**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run app1.py**

   ```bash
   python app1.py
   ```

4. **Launch local deployment**

   ```bash
   * Running on http://127.0.0.1:2000
   ```

---

## 🔍 Model Features

* **High Accuracy**: 90%+, Implements advanced regularization (L1 & L2), which helps prevent overfitting.
* **Parallel Processing**: Uses multithreading during training
* **Flexibility**: Can be integrated with cameras or sensors for automated quality assessment.

---

## ✅ Future Enhancements

* Deploy on mobile or edge devices (e.g., Raspberry Pi)
* Real-time camera input using OpenCV
* Dashboard for analytics and batch processing

---

