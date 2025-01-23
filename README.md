# RUL-Forecasting
This project is for classifying the Remaining Useful Life (RUL) Time of bearing 
## Process Overview

1. **Data Collection**
   - Acquire vibration signals from bearings and label them with Remaining Useful Life (RUL).

2. **Data Preprocessing**
   - Segment the time-series data into smaller windows.
   - Normalize the signals.

3. **Signal Conversion**
   - Extract features using methods like Short Time Fourier Transform (STFT) or wavelet transform.
   - Convert extracted features into images in this work simple plot creation is used.

4. **Dataset Preparation**
   - Split the dataset into training, validation, and test sets.
   - Apply data augmentation to enhance image diversity.

5. **Transfer Learning**
   - Select a pre-trained CNN model (Exception network).
   - Modify the output layer for RUL classification.

6. **Model Training**
   - Train the modified CNN on the image dataset, utilizing transfer learning techniques.
7. **Evaluation Results**
     ![image](https://github.com/user-attachments/assets/170131b3-2a26-456b-a032-dce5eb058f2b)
     ![image](https://github.com/user-attachments/assets/c1759fca-0025-4797-bd6d-0fa70ba0170f)


7. **Model Evaluation**
   - Assess model performance using accuracy, precision, recall, and other metrics.

8. **Deployment**
   - Integrate the model into operational settings for real-time RUL predictions, with a feedback loop for continuous improvement.
