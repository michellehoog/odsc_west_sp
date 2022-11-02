# ODSC West 2022: Signal Processing Workshop

This repo contains the slides and notebook for the ODSC West 2022 presentation, "Separating the signal from the noise: Signal processing and feature extraction techniques for biological data".

## Introduction
Your model is only as good as the data that goes into it, so removing the maximum amount of noise while retaining signal is vital. This talk will introduce basic time and frequency domain signal processing techniques and methods to identify and deal with motion artefacts. The session will take you through practical examples that you can apply straight away to your biological data. You’ll learn when to apply which techniques and how to evaluate the outcome. I will also make recommendations for data collection to consider when designing a sensor so that you can get the best possible data (because prevention is better than treatment!). Those interested in machine learning and signal analysis for biomedical processing, electrical and optical signals, and wearables technology will enjoy this talk!

## In this repo
The linked [Google Colab Notebook](https://colab.research.google.com/drive/12GTHacYHUfVU8g7c_5Srf2uA2xujRiUj?usp=sharing) uses real-life PPG data from the PPG-DaLiA dataset (https://archive.ics.uci.edu/ml/datasets/PPG-DaLiA) as an example for exploring different signal processing techniques.

The notebook and slides are also in this repo so that you can use the resources locally.

## Data

### Source 
Attila Reiss, Ina Indlekofer, Philip Schmidt, and Kristof Van Laerhoven. 2019. Deep PPG: Large-scale Heart Rate Estimation with Convolutional Neural Networks. MDPI Sensors, 19(14).

### Data Set Information

PPG-DaLiA is a publicly available dataset for PPG-based heart rate estimation. This multimodal dataset features physiological and motion data, recorded from both a wrist- and a chest-worn device, of 15 subjects while performing a wide range of activities under close to real-life conditions. The included ECG data provides heart rate ground truth. The included PPG- and 3D-accelerometer data can be used for heart rate estimation, while compensating for motion artefacts. Details can be found in the dataset's readme-file, as well as in the article above.

This repo explores the synchronized ECG and blood volume pulse data (BVP, 64 Hz). BVP was recorded using an Empatic E4 wrist-worn device during different activities such as sitting, walking and driving. 

The dataset's readme-file on [UCI's Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/PPG-DaLiA) contains further details on the dataset structure, data format and study protocol.

