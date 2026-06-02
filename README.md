# proteinspectranet
Code and experiments for protein-to-spectrogram transformation, spectral representation learning, and antiviral peptide classification.

# Protein-to-Spectrogram AVP Classification

## Overview

This repository contains the implementation of a signal-processing and deep-learning framework for antiviral peptide (AVP) classification. The proposed approach transforms protein sequences into audio-like signals using biologically inspired encoding strategies and subsequently generates spectrogram-based representations for deep spectral learning.

The framework integrates protein signal generation, time–frequency analysis, spectrogram construction, data augmentation, and attention-enhanced convolutional neural networks for antiviral peptide classification.

---

## Methodology

The workflow consists of the following stages:

1. Protein sequence acquisition from the ENNAVIA datasets.
2. Transformation of protein sequences into one-dimensional signals using multiple biochemical mapping strategies.
3. Generation of time–frequency representations through signal-processing techniques.
4. Construction of spectrogram images for visual feature extraction.
5. Data augmentation and preprocessing.
6. Deep learning using CNN-based architectures with attention mechanisms.
7. Performance evaluation using standard classification metrics.

---

## Datasets

Experiments were conducted using the ENNAVIA benchmark datasets:

* ENNAVIA-A
* ENNAVIA-B
* ENNAVIA-C
* ENNAVIA-D

Dataset source:

https://research.timmons.eu/ennavia-dataset/

---

## Models

The repository includes implementations of:

* InceptionV3
* EfficientNetV2-S
* EfficientNetV2-M
* ResNet50
* Squeeze-and-Excitation (SE) Attention
* Convolutional Block Attention Module (CBAM)
* CutMix Augmentation

---

## Performance

The proposed framework achieved strong classification performance on multiple ENNAVIA subsets, with the best configuration reaching approximately 95% accuracy.

---

## Repository Structure

```text
dataset/
│
├── fasta_sequences/
├── generated_signals/
├── spectrograms/
│
models/
├── inceptionv3/
├── efficientnetv2/
├── resnet50/
│
training/
evaluation/
results/
figures/
```

---

## Requirements

* Python 3.10+
* TensorFlow
* Keras
* NumPy
* Pandas
* SciPy
* Librosa
* Matplotlib
* Scikit-learn
* OpenCV



---


## Citation

If you use this repository in your research, please cite the corresponding journal article.

```bibtex
Citation information will be added after publication.
```

---

## License

This repository is provided for academic and research purposes.
