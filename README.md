# slippery-surface-detection
Deep learning–based pixel-wise segmentation of slippery road surfaces using DeepLabV3+, attention mechanisms, curriculum learning, and semi-supervised enhancement strategies.

This repository implements a semantic segmentation pipeline for detecting slippery road regions using DeepLabV3+ augmented with attention mechanisms and curriculum-based training. The framework explores both fully supervised and semi-supervised strategies, including encoder-feature clustering (K-Means) for pseudo-label generation and a hybrid loss formulation to improve segmentation under limited annotated data.

Experimental evaluation demonstrates consistent improvements in IoU and Dice metrics over baseline models, as well as stability under realistic perturbations. The project emphasizes modular design, reproducibility, and extensibility for future research in road-surface condition estimation.
