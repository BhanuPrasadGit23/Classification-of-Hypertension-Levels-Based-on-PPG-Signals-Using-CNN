This project involves developing a deep learning model using Convolutional Neural Networks (CNN) to classify hypertension levels based on Photoplethysmography (PPG) signals. The system predicts Systolic Blood Pressure (SBP) and Diastolic Blood Pressure (DBP) using a model trained on PPG data and additional patient information, such as age, gender, height, weight, and Body Mass Index (BMI). The CNN architecture consists of multiple convolutional layers, followed by pooling layers and dense layers with softmax activation for class prediction. The model classifies hypertension into four categories: Normal, Pre-Hypertension, Hypertension Stage 1, and Hypertension Stage 2.

The dataset used in this project was acquired from Guilin People's Hospital in 2017. It contains 219 validated patient records, which include information such as subject ID, sex, age, height, weight, Systolic Blood Pressure (SBP), Diastolic Blood Pressure (DBP), heart rate, Body Mass Index (BMI), and hypertension status. Additionally, there are 657 Photoplethysmography (PPG) signal recordings, with each patient having three PPG data recordings.

During training, the model achieved the following performance:

SBP prediction: training loss of 13.8498, mean absolute error (MAE) of 2.9043, validation MAE of 4.25167, and test MAE of 4.96.
DBP prediction: training loss of 3.1329, MAE of 1.3883, validation MAE of 2.68066, and test MAE of 3.00.
For the classification of hypertension levels based on SBP, DBP predictions, and other patient data (sex, height, weight, BMI, age, etc.), the model achieved:

Training accuracy: 0.9879, loss: 0.0607
Validation accuracy: 0.91892
Test accuracy: 0.9067 with a test loss of 0.7507.
