# 🖼️ Image Processing Techniques with OpenCV

This project showcases classic and modern **image processing techniques** using `OpenCV`, `NumPy`, and `Matplotlib` in Python. It demonstrates how to enhance, filter, and analyze grayscale images using both **spatial** and **frequency domain methods**.

---

## 📚 Techniques Covered

### 🧼 1. Noise Reduction
- **Gaussian Blur**: Removes Gaussian noise using a kernel-based smoothing filter.
- **Median Blur**: Removes salt-and-pepper noise by taking the median of surrounding pixels.

### 🧱 2. Edge Detection
- **Sobel Operator**: Computes gradient edges in X and Y directions.
- **Laplacian of Gaussian**: Highlights regions of rapid intensity change.
- **Canny Edge Detector**: A multi-stage algorithm for strong edge detection.

### 🎨 3. Contrast Enhancement
- **Histogram Equalization**: Improves contrast by spreading pixel intensity distribution.
- **CLAHE (Contrast Limited Adaptive Histogram Equalization)**: Enhances contrast in small regions (tiles) without overamplifying noise.

### 🌐 4. Frequency Domain Filtering
- **Low-pass Filtering**: Retains smooth regions; removes high-frequency noise.
- **High-pass Filtering**: Highlights edges and sharp transitions; suppresses smooth areas.
- Powered by **Fourier Transform** (`np.fft`) for frequency analysis.

---

## 📁 Folder Structure


---

## 🧪 Sample Results

| Technique            | Sample Output |
|----------------------|----------------|
| Noise Reduction      | ![Gaussian Blur](outputs/noise_reduction/sample_gaussian.jpg) |
| Edge Detection       | ![Canny Edge](outputs/edge_detection/sample_canny.jpg) |
| Contrast Enhancement | ![CLAHE](outputs/contrast_enhancement/sample_clahe.jpg) |
| Frequency Filtering  | ![Low Pass](outputs/frequency_domain/sample_lowpass.jpg) |

> *Note: Outputs are generated dynamically and only a few are included here for demonstration.*



