# 📡 Digital Predistortion (DPD) for Power Amplifier Linearization

## 🎓 B.Tech Final Year Project

This repository presents the implementation of a **Digital Predistortion (DPD) system** for **Power Amplifier (PA) linearization**, aimed at improving signal integrity and reducing nonlinear distortion in RF communication systems.

The project is developed using Python and executed on Google Colab, leveraging data-driven modeling techniques to simulate and compensate for PA nonlinearities.

---

## 🚀 Project Overview

Power Amplifiers (PAs) are inherently nonlinear devices, especially when operated near saturation for efficiency. This nonlinearity introduces spectral regrowth and signal distortion.

To address this, **Digital Predistortion (DPD)** is used to pre-distort the input signal such that the combined response of DPD + PA becomes linear.

This project implements:

* Data extraction and preprocessing
* PA modeling
* DPD training
* Output linearization through gain control

---

## 🧩 Project Workflow

### 1️⃣ Data Extraction

Raw signal data is extracted and preprocessed from `.txt` files.

🔗 Colab Notebook:
[https://colab.research.google.com/drive/1qAS8-KAFbsDIjEKkUVEVWuc5LAhA6w2C?usp=sharing](https://colab.research.google.com/drive/1qAS8-KAFbsDIjEKkUVEVWuc5LAhA6w2C?usp=sharing)

**Key Tasks:**

* Reading raw I/Q data
* Cleaning and structuring dataset
* Preparing training-ready inputs

---

### 2️⃣ PA Modeling & DPD Training

This stage involves building a behavioral model of the Power Amplifier and training a Digital Predistortion model.

🔗 Colab Notebook:
[https://colab.research.google.com/drive/1h3uCEYmt5YHsOnolWoAsLetvYucv-8E-?usp=sharing](https://colab.research.google.com/drive/1h3uCEYmt5YHsOnolWoAsLetvYucv-8E-?usp=sharing)

**Key Tasks:**

* Modeling PA nonlinearity
* Training DPD using machine learning techniques
* Evaluating model performance

---

### 3️⃣ Output Linearization (Gain Control)

After training, the system evaluates linearization performance by varying gain and analyzing output characteristics.

🔗 Colab Notebook:
[https://colab.research.google.com/drive/1YzybUXr95v0E-4eAOfNvm66kEoJykme-?usp=sharing](https://colab.research.google.com/drive/1YzybUXr95v0E-4eAOfNvm66kEoJykme-?usp=sharing)

**Key Tasks:**

* Applying trained DPD
* Adjusting gain parameters
* Observing linearization effects

---

## 📊 Results

* Reduction in nonlinear distortion
* Improved spectral efficiency
* Enhanced signal linearity

(Refer to the attached report for detailed graphs and analysis.)

---

## 🛠️ Technologies Used

* Python
* Google Colab
* NumPy
* SciPy
* Matplotlib
* Machine Learning Models

---

## 📁 Repository Structure

```
├── data/
│   └── raw_txt_files
├── notebooks/
│   ├── data_extraction.ipynb
│   ├── dpd_training.ipynb
│   └── linearization.ipynb
├── results/
├── report/
│   └── final_report.pdf
└── README.md
```

---

## 📄 Report

A detailed project report is included in this repository covering:

* Theoretical background
* Mathematical modeling
* Implementation details
* Results and analysis

---

## 📌 Key Concepts

* Digital Predistortion (DPD)
* Power Amplifier Nonlinearity
* Behavioral Modeling
* RF Signal Processing

---

## 🧠 Future Work

* Implementation on hardware (FPGA/SDR)
* Real-time DPD adaptation
* Advanced neural network architectures

---

## 🤝 Acknowledgment

This project was completed as part of the B.Tech program in Electronics and Communication Engineering.

---

## ⭐ How to Use

1. Clone the repository
2. Open the Colab notebooks
3. Run each step sequentially
4. Analyze the results

---

## 📬 Contact

For any queries or collaboration, feel free to reach out.

---

⭐ If you find this project useful, consider giving it a star!
