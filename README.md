# Digital Signal Processing Lab Series

This repository contains a collection of Jupyter notebooks for my digital signal processing (DSP) lab sequence in calls ENGS110. The goal of the course was to build intuition and implementation skills across a range of core DSP topics using Python, NumPy, SciPy, and other open-source tools. Each notebook represents a stand-alone topic with practical examples and visualizations to reinforce signal processing theory through hands-on coding.

---

### 1. Python Setup and Environment Configuration

Introduces the Jupyter Notebook interface and essential Python packages used throughout the lab series. This notebook ensures the development environment is fully equipped for scientific computing, including instructions for package management and custom function integration for DSP workflows.

---

### 2. Random Signal Generation and Statistical Analysis

Demonstrates how to generate pseudo-random discrete-time signals and explores their statistical properties such as mean, variance, and autocorrelation. Highlights practical use cases of random signals in system testing and noise modeling. Includes custom implementation of uniform and Gaussian generators.

---

### 3. Sampling Theory and Signal Reconstruction

Covers the fundamentals of sampling continuous-time signals, reconstruction using sinc interpolation, and the critical role of the Nyquist rate. Visualization of aliasing artifacts underscores how under-sampling distorts signal representation in the discrete domain.


---

### 4. Frequency Response and Time-Domain Filtering

Analyzes the behavior of linear time-invariant (LTI) systems through their frequency response. Implements moving average (MA) filters and explores the trade-offs between time-domain smoothing and frequency-domain attenuation. This notebook lays the groundwork for understanding filter design in later modules.


---

### 5. IIR Filter Design and Implementation

Focuses on Infinite Impulse Response (IIR) filters, particularly Butterworth and Chebyshev designs. Walks through filter specification, design via `scipy.signal`, and implementation in both difference equation and transfer function forms. Emphasizes how pole-zero placement influences system dynamics.

---

### 6. FIR Filter Design Using Windowing Techniques

Introduces Finite Impulse Response (FIR) filter design with various window functions (e.g., Hamming, Blackman). Compares ideal versus realizable filters and visualizes how windowing affects frequency resolution and side lobe behavior. Design examples include bandpass and high-pass filters.

---

### 7. Filter Structures and Quantization Effects

Explores different realizations of digital filters, including direct form, cascade, and parallel implementations. Evaluates the numerical impact of finite word length and quantization noise. The notebook also introduces fixed-point arithmetic simulation for embedded system considerations.

---

### 8. Discrete Fourier Transform and Spectral Analysis

Applies the Discrete Fourier Transform (DFT) to analyze the frequency content of signals. Highlights the relationship between time-domain sampling and frequency resolution. Uses FFT algorithms to visualize spectral leakage and the impact of different time-windowing strategies.


---

## 🔧 Requirements

- Python 3.x  
- Core libraries: `numpy`, `scipy`, `matplotlib`, `jupyter`, `scikit-dsp-comm`

To install dependencies:
```bash
pip install -r requirements.txt
```

---

## 📘 License

This work is intended for educational and research purposes. Content builds on publicly available tools and academic materials used in digital signal processing courses.
