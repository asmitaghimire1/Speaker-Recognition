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

📊 Model Performance

    Loss and Accuracy Graphs: 
    ![483331130_2159385587871599_3087932711519065501_n](https://github.com/user-attachments/assets/c0951067-a285-4b84-967b-88375b2c9122)
    ![483156597_1063452739133508_7248400490991682105_n](https://github.com/user-attachments/assets/738f482f-a3b4-4048-9a8b-fc5fd42e9cf2)


🎯 Future Improvements

    Support for more speakers
    Implementing LSTM for temporal feature learning
    Optimizing CNN architecture for better accuracy
    Real-time speaker recognition
