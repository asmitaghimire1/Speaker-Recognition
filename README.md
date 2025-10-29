# Speaker Recognition using CNN and MFCC  

### Overview

This project implements a speaker recognition system using Convolutional Neural Networks (CNNs) and Mel-Frequency Cepstral Coefficients (MFCCs) for feature extraction. The dataset consists of audio recordings from five different speakers, with each speaker having 1500 clips of 1 second each.

### Dataset

- Source: Kaggle - Speaker Recognition Dataset
- Format: 16000 Hz PCM WAV files
- Structure: Audio files are stored in separate folders for each speaker.

        dataset/
        ├── speaker_1/
        │   ├── clip_001.wav
        │   ├── clip_002.wav
        │   └── ...
        ├── speaker_2/
        ├── speaker_3/
        ├── speaker_4/
        ├── speaker_5/

### Features

- MFCC Extraction: Converts audio signals into meaningful features.
- CNN Model: Classifies speakers based on extracted MFCC features.
- Train/Test Split: Data is split into training and testing sets.
- Performance Metrics: Accuracy, precision, recall, and loss visualization.

### Model Performance
Loss and Accuracy graphs:  

<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/ba039b6a-eccd-473c-93b5-b352896eb658" /> 

Classification Report and Confusion Matrix:

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/3dc7b7b4-c248-4107-88e9-cd4d016abd7c" />


### Future Improvements

- Support for more speakers
- Implementing LSTM for temporal feature learning
- Optimizing CNN architecture for better accuracy
- Real-time speaker recognition
