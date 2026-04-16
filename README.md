EEG-Based Schizophrenia Detection using CNN

Deep learning project that uses Convolutional Neural Networks (CNN) to analyze EEG signals and classify subjects as healthy or affected by schizophrenia.

 Overview

Schizophrenia is a serious mental disorder that affects thinking, perception, and behavior. EEG (Electroencephalogram) signals provide insights into brain activity and can help detect neurological abnormalities.

This project builds a CNN-based model to automatically learn patterns from EEG data and classify whether a subject has schizophrenia or not.

 Dataset
EEG recordings from 80+ subjects
Includes:
Healthy individuals
Schizophrenia patients
Multiple experimental conditions:
Button press with tone
Passive listening
Button press without tone
Focus on brain response patterns like N100 waveform

 Workflow
1. Data Preprocessing
Loading EEG signal data
Cleaning and normalization
Label encoding (0 = Healthy, 1 = Schizophrenia)
Signal reshaping for CNN input
Averaging signals to reduce noise
2. Model Building
Convolutional Neural Network (CNN)
Extracts spatial & temporal features from EEG data
3. Training & Evaluation
Train-test split
Model training using supervised learning
Performance evaluation using accuracy and loss metrics
4. Experiment Tracking
Integrated with Weights & Biases (W&B)
Tracks:
Training performance
Hyperparameters
Model metrics

 Features
End-to-end EEG classification pipeline
Deep learning-based feature extraction
Noise reduction using averaging
Experiment tracking with W&B
Extendable for other biomedical signal analysis

 Tech Stack
Python
NumPy, Pandas
Matplotlib
Scikit-learn
TensorFlow / Keras
Weights & Biases (W&B)

 Project Structure
├── data/                # EEG dataset (not included / optional)
├── notebooks/           # Jupyter notebooks
├── models/              # Saved models
├── results/             # Output graphs and metrics
├── README.md

How to Run
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook

Future Scope
Improve model accuracy with hyperparameter tuning
Try advanced models (LSTM, Transformers)
Real-time EEG classification
Deploy as a web application

 Objective
To explore how deep learning can assist in early detection of schizophrenia using EEG signals and contribute to AI-based healthcare solutions.
