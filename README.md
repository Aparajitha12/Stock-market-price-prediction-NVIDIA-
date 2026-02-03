# Stock Market Price Prediction-NVIDIA

This project presents a deep learning-based approach to forecasting NVIDIA stock prices using Convolutional Neural Networks (CNNs) and Short-Time Fourier Transform (STFT) spectrograms. The model includes embedded logic for buy/sell signal generation, offering insights into long-term market trends. NVIDIA’s historically dynamic price behavior particularly notable around 2016, provides a relevant testbed for evaluating model performance in high-variance financial contexts.

## Repository Contents

- `Nvidia Data.csv`  
  Historical stock price dataset used for training and evaluation.

- `NVIDIA_Stock_Price_Prediction.ipynb`  
  Jupyter Notebook implementing the complete workflow, including:
  - Data preprocessing  
  - Spectrogram generation using STFT  
  - CNN model architecture and training  
  - Prediction visualization and signal generation

## Features

- Spectrogram-based transformation of time series data  
- Custom CNN model for capturing temporal and frequency-domain patterns  
- Integrated decision logic for buy/sell signal overlay  
- Designed for high-volatility datasets like NVIDIA stock

## Setup Instructions

**Dependencies**:  
- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  
- TensorFlow / Keras  


Install dependencies using:

```bash
pip install -r requirements.txt
