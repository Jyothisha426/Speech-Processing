# Speech Emotion Recognition (SER) using Deep Learning


## 📌 Overview
A **deep learning model** that classifies human emotions from speech signals using **Convolutional Neural Networks (CNN)** and **MFCC features**.  
- **Datasets Used**: [RAVDESS](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio/data), [TESS](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess)  
- **Key Features**:  
  - Audio preprocessing (noise removal, normalization).  
  - Feature extraction (MFCCs, Chroma STFT, Mel Spectrogram).  
  - CNN-based emotion classification.

## File Structure:
Speech-Processing/
├── SER_Model.ipynb       # Main Jupyter Notebook
├── SpeechProcessingReport.pdf  # Project report

## Tools & Technologies
- Python Libraries: Librosa, TensorFlow/Keras, Scikit-learn, Pandas.
- Data Augmentation: Noise addition, time-stretching, pitch-shifting.
- Model Architecture: CNN with [specify layers, e.g., Conv2D, MaxPooling].

## Run the Jupyter Notebook
  ```
    jupyter notebook SER_Model.ipynb
  ```
