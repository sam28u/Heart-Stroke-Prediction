# Heart Disease Model Web App

This repository contains a small web application that demonstrates a machine learning model for predicting heart disease risk from clinical features. The app is built with a simple Python web framework and exposes an interactive UI for uploading inputs and viewing predictions.

**Live Demo**

- Demo: https://heartstrokepred.streamlit.app/  

**Key Features**

- Interactive web UI for entering patient features and viewing probability of heart disease.
- Preprocessing pipeline included to match model training (scaling/encoding as needed).
- Example sample input and explanation of model outputs.

**Dataset & Model**

- Dataset: originally trained on a public heart disease dataset (CSV). 
- Model: a scikit-learn classifier saved as a serialized file (e.g., `knn_heart_model.pkl`). 


**Run locally**

1. Create and activate a virtual environment

```powershell
python -m venv venv
venv\Scripts\Activate.ps1   # PowerShell on Windows
```

2. Install dependencies

```powershell
pip install -r requirements.txt
```

3. Start the app

```powershell
streamlit run app.py
```

4. Open the provided localhost URL shown in the terminal (usually http://127.0.0.1:8501 or http://127.0.0.1:5000 depending on framework).


**Project Structure**

- `app.py` — main app runner
- `requirements.txt` — Python dependencies
- `knn_heart_model.pkl` or similar — serialized trained model (not checked in by default)



**Contact**

- For questions or help, reply here or add an issue in the repo.

