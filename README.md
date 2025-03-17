# ENHANCE SEIZURE DETECTION USING DEEP LEARNING MODELS
## Overview
This repository contains the implementation of a deep learning-based seizure detection model, designed to be integrated into wearable devices. By leveraging multimodal sensor data, our approach enhances seizure recognition accuracy, ultimately improving patient care and intervention strategies.
## Table of Contents 
- [Dataset overview](#Dataset)
- [Usage](#Usage)
- [Installation](#Installation)
  
## Dataset Overiew
The dataset used in this project consists of sensor readings from wearable devices, capturing:
  - **Electrodermal Activity (EDA):** Measures skin conductance to detect stress and autonomic responses.
  - **Accelerometer (ACC):** Captures movement patterns to identify seizure-related tremors.
  - **Heart Rate (HR):** Monitors fluctuations that may indicate seizure onset.
  - **Blood Volume Pulse (BVP):** Tracks changes in blood circulation.
  - **EEG Readings (if available):** Provides direct brain activity insights.
  
To improve detection accuracy, we preprocess the dataset by removing unnecessary features and splitting it into training and validation sets.

## Usage
This project has a wide range of applications across different fields:

  #### 1. Healthcare & Patient Monitoring
  - Personal Use: Individuals with epilepsy can use it for continuous monitoring and seizure prediction.
  - Hospital & Clinical Settings: Can be integrated into hospital monitoring systems to assist doctors in real-time seizure detection.
  #### 2. Emergency Response & Caregiver Support
  - Alerts caregivers, family members, and emergency responders immediately upon detecting a seizure, ensuring timely intervention.
  #### 3. Wearable Technology & IoT Devices
  - Can be integrated into smartwatches, fitness trackers, and medical wearables to enhance real-time health monitoring.
  #### 4. AI-Powered Research & Development
  - Researchers and healthcare professionals can use the system to analyze seizure patterns and improve epilepsy treatment strategies.
  ##### 5. Telemedicine & Remote Healthcare
  - Can be used in telehealth applications to provide remote monitoring solutions for epilepsy patients, reducing the need for hospital visits.

## Installation

#### Clone the repository:
    git clone https://github.com/rishi7736/Minor-Project-2.git
    cd Minor-Project-2

#### Install dependencies:
    pip install -r requirements.txt

#### Run the script:
    python mp-final.ipynb
