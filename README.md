# Exoplanet-Detection-using-ML
🪐 Exoplanet Detection from Kepler Light Curves using Machine Learning

Detecting planets beyond our solar system is one of the most fascinating challenges in modern astronomy. This project applies machine learning to classify whether a dip in a star's brightness indicates a transiting exoplanet or is just noise or a false positive.

---

## 🌌 Overview

Astronomers use the **transit method** to detect exoplanets by observing dips in a star’s light when a planet passes in front of it. These **light curves**, captured by telescopes like **Kepler**, are analyzed to determine whether a planet is present.

In this project:
- We use **time-series classification models** (Random Forest, CNN, LSTM) to analyze light curves
- Start with clean, labeled data from **Kaggle’s Kepler dataset**
- Extend to raw NASA data (FITS files) for more realistic detection
- Optionally deploy a **Streamlit app** to visualize and classify uploaded light curves

---

## 🔍 Goals

- Build a clean pipeline to detect exoplanets using supervised learning
- Compare baseline models (Random Forest, Logistic Regression) with deep learning (1D CNN, LSTM)
- Visualize model predictions and light curve behavior
- Extend to raw telescope data (NASA TESS/Kepler Archive)
- Optionally deploy as a web app for real-time planet classification
