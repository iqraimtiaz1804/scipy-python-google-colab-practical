# SciPy Library — Complete Practical in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iqraimtiaz1804/scipy-python-google-colab-practical/blob/main/SciPy_Complete_Practical.ipynb)

> Replace `YOUR_USERNAME` in the badge link above with your GitHub username.

## Introduction

SciPy (*Scientific Python*) is an open-source Python library for scientific and technical computing. It is built on top of NumPy and provides ready-made tools for clustering, constants, Fourier transforms, interpolation, linear algebra and image processing.

This repository contains a beginner-friendly Google Colab notebook that demonstrates six SciPy subpackages with small, reproducible examples. No external files, datasets, API keys or paid services are needed.

## Objectives

- Understand what SciPy is and how it differs from NumPy.
- Learn to set up and run SciPy code in Google Colab.
- Practise six SciPy subpackages with simple, working examples.
- Read, verify and explain the outputs and graphs.
- Present the work clearly in a classroom.

## Technologies Used

| Tool | Purpose |
|---|---|
| Python 3 | Programming language |
| SciPy | Scientific computing tools |
| NumPy | Arrays and basic maths |
| Matplotlib | Graphs and image display |
| Google Colab | Cloud notebook environment |

## SciPy Subpackages Covered

| Subpackage | Topic | Example in the notebook |
|---|---|---|
| `scipy.cluster` | Grouping similar data | K-Means grouping of 10 students (`whiten`, `kmeans`, `vq`) |
| `scipy.constants` | Scientific constants | Distance travelled by light; energy using E = mc² |
| `scipy.fftpack` | Frequency analysis | FFT of a 5 Hz + 12 Hz signal (`fft`, `fftfreq`, `ifft`) |
| `scipy.interpolate` | Estimating missing values | Missing temperature at hour 5 (`interp1d`, `CubicSpline`) |
| `scipy.linalg` | Matrices and equations | `det`, `inv`, `solve`, `eig` on a 2×2 system |
| `scipy.ndimage` | Image processing | Gaussian blur, rotation and Sobel edges (`gaussian_filter`, `rotate`, `sobel`) |

Notes: `scipy.fft` is the modern recommended FFT interface; `scipy.fftpack` is used here because it is part of the course requirement. `interp1d` is a legacy interface used for learning; `CubicSpline` is the modern alternative.

## How to Run the Notebook

**Option 1 — Open directly in Colab**
1. Click the **Open In Colab** badge at the top of this file.
2. Click **Runtime → Run all**.

**Option 2 — Upload manually**
1. Download `SciPy_Complete_Practical.ipynb` from this repository.
2. Go to <https://colab.research.google.com>, choose **File → Upload notebook**, and select the file.
3. Click **Runtime → Run all**.

SciPy, NumPy and Matplotlib are already installed in Google Colab. If SciPy is ever missing, run `%pip install scipy` in a code cell.

## Example Outputs

These values are produced by the notebook's code (and can be checked by hand):

| Module | Result printed by the notebook |
|---|---|
| Cluster | 3 groups of students with centroids (hours, marks) ≈ (1.50, 39.00), (4.50, 62.33) and (8.75, 90.00) |
| Constants | Light travels 17,987,547,480 m in 60 s; 1 kg of mass has E = 8.987552 × 10¹⁶ J |
| FFTPACK | Spectrum peaks at 5.0 Hz (amplitude 1.00) and 12.0 Hz (amplitude 0.50) |
| Interpolate | Temperature at hour 5: 22.50 °C (linear) and 23.05 °C (cubic spline) |
| Linalg | Determinant = 5; solution of 2x + y = 5 and x + 3y = 6 is x = 1.8, y = 1.4 |
| NDIMAGE | 64×64 image blurred, rotated by 30° and edge-detected; total brightness unchanged by blur (638.4) |

The notebook also draws five graphs (clusters, signal and spectrum, interpolation curves, equation lines, image panels). Open the notebook to view them.

## Conclusion

This practical shows that SciPy, together with NumPy and Matplotlib, can solve many scientific and engineering tasks with only a few lines of code. Learning these six subpackages gives a strong foundation for Software Engineering, AI and Data Science work.

## Author
    IQRA IMTIAZ
    LCWU-BSSE-7th sem
    
