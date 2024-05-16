# Environmental Sound Classification with Deep Learning

## Overview
This project explores the classification of environmental sounds using advanced deep learning techniques. The study utilizes the ESC-50 dataset to compare the efficacy of Mel spectrograms and raw audio waveforms in model training, enhanced by a variety of data augmentation strategies.

## Key Findings
- **Data Augmentation Impact**: Data augmentation significantly improves model accuracy and robustness. Techniques like pitch shifting, time stretching, and noise addition were particularly effective.
- **Model Performance**: Different neural network architectures were compared, with convolutional neural networks (CNNs) optimized for Mel spectrogram inputs showing the best results. The study highlights the role of advanced architectures in achieving higher classification accuracy.
- **Challenges Addressed**: The project tackles common issues in sound classification such as class imbalance and feature extraction nuances, offering solutions that enhance classification accuracy.

## Technologies Used
- **Python** for all preprocessing and model training.
- **Librosa** library for audio signal processing.
- **Keras** and **TensorFlow** for building and training deep learning models.

## Models Explored
- CNN architectures tailored for both Mel spectrograms and raw audio waveforms.
- AclNet SC model noted for its robust performance on raw waveform input.

## Conclusions
The study confirms the potential of deep learning in accurately classifying environmental sounds, contributing valuable insights into sound classification systems and suggesting directions for future research in audio analysis.

## How to Use This Repository
- Clone the repository to get started.
- Install the required Python packages using `pip install -r requirements.txt`.
- Explore the notebooks to see the data augmentation processes and model training steps.

## Future Work
Further exploration into unsupervised learning models and real-time classification systems could expand the capabilities and applications of environmental sound classification.
