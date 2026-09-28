# Real-Time Railway Health Management

## 📌 Project Overview

**Real-Time Railway Health Management** is a predictive maintenance system designed to monitor the health of railway assets and estimate their remaining useful life without requiring run-to-failure data.

The system uses **motor current signals**, **Dynamic Time Warping (DTW)**, and **K-Means clustering** to identify fault conditions, measure fault severity, and estimate the remaining useful life of railway assets.

## 🎯 Objectives

* Monitor railway asset health using motor current signals.
* Detect abnormal or faulty conditions.
* Measure the severity of faults.
* Estimate the remaining useful life of an asset.
* Reduce the need for run-to-failure datasets.
* Support condition-based and predictive maintenance.

## 🔄 System Workflow

```text
Motor Current Data
        ↓
Data Preprocessing
        ↓
DTW Similarity Analysis
        ↓
Fault Detection
        ↓
K-Means Clustering
        ↓
Fault Severity Assessment
        ↓
Lifetime Estimation
        ↓
Visualization
```

## 🧠 Methodology

### 1. Data Preprocessing

The input motor current data is collected and processed before analysis. Preprocessing helps prepare the signal data for further analysis.

### 2. Dynamic Time Warping (DTW)

DTW is used to measure the similarity between current signal sequences. It can compare sequences even when they have different lengths or speeds.

### 3. Fault Detection

The DTW similarity analysis is used to identify differences between normal and faulty operating conditions.

### 4. K-Means Clustering

K-Means clustering is used to divide the data into different health or fault-severity levels. The project uses four clusters to represent different severity conditions.

### 5. Lifetime Estimation

The time differences between severity levels are used to estimate the available remaining life of the railway asset. When the estimated lifetime approaches the critical severity level, maintenance or replacement can be considered.

## 🧩 Main Modules

* Dataset Upload
* Data Preprocessing
* Live/Historical Current Signal Acquisition
* DTW Similarity Analysis
* Fault Detection
* K-Means Clustering
* Lifetime Estimation
* Optimized K-Means Tuning
* Performance Evaluation
* Visualization
* Tkinter GUI

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TensorFlow
* Keras
* h5py
* Tkinter
* Dynamic Time Warping (DTW)
* K-Means Clustering

## 📋 Requirements

* Python 3.7 or above
* VS Code or Jupyter Notebook
* Required Python libraries

## ⭐ Key Features

* Does not require run-to-failure datasets.
* Uses motor current signals for health monitoring.
* Detects fault conditions.
* Determines fault severity using clustering.
* Estimates remaining useful life.
* Provides visualization of analysis results.
* Supports real-time feedback.
* Can be adapted for railway electromechanical assets.

## 📊 Expected Outcome

The system provides information about the current health condition of a railway asset and estimates its remaining useful life. This can support predictive and condition-based maintenance and help reduce unnecessary maintenance activities.

## 📄 Project Report

The complete project report is available in this repository:

**G8 BH (1).pdf**

## 👥 Project Team

* **Nomula Srivalli**
* **Repani Pavan Kumar**
* **Md. Ibrahim Ali Sharfi**
* **B. Raghavendra**

## 📌 Project Type

**Academic Mini Project – Predictive Maintenance / Machine Learning**

## 🔑 Keywords

`Predictive Maintenance` `Railway Health Monitoring` `DTW` `K-Means` `Machine Learning` `Fault Detection` `Remaining Useful Life` `Motor Current Signals`

