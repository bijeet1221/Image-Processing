# Frequency Domain Image Processing and Filtering

This repository contains a collection of Python scripts for image processing in the frequency domain using Fast Fourier Transform (FFT). The scripts demonstrate various techniques such as FFT on rows and columns, 2D FFT, high-pass filtering, and Gaussian filtering. 

## Features

### 1. **1D FFT Processing (`1D.py`)**
- Applies FFT along rows and columns of grayscale images.
- Visualizes the original image, FFT on rows and columns (log scale), and reconstructed images using inverse FFT.
- Helps understand how the 1D FFT transforms images in specific dimensions.

### 2. **2D FFT Processing (`2D.py`)**
- Implements 2D FFT for complete image frequency domain transformation.
- Displays the original image, magnitude spectrum, and reconstructed image.
- Highlights the effect of 2D FFT on the entire image.

### 3. **High-Pass Filtering (`high_pass_filter.py`)**
- Demonstrates high-pass filtering using FFT to emphasize edges and remove low-frequency components.
- Uses a circular mask to filter high-frequency components.
- Visualizes the input image, magnitude spectrum, masked spectrum, and the image after applying inverse FFT.

### 4. **Edge Detection with Gaussian Filter (`edge_detection.py`)**
- Combines FFT and a Gaussian filter for edge detection.
- Filters the frequency domain using a Gaussian kernel.
- Shows the original and filtered images.

### 5. **Gaussian Filtering in Frequency Domain (`gaussian.py`)**
- Applies a Gaussian filter directly in the frequency domain to smooth images.
- Reconstructs the image after filtering.
- Useful for understanding the effect of low-pass filtering in the frequency domain.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/<username>/frequency-domain-image-processing.git
    cd frequency-domain-image-processing
    ```

2. Install the required Python libraries:
    ```bash
    pip install numpy opencv-python matplotlib
    ```

3. Run the scripts:
    - Replace `image1.jpg`, `image2.jpg`, etc., with your own images or ensure these images are in the same directory.
    - Use the following commands:
      ```bash
      python 1D.py
      python 2D.py
      python high_pass_filter.py
      python edge_detection.py
      python gaussian.py
      ```

## Results
Each script generates plots that show:
- The input image.
- Frequency domain transformations (e.g., FFT, magnitude spectrum).
- Filtered or reconstructed images.

## Dependencies
- **NumPy**: For numerical operations and FFT.
- **OpenCV**: For image reading, manipulation, and DFT.
- **Matplotlib**: For visualization.

## Contribution
Feel free to contribute by submitting issues or pull requests. Any feedback is welcome!


