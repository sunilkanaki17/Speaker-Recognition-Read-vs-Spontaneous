# Speaker Recognition: Read vs Spontaneous

This project implements a speaker recognition system using deep learning techniques, specifically comparing the performance of SincNet and standard CNN architectures under different speech styles: read and spontaneous.

## Project Structure

- `code/`: Contains the implementation codes.
- `results/`: Contains images and plots used in the project.
- `README.md`: Project documentation.

## Description

### 1. Introduction
Speaker recognition helps determine who is speaking by using the speaker’s unique voice characteristics. This project aims to compare the accuracy of speaker recognition using SincNet and CNN architectures.

### 2. Dataset
The dataset is taken from IITG-MV which contains multilingual audio files of 100 speakers. It includes both read and spontaneous speech samples.

### 3. Methodology
- **Data Preprocessing**: Cleaning and transforming raw data.
- **Feature Extraction**: Using SincNet and CNN layers to extract features.
- **Training and Validation**: Training the model and validating its performance.

### 4. Results
The results indicate that SincNet outperforms standard CNN in terms of accuracy for speaker recognition tasks.

### 5. Conclusion
The proposed SincNet model provides a robust and reliable solution for speaker recognition, particularly in diverse linguistic contexts.

