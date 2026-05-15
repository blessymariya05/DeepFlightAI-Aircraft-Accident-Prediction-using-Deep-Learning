# DeepFlightAI-Aircraft-Accident-Prediction-using-Deep-Learning
DeepFlightAI is an AI-powered aviation safety analysis project developed using Python, TensorFlow, and Machine Learning techniques. The main goal of the project is to predict accident occurrence using historical airline accident datasets and deep learning models.
## Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Seaborn

---

## Deep Learning Concepts Used

- LSTM Neural Networks
- Dense Neural Networks
- Binary Classification
- Data Preprocessing
- Feature Scaling
- Sequence Generation
- Early Stopping
- Feature Importance Analysis
- Confusion Matrix
- Accuracy Evaluation

---

## Dataset Features

The dataset contains aviation-related numerical features including:

- Total Fatal Injuries
- Total Serious Injuries
- Total Minor Injuries
- Total Uninjured
- Latitude
- Longitude
- Number of Engines

---

## Project Workflow

1. Load aviation accident dataset
2. Convert required columns into numeric format
3. Create target variable for accident occurrence
4. Handle missing values
5. Normalize features using StandardScaler
6. Create sequences for LSTM model
7. Split data into training and testing sets
8. Train LSTM deep learning model
9. Evaluate model performance
10. Visualize training results and predictions
11. Analyze feature importance

---

## Model Architecture

The project uses:
- LSTM Layer
- Dense Layers
- Dropout Layers
- Sigmoid Activation for Binary Classification

---

## Visualizations Included

- Training Loss Graph
- Training Accuracy Graph
- Confusion Matrix
- Prediction Probability Distribution
- Feature Importance Graph

---

## Evaluation Metrics

The model evaluation includes:
- Accuracy
- Precision
- Recall
- Classification Report
- Confusion Matrix

---

## Libraries Used

```python
import pandas as pd
import numpy as np
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.metrics import classification_report, confusion_matrix
import matplotlib.pyplot as plt
import seaborn as sns
import tensorflow as tf
```

---

## Future Improvements

- Real-time accident prediction
- Integration with live aviation datasets
- Streamlit or Flask deployment
- Advanced deep learning architectures
- Predictive maintenance analysis

---

## Author

Blessy Mariya  
