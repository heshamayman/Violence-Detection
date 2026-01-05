# Violence Detection Mobile App
## Overview

This project is a mobile application for detecting acts of violence in live streams and uploaded videos.
It aims to help government institutions, schools, and parents in Egypt identify violent behavior early and take appropriate action.

The system combines deep learning models with a mobile-friendly deployment to enable fast and efficient violence detection, even on low-end devices.

## Tech Stack
- **Mobile:** Flutter, Dart

- **Backend:** Python, FastAPI

- **Deep Learning:** TensorFlow

- **Development & Training:** Google Colab

## Key Features

- Detects violent activities in live video streams and uploaded videos

- Mobile application with simple and user-friendly interface

- Backend API for model inference and communication

- Optimized for real-time and time-sensitive applications

## Model & Approach

- Implemented SepConvLSTM, a compact and efficient alternative to ConvLSTM, enabling effective spatiotemporal feature learning with fewer parameters

- Trained and evaluated models using the RWF-2000 surveillance dataset

- Experimented with multiple architectures:

  - SepConvLSTM

  - 3D CNN (3DCNN)

  - C3D for action recognition

  - Transformer encoders with multi-head self-attention for sequential video data

The SepConvLSTM model achieved strong performance while remaining computationally efficient, making it suitable for real-world deployment.

## Data Analysis & Experiments

- Analyzed and categorized violence samples from the RWF-2000 dataset

- Extracted feature vectors using a trained 3DCNN

- Applied dimensionality reduction techniques:

  - t-SNE

  - UMAP

- Performed clustering using:

  - K-Means

  - DBSCAN

The clustering results did not align clearly with predefined violence categories, highlighting the complexity of real-world violent behavior.

## Use Case

- Early detection of violence in schools and public institutions

- Supporting authorities and parents in taking preventive actions

- Real-time monitoring in surveillance systems

## Future Improvements

- Improve model accuracy on real-world noisy footage

- Expand dataset with more diverse violence scenarios

- Optimize backend for lower latency on mobile devices

## Why This Project Matters

Violence detection is a critical real-world problem, especially in educational and public environments.
This project demonstrates the application of modern deep learning techniques in a practical, mobile-first solution.

<img width="214" height="467" alt="image" src="https://github.com/user-attachments/assets/506f69cc-a96c-4542-b955-e8fc5d47f7c0" />

<img width="213" height="464" alt="image" src="https://github.com/user-attachments/assets/1aedad11-fbbf-457b-9459-b660020f6732" />

<img width="223" height="433" alt="image" src="https://github.com/user-attachments/assets/ab927710-f824-423e-989b-e84a98ce6729" />

<img width="235" height="401" alt="image" src="https://github.com/user-attachments/assets/4b19c754-1fa5-4276-a6b8-3809451a63d3" />

<img width="217" height="421" alt="image" src="https://github.com/user-attachments/assets/b6aa47d0-6c78-410c-9962-de9c75525fdd" />

<img width="216" height="432" alt="image" src="https://github.com/user-attachments/assets/1108cdcf-d741-4ce0-9be2-9b51ced1de72" />

<img width="211" height="428" alt="image" src="https://github.com/user-attachments/assets/592891fb-ac72-4f19-8865-1bf58dac8eb7" />






