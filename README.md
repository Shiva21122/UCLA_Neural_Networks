# UCLA_Neural_Networks

This project uses a neural network model to predict the likelihood of a student's admission to UCLA based on academic and personal profile data.

**What It Does**

- Trains a Multi-Layer Perceptron (MLP) using admission-related features

- Predicts the probability of admission

- Offers a user-friendly Streamlit interface to test the model

**Tools Used**

- Python

- Pandas, NumPy, scikit-learn

- Streamlit

- Matplotlib, Seaborn

**How It Works**

- Data is preprocessed and scaled

- An MLP model is trained and saved using pickle

- A Streamlit app loads the model and provides prediction based on user input

**Files**

- app.py — Streamlit web app

- ucla_mlp_model.pkl — Trained model

- requirements.txt — List of required libraries

**How to Run**

- Clone the repository

- Install dependencies: pip install -r requirements.txt

- Run: streamlit run app.py

**Note**
This is a basic educational demo meant for academic prediction exploration. It is not intended for real-world admissions decisions.
