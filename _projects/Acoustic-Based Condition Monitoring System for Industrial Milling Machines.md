---
name: Acoustic-Based Condition Monitoring System for Industrial Milling Machines

tools: [librosa, Tensorflow, Qt, Supervised Learning, Python,  Audio Signal Preprocessing]

image: 

description: Acoustic-based monitoring system was developed to detect tool wear and failutes in industrial milling machines.
---
# Acoustic-Based Condition Monitoring System for Industrial Milling Machines

In this university-industry collaboration project between Sivas Cumhuriyet University and [ESTAŞ](https://www.estas.com.tr), an acoustic-based monitoring system was developed to detect tool wear and failures in industrial milling machines. The system works by analyzing the audio data generated during the cutting process by the asynchronous motor driving the milling tool. These audio signals are processed and classified using a deep learning-based algorithm to detect anomalies and provide real-time feedback through an operator panel. Notably, this project was the first and only TÜBİTAK 2209-B project accepted at Sivas Cumhuriyet University during its funding year.


This system, which I developed to classify the conditions of cutting tools (blunt, broken, burned, idling, rigid/solid) solely based on motor sound data, aims to enable operators to make fast and data-driven decisions during critical processes such as tool replacement, maintenance, or failure intervention on the production line.

The data collection process was carried out by placing microphones on milling machines, capturing raw audio signals from the motors. These signals were transformed from time-domain into meaningful spectral representations by extracting MFCC (Mel-Frequency Cepstral Coefficients) features, making them suitable for classification.

The extracted MFCC features were used to train deep neural network (DNN) models built with Keras. As a result, the system successfully classified the audio signals into five distinct tool condition categories: blunt, broken, burned, idling, and rigid.

![preview](/images/tubitak.png)

For real-world deployment, I developed a PyQt5-based desktop interface that captures real-time audio samples in 60-second intervals and sends them to the classification module. The tool condition, determined through classification, is presented to the operator with instant visual alerts, enabling immediate intervention when necessary.

This project offers an end-to-end integrated system solution with direct application not only in signal processing and machine learning but also in manufacturing technologies, human-machine interaction, and predictive maintenance.
