Pain Recognition With Physiological Signals Using Multi-Level Context Information
Description

This project is developed to recognize and classify pain levels automatically using physiological signal data. The system uses machine learning and deep learning models to detect pain intensity from EEG/physiological signals. It provides a graphical user interface (GUI) using Tkinter, where the user can upload a dataset, preprocess it, train models, compare results, and predict pain levels.

Features
Upload physiological signals dataset (CSV format)
Preprocess and normalize dataset using MinMaxScaler
Split dataset into training and testing sets (80%-20%)
Train different models:
Random Forest (Existing Model)
CNN + BiLSTM (Proposed Model)
CNN + BiLSTM + BiGRU (Extension Model)
Display evaluation metrics:
Accuracy
Precision
Recall
F1-Score
Display confusion matrix graph
Display comparison performance graph
Predict pain type for new test samples
Technologies Used
Programming Language: Python
GUI: Tkinter
Machine Learning: Scikit-learn
Deep Learning: TensorFlow / Keras
Visualization: Matplotlib, Seaborn
Dataset Handling: Pandas, NumPy
Algorithms Used
Random Forest Classifier
CNN (Convolutional Neural Network)
BiLSTM (Bidirectional Long Short-Term Memory)
BiGRU (Bidirectional Gated Recurrent Unit)
How to Run
Step 1: Install Required Libraries

Run this command in Command Prompt:

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
Step 2: Place Dataset
Keep your dataset inside a folder named Dataset
Dataset should be in CSV format
Step 3: Run the Python File

Run the project file:

python main.py
Step 4: Use GUI Buttons in Order
Upload Dataset
Preprocess & Split Dataset
Run Random Forest
Run CNN + BiLSTM
Run CNN + BiLSTM + BiGRU
Comparison Graph
Predict
Output
Confusion Matrix for each model
Comparison Graph of Accuracy, Precision, Recall, F1-score
Pain Level Prediction output displayed in GUI
Pain Classes
Pain0
Pain1
Pain2
Pain3
Pain4
