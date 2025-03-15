# AC-Motor-Speed-Prediction

🚀 AC Motor Speed Prediction
📌 How to Run the Web App
Since the required model files are too large for GitHub, you'll need to generate them yourself before running the app. Follow the steps below carefully.

🛠️ Step 1: Run the Jupyter Notebook
Open the provided Jupyter Notebook in your environment.

Run the entire notebook to ensure all cells execute, including the one that saves the model files.

After execution, the following files will be saved in the same directory as the notebook:

✅ random_forest_model_df1.pkl
✅ scaler_df1.pkl
✅ target_scaler_df1.pkl

📂 Step 2: Organize Files
Create a new folder and move the three .pkl files into it.
🔽 Step 3: Download main.py
Download main.py from this GitHub repository.
Move main.py into the same folder where you placed the .pkl files.
🖥️ Step 4: Open the Folder in VS Code
Open VS Code.
Click on File → Open Folder, and select the folder containing:
main.py
random_forest_model_df1.pkl
scaler_df1.pkl
target_scaler_df1.pkl
🚦 Step 5: Run the Streamlit App
Click on main.py to open it.

Open a new terminal in VS Code.

Run the following command:

streamlit run main.py
Your web app will launch in your browser! 🎉

