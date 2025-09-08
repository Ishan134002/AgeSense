# AgeSense

**Real-time Age Prediction from Facial Images**  
A machine learning–based system that predicts a person’s age from facial images using **OpenCV**, **scikit-learn**, **NumPy**, and **Pandas**, trained on over 20K samples with ~80% real-time accuracy.

---

##  Table of Contents

- [Introduction](#introduction)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Model Training & Performance](#model-training--performance)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

## Introduction

AgeSense is designed to detect facial features and predict a person’s age in real time. It uses traditional computer vision and machine learning techniques for quick, lightweight inference—no deep learning frameworks required.

---

## Features

- Detects facial features using **OpenCV**
- Predicts age with **scikit-learn** model
- Handles input images and webcam feed in real time
- ~80% accuracy based on evaluation over 20K+ samples
- Lightweight dependencies, easy to configure and deploy

---

## Tech Stack

- **Python** (3.6+ recommended)  
- **OpenCV-Python** – image capture & face detection  
- **scikit-learn** – age prediction model  
- **NumPy**, **Pandas** – data processing  
- Optionally: **Matplotlib** for visualization

---

## Prerequisites

- Python 3.6 or above  
- pip (or virtual environment tool)  
- Webcam (for real-time camera mode)  

---

## Installation

```bash
git clone https://github.com/Ishan134002/AgeSense.git
cd AgeSense
pip install -r requirements.txt
