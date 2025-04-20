"# GIT-Group-9: Signal Visualization Project" 

## Overview

This repository contains our complete group submission for the **Assignment 1** of the **Graphics and Interactive Techniques 1** module, exploring signal types and their visualization across 1D, 2D, and 3D domains. 

The implementation is based on Python, using notebooks and interactive visualizations. Each section addresses the respective analytical questions from the assignment and includes well-documented code and structured markdowns.

Collaborators: Safae Hajjout & Yahya Mansoub, 1st year engineering cycle students at the **College of Computing**.

## Project Structure

```
├── 1D/
│   ├── ecg_signal_visualization.ipynb
│   └── requirements.txt
├── 2D/
│   ├── gifs/
│   ├── image_sequence_visualization.ipynb
│   └── requirements.txt
├── 3D/
│   ├── data/
│   ├── motion_capture_visualization.ipynb
│   └── requirements.txt
├── .gitignore
└── README.md
```

## Features

Each notebook tackles visualization through a different dimension of signal data:

### **🔹 1D — ECG Signal Visualization**

    Time and frequency-domain exploration using the ECG5000 dataset

    FFT, PSD, and spectrograms

    Signal normalization, clustering, and class-wise comparisons

### **🔹 2D — Image Data Exploration**

    MNIST and COIL-20 datasets

    GIF creation for rotating image effects

    Dimensionality reduction with PCA, t-SNE, UMAP

    RNX curves, k-means, and k-NN analysis

### **🔹 3D — Motion Capture Dashboard**

    CMU Mocap data (Subjects 1 & 2, Trials 1 & 4)

    Skeleton movement synced with original video and time series

    Interactive dashboard with synchronized playback

## Installation

We recommend setting up different python environments for each part so as to avoid any dependency issues.

You can install all dependencies directly by executing the following command:
```bash
pip install -r 1D/requirements.txt -r 2D/requirements.txt -r 3D/requirements.txt
```



