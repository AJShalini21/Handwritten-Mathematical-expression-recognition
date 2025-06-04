# Handwritten-Mathematical-expression-recognition

# Handwritten Arithmetic Expression Recognition

This project implements a complete system to recognize and evaluate handwritten arithmetic expressions in real time. It combines image preprocessing, symbol classification using deep learning, sequence recognition, expression parsing, and final computation.

## Features

- End-to-end pipeline from image to evaluated result
- Symbol recognition using CNN, MobileNetV2, and ResNet
- Sequence modeling with contour detection and symbol classification
- Secure expression parsing and evaluation

## Models Used

- **Basic CNN**: Lightweight, fast, moderate accuracy
- **MobileNetV2**: Efficient and accurate with low memory usage
- **ResNet**: Most accurate (~94.2%) but computationally intensive

## Dataset

- **Symbol recognition**: [Kaggle - Handwritten Math Symbols](https://www.kaggle.com/datasets/xainano/handwrittenmathsymbols)
- **Sequence data**: Custom handwritten expression images with annotated ground truth

## Tech Stack

- Python, TensorFlow/Keras, OpenCV
- Jupyter Notebook for development
- Image processing: grayscale conversion, resizing, normalization, contour detection

## Evaluation Metrics

- Classification Accuracy
- Loss Curves
- Precision, Recall, F1-Score
- Expression Recognition Accuracy

## Future Work

- Extend symbol support (e.g., exponents, roots)
- Improve generalization for diverse handwriting styles
- Optimize for deployment in educational tools

## References

- [MobileNetV2: CVPR 2018](https://doi.org/10.1109/CVPR.2018.00474)
- [Offline Handwritten Expression Recognition](https://doi.org/10.1109/ICICET.2018.8533789)
- [Handwritten Math Recognition Tool](https://doi.org/10.1109/ICCIDS.2019.8862155)

---

*Developed by Shalini Ananthavel Jayalakshmi*
