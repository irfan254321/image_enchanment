# image_enchanment

# 🌟 Image Enhancement Toolkit

A robust and versatile Python framework designed to automatically restore, correct, and enhance low-quality images across various real-world degradation scenarios. Whether your input is underexposed, severely blurred, or washed out, this pipeline adapts dynamic processing techniques to recover visual clarity and fine details.

## ✨ Supported Degradation Types

* **Dark & Underexposed Images:** Gamma correction, adaptive histogram equalization (CLAHE), and dynamic range expansion to reveal shadow details without blowing out midtones.
* **Overexposed & Bright Images:** Highlight recovery, tone mapping, and contrast rebalancing to restore washed-out regions.
* **Blurred & Soft Images:** Unsharp masking, edge-preserving sharpening, and deconvolution techniques to recover crisp edges.
* **Low-Contrast Images:** Adaptive global and local contrast stretching to enhance depth and perceptual sharpness.
* **Noisy & Grainy Inputs:** Denoising filters (Bilateral / Non-Local Means / Wavelet) that smooth out artifacts while preserving edges.

## 🚀 Key Features

* **Multi-Condition Robustness:** Handles single-case degradation as well as mixed artifacts (e.g., dark + noisy + blurry).
* **Batch Processing Support:** Easily process individual images or full datasets via CLI or modular API calls.
* **Flexible Architecture:** Modular pipeline allowing custom filter chaining, parameter tuning, or integration with deep learning backbones (CNN/GAN/Diffusion).