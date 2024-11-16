# Edge Detection with Oriented Non-Maximum Suppression

This project demonstrates an edge detection technique using oriented non-maximum suppression (NMS) combined with Sobel filters. The algorithm processes grayscale images to enhance edges and suppress non-relevant features, making it particularly useful for applications like crack detection, texture analysis, or general image preprocessing.

---

## Features

- **Oriented Non-Maximum Suppression**: Enhances edge clarity by suppressing non-maximum pixels in gradient directions.
- **Adjustable Parameters**: Tweak thresholds, Gaussian blur strength, and Sobel filter parameters for fine-tuning.
- **Image Morphology Operations**: Post-processing using morphological closing for improved output clarity.
- **Visualization**: Displays processed images in real-time.

---

## Requirements

- Python 3.7+
- OpenCV
- NumPy
- SciPy

Install dependencies with:
```bash
pip install opencv-python-headless numpy scipy
