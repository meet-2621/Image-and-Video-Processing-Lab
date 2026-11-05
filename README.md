# Image and Video Processing Lab

A collection of Python-based practical assignments for **Image and Video Processing**. This repository contains Jupyter notebooks demonstrating fundamental image-processing operations using OpenCV, NumPy, and Matplotlib.

The experiments cover image input/output, image transformations, enhancement, filtering, edge detection, noise generation, denoising, texture analysis, and image segmentation.

## Technologies Used

- **Python**
- **OpenCV** – image and video processing
- **NumPy** – numerical operations and array manipulation
- **Matplotlib** – displaying images and plotting histograms
- **Jupyter Notebook** – running and documenting practical experiments

## Repository Contents

| Notebook | Topics Covered |
|---|---|
| `lab 1.ipynb` | Reading, displaying, writing, and inspecting images; converting color images to grayscale; reading and displaying video |
| `lab2.ipynb` | Grayscale-to-binary conversion using mean and user-defined thresholds; RGB-to-grayscale conversion using average and user-defined channel weights |
| `Lab 3.ipynb` | Adding borders/padding to grayscale and binary images; image complement |
| `Lab 4.ipynb` | Image enhancement using logarithmic transformation, power-law (gamma) transformation, and intensity-level slicing |
| `lab 5.ipynb` | Grayscale and color image histograms; contrast stretching |
| `lab 6.ipynb` | Image smoothing using averaging, weighted, and Gaussian filters |
| `lab 7.ipynb` | Image sharpening using Laplacian and Sobel operators, Canny edge detection, and unsharp masking |
| `lab 8.ipynb` | Generating uniform, Gaussian, Erlang, exponential, and Rayleigh noise; plotting noise histograms |
| `lab 9.ipynb` | Local Binary Pattern (LBP); denoising Gaussian- and speckle-noise-corrupted images using Wiener, median, Gaussian, and bilateral filters |
| `Lab 10.ipynb` | Adaptive median filtering with PSNR comparison; image segmentation using Otsu's global thresholding |

> **Note:** Notebook filenames use the capitalization and spacing shown in the repository.

## Setup and Installation

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Install the required libraries:

```bash
pip install opencv-python numpy matplotlib jupyter
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the notebook you want to run and execute its cells in order.

## Input Image

The repository includes `wallpaper.jpg`, which is used as the sample image in several practicals.

If a notebook uses a different image filename (for example, `input.jpg`), place that image in the same folder as the notebook or update the image path in the code.

## Learning Objectives

Through these practical assignments, the repository provides hands-on practice with:

- Basic image and video operations
- Color-space conversion and thresholding
- Spatial-domain image enhancement
- Image smoothing and sharpening
- Noise models and noise removal
- Texture feature extraction using LBP
- Image quality evaluation using PSNR
- Global threshold-based image segmentation

## How to Use

Each notebook contains the code for one or more practical exercises. Run the cells sequentially, provide input values when prompted, and observe the displayed images, outputs, and plots.

Some operations may take longer to execute depending on the image dimensions and the selected filter window size.

## Author

**Manmeet Kaur**

---

This repository is maintained for academic learning and practice in Image and Video Processing.
