
# **Human Activity Classification Project**  

## **📌 Overview**  
This project focuses on **Human Activity Recognition (HAR) using Smartphones**, where study participants carried a smartphone equipped with an **inertial sensor** while performing **daily activities**. The goal is to classify these activities into one of six categories:  

✅ **Walking**  
✅ **Walking Upstairs**  
✅ **Walking Downstairs**  
✅ **Sitting**  
✅ **Standing**  
✅ **Laying**  

This classification is achieved using **machine learning** techniques on sensor data collected from accelerometers and gyroscopes.  

---

## **📂 Dataset Information**  
The dataset contains sensor data from the **Human Activity Recognition with Smartphones** database. Each record includes:  

🔹 **Triaxial Acceleration** – From the accelerometer (total acceleration & estimated body acceleration)  
🔹 **Triaxial Angular Velocity** – From the gyroscope  
🔹 **561 Feature Vector** – Containing time-domain and frequency-domain variables  
🔹 **Activity Label** – Corresponding to one of the six activities  

The data is **scaled from -1 (minimum) to 1.0 (maximum)** for better model performance.  

📌 **Sample Data Types (Last 5 Columns):**  

```python
data.dtypes.tail()
angle(tBodyGyroJerkMean,gravityMean)    float64
angle(X,gravityMean)                    float64
angle(Y,gravityMean)                    float64
angle(Z,gravityMean)                    float64
Activity                                 object
```

---

## **🚀 Project Objectives**  
✔️ **Preprocess & Clean Data** for ML models  
✔️ **Feature Engineering** to extract meaningful patterns  
✔️ **Train Classification Models** to predict activities  
✔️ **Evaluate Model Performance** using accuracy and confusion matrices  
✔️ **Optimize Performance** using hyperparameter tuning  

---

## **🛠️ Technologies Used**  
- **Python** 🐍  
- **Pandas, NumPy** (Data Handling)  
- **Scikit-Learn** (Machine Learning)  
- **Matplotlib, Seaborn** (Data Visualization)  
- **Jupyter Notebook** (Interactive Development)  

---

## **📊 Model Performance & Evaluation**  
📈 **Metrics Used:**  
✅ Accuracy  
✅ Precision  
✅ Recall  
✅ Confusion Matrix  

The dataset is well-balanced, and the models are evaluated to ensure **high classification accuracy** across all activity categories.  

---

## **📁 Folder Structure**  
```
📂 Human-Activity-Classification  
 ├── 📁 data/                # Dataset Files  
 ├── 📁 notebooks/           # Jupyter Notebooks  
 ├── 📁 models/              # Trained Models  
 ├── 📄 README.md            # Project Documentation  
 ├── 📄 requirements.txt     # Dependencies  
```

---

## **👨‍💻 How to Run the Project**  
1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/Tolumie/Human-Activity-Classification-Project.git
cd Human-Activity-Classification-Project
```
2️⃣ **Install Dependencies**  
```bash
pip install -r requirements.txt
```
3️⃣ **Run the Jupyter Notebook**  
```bash
jupyter notebook
```
4️⃣ **Train & Evaluate the Model**  

---

## **📌 Future Improvements**  
✅ Implement **Deep Learning (LSTMs, CNNs)** for better feature extraction  
✅ Improve real-time activity detection using **streaming data**  
✅ Optimize feature engineering for better **classification accuracy**  

---

## **📜 License**  
This project is open-source under the **MIT License**.  

🔗 **Contributions are welcome!** Fork this repo and submit a PR.  
