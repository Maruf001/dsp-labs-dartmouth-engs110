# Digital Signal Processing Lab Series

This repository contains a comprehensive set of Jupyter notebooks developed as part of a digital signal processing (DSP) course. The labs are designed to build hands-on experience with Python tools and concepts fundamental to the analysis, synthesis, and manipulation of discrete-time signals.

## 📁 Repository Structure

Each notebook focuses on a specific signal processing concept or toolset. The labs are designed to progressively build your understanding of core DSP topics, from signal generation to spectral analysis.

---

### 🧰 Python Setup and Fundamentals
Covers the basics of working in a Jupyter environment, installing required packages, and reviewing core Python functionalities relevant to signal processing workflows.

---

### 🎲 Random Signal Generation
Focuses on the creation and analysis of random signals. Demonstrates custom random number generators and introduces signal properties like mean, variance, and correlation.

---

### ⏱️ Sampling and Reconstruction
Explores the principles of signal sampling, aliasing, and ideal reconstruction. Visual and numerical examples illustrate how improper sampling affects signal integrity.


---

### 🔁 Frequency Response and Moving Average Filter
Introduces linear time-invariant (LTI) systems, frequency response analysis, and simple filtering using moving average techniques.


---

### 🧮 IIR Filter Design
Discusses Infinite Impulse Response (IIR) filter structures, their frequency responses, and how to implement and analyze Butterworth and Chebyshev filters in Python.

---

### 🔳 FIR Filter Design with Windows
Focuses on Finite Impulse Response (FIR) filter design using windowing techniques. Includes window types (e.g., Hamming, Blackman) and their effects on filter performance.

---

### 🔄 Filter Structures and Quantization
Examines practical issues in digital filter implementation such as cascade and parallel structures, as well as the effects of finite precision and quantization errors.

---

### 🔬 Discrete Fourier Transform (DFT)
Covers the theoretical foundation and implementation of the DFT. Demonstrates signal decomposition and frequency-domain interpretation using FFT tools.


---

### 📊 Spectral Analysis and Time Windowing
Final module on spectral estimation, demonstrating how windowing affects frequency resolution and leakage. Includes comparisons of different window types and spectral plots for compound signals.


---

## ⚙️ Requirements
- Python 3.x  
- `numpy`, `scipy`, `matplotlib`, `ipython`, `jupyter`, `scikit-dsp-comm`, etc.

To install all dependencies:
```bash
pip install -r requirements.txt
```

---

## 📚 License
This project is for educational use only. All rights reserved by the original authors or instructors unless stated otherwise.
