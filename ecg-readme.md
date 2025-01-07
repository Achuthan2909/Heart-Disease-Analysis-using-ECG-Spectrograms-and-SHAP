# ECG Arrhythmia Classification with XAI

This project focuses on ECG arrhythmia classification using STFT-based spectrograms and Convolutional Neural Networks (CNN), combined with Explainable Artificial Intelligence (XAI) techniques. The implementation is based on the research paper "ECG Arrhythmia Classification Using STFT-Based Spectrogram and Convolutional Neural Network" by Jingshan Huang, Binqiang Chen, Bin Yao, and Wangpeng He.

## Research Foundation

This project is based on the paper:
**"ECG Arrhythmia Classification Using STFT-Based Spectrogram and Convolutional Neural Network"**
- Authors: Jingshan Huang, Binqiang Chen, Bin Yao, and Wangpeng He
- Institutions: Xiamen University and Xidian University
- Funding: Supported by the National Natural Science Foundation of China and related provincial science foundations

## Key Features and Components

### ECG Signal Classification Using CNN and STFT-Based Spectrograms
- Short-Time Fourier Transform (STFT) for time-frequency analysis of ECG signals
- Convolutional Neural Network (CNN) architecture optimized for spectrogram image inputs
- Classification system for common arrhythmia types
- SHapley Additive exPlanations (SHAP) analysis for model interpretability
- Feature importance visualization highlighting classification-influencing factors

## Installation and Dependencies

The following dependencies are required to run the provided code:
- Python 3.x
- NumPy
- SciPy
- TensorFlow or PyTorch (depending on implementation)
- Librosa (for audio processing)
- Matplotlib (for visualization)
- SHAP (for explainability)

## Project Structure

The project combines signal processing techniques with deep learning approaches to achieve accurate ECG arrhythmia classification while maintaining model interpretability through XAI methods.
