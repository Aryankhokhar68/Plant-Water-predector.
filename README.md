# Plant-Water-predector.
This project uses a Random Forest Classifier to predict the water requirement level of plants based on features such as soil type, temperature, humidity, sunlight exposure, and other environmental factors.
📌 Key Features
Dataset: Loaded from plants.csv, includes plant and environmental features.

Preprocessing:

Label encoding for categorical data (soil_type, water_need)

Feature scaling using StandardScaler

Model: Trained using RandomForestClassifier from Scikit-learn

Evaluation Metrics:

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

Visualization:

Heatmap of the Confusion Matrix

Feature Importance Bar Plot

🎯 Objective
To aid smart agriculture or automated irrigation by predicting plant water needs based on measurable environmental inputs.

📦 Tools & Libraries
Python, Pandas, NumPy

Scikit-learn

Seaborn, Matplotlib

