🎤 Speaker Recognition using CNN and MFCC
📌 Overview

This project implements a speaker recognition system using Convolutional Neural Networks (CNNs) and Mel-Frequency Cepstral Coefficients (MFCCs) for feature extraction. The dataset consists of audio recordings from five different speakers, with each speaker having 1500 clips of 1 second each.
📂 Dataset

    Source: Kaggle - Speaker Recognition Dataset
    Format: 16000 Hz PCM WAV files
    Structure: Audio files are stored in separate folders for each speaker.

    dataset/
    ├── speaker_1/
    │   ├── clip_001.wav
    │   ├── clip_002.wav
    │   └── ...
    ├── speaker_2/
    ├── speaker_3/
    ├── speaker_4/
    ├── speaker_5/

⚙️ Features

    MFCC Extraction: Converts audio signals into meaningful features.
    CNN Model: Classifies speakers based on extracted MFCC features.
    Train/Test Split: Data is split into training and testing sets.
    Performance Metrics: Accuracy, precision, recall, and loss visualization.

🛠 Installation & Setup
Prerequisites

Make sure you have Python and the required dependencies installed.

pip install numpy pandas librosa tensorflow matplotlib scikit-learn

Clone the Repository

git clone https://github.com/yourusername/speaker-recognition.git
cd speaker-recognition

🚀 Usage

    Extract MFCC Features
    Run the feature extraction script to generate MFCCs:

python mfcc_extraction.py

Train the CNN Model

python train_model.py

Test the Model

python test_model.py

Evaluate Performance

    python evaluate.py

📊 Model Performance

    Accuracy: XX% (to be updated after training)
    Loss and Accuracy Graphs: (Generated in the results folder)

📜 Project Structure

├── dataset/              # Audio dataset
├── mfcc_extraction.py    # MFCC feature extraction
├── train_model.py        # CNN model training
├── test_model.py         # Model testing
├── evaluate.py           # Model evaluation
├── models/               # Saved models
├── results/              # Graphs and performance metrics
└── README.md             # Project documentation

🎯 Future Improvements

    Support for more speakers
    Implementing LSTM for temporal feature learning
    Optimizing CNN architecture for better accuracy
    Real-time speaker recognition
