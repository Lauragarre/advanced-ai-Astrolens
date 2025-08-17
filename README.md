# AstroLens: Intelligent Universe Explorer with AI

AstroLens is a project that applies **Deep Learning and Computer Vision** to classify astronomical images into different categories (galaxies, stars, nebulae, etc.).  
It serves as a first step toward a broader system capable of **object detection, clustering, and automated descriptions** of celestial images.

---

## Objectives
- Build a Convolutional Neural Network (CNN) to classify galaxies from real telescope data.
- Explore extensions such as **clustering embeddings**, **object detection** (YOLO/DETR), and **LLM-based descriptions**.
- Provide a reproducible pipeline that can be executed in **Google Colab**.

---

## Requirements
Main dependencies:
- TensorFlow / Keras
- astroNN (dataset loader for Galaxy10 DECaLS)
- NumPy, Pandas, Matplotlib, scikit-learn

Install locally (optional):
```bash
pip install -r requirements.txt