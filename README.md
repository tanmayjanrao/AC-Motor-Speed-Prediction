# 🚀 AC Motor Speed Prediction  

### *An AI-powered tool for predicting AC motor speed with ease!*  

---

## **📌 Business Objective**  
* The goal of this project is to develop an intelligent AC motor speed prediction system.  
* This solution aims to:  
  * ✅ Reduce manual effort in motor speed calculations.  
  * ✅ Improve prediction accuracy with machine learning.  
  * ✅ Provide real-time speed predictions with minimal intervention.  

---

## **🖥️ Motor Speed Predictor UI**  
![Motor Speed Predictor](https://github.com/tanmayjanrao/AC-Motor-Speed-Prediction/blob/main/image.png)

---

## **🛠️ How to Run the Web App**  

Since the required model files are too large for GitHub, you'll need to generate them yourself before running the app. Follow these steps:  

---

## 🔹 **Step 1: Run the Jupyter Notebook**  
* Open the provided **Jupyter Notebook** in your environment.  
* **Run the entire notebook** so that all cells execute, including the one that saves the model files.  
* The following files will be generated in the same directory as your notebook:  

  * `random_forest_model_df1.pkl`  
  * `scaler_df1.pkl`  
  * `target_scaler_df1.pkl`  

---

## 📂 **Step 2: Organize Files**  
* **Create a new folder** and move the three `.pkl` files into it.  

---

## 🔽 **Step 3: Download `main.py`**  
* Download **`main.py`** from this GitHub repository.  
* Move `main.py` into the same folder where you placed the `.pkl` files.  

---

## 🖥️ **Step 4: Open the Folder in VS Code**  
* Open **VS Code**.  
* Click on **File** → **Open Folder**, and select the folder containing:  
  * `main.py`  
  * `random_forest_model_df1.pkl`  
  * `scaler_df1.pkl`  
  * `target_scaler_df1.pkl`  

---

## 🚦 **Step 5: Run the Streamlit App**  
* Click on `main.py` to open it.  
* Open a **new terminal** in VS Code.  
* Run the following command:  

  ```sh
  streamlit run main.py
