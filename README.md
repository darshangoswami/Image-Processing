# Image-Processing

This project implements and demonstrates various image processing techniques using Python. It focuses on fundamental operations such as sampling, filtering, noise reduction, and edge detection.

## Project Overview

The project is divided into five main problems, each exploring different aspects of image processing:

1. Image Sampling
2. Gaussian Smoothing
3. Image Filtering and Upsampling
4. Noise Reduction
5. Sobel Filter and Edge Detection

## Requirements to run in Jupyter Notebook or JupyterLab

- Python 3.x
- NumPy
- OpenCV (cv2)
- Matplotlib
- Pillow (PIL)

You can install the required packages using:

```
pip install numpy opencv-python matplotlib pillow
```

## Usage for Jupyter Notebook or JupyterLab

Each problem is implemented in a separate section of the main Jupyter notebook (`main.ipynb`). To run the experiments:

1. Open the `main.ipynb` file in Jupyter Notebook or JupyterLab.
2. Ensure you have the 'Lenna.png' image in the same directory as the notebook.
3. Run all cells in order to see the results of each problem, since some problems share functions from previous problems

## Installation to run in VS Code

1. Download and extract the project.

2. In the project directory set up a virtual environment:

```
python3 -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```

3. Install dependencies:

```
pip install -r requirements.txt
```

## Usage for VS Code

1. Open the project folder in VS Code
2. Open the main.ipynb file.
3. Click on "Run All" Button. (VS Code might ask you to install the Jupyter kernel is not already installed.)
4. Some problems share functions from previous problems, so make sure to run all of them together.

## Results

The notebook generates various output images for each problem, demonstrating the effects of different image processing techniques. These results are displayed inline in the notebook after each corresponding code cell. Key outputs include:

- Downsampled and upsampled images
- Gaussian smoothed images with varying parameters
- Noise reduction comparisons
- Edge detection visualizations

## Acknowledgments

- The project uses the standard 'Lenna' image, which is widely used in image processing literature.
- Inspired by fundamental image processing techniques taught in computer vision courses.
