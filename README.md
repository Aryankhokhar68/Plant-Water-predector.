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
RESULT:
![image](https://github.com/user-attachments/assets/2397e01b-27b8-43d1-9f05-aacc8df4ebe8)
Classification Report:
              precision    recall  f1-score   support

        high       0.29      0.40      0.33         5
         low       0.38      0.27      0.32        11
      medium       0.20      0.25      0.22         4

    accuracy                           0.30        20
   macro avg       0.29      0.31      0.29        20
weighted avg       0.32      0.30      0.30        20

<ipython-input-5-f373ca423c65>:71: FutureWarning: 

Passing `palette` without assigning `hue` is deprecated and will be removed in v0.14.0. Assign the `y` variable to `hue` and set `legend=False` for the same effect.

  sns.barplot(
  ![image](https://github.com/user-attachments/assets/ee838abe-be07-4f86-84b6-01dd38004227)


  


