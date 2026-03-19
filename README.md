# From-Strokes-to-Sentences-Handwritten-Text-Recognition-using-Vision-Transformer
Handwritten Text Recognition using Vision Transformer hybrid with CTC loss, MC Dropout, and multi-script support

## Overview
A deep learning system for recognizing handwritten text across multiple scripts using a **CNN-ViT hybrid architecture** with CTC loss. Designed with accessibility features including Text-to-Speech (TTS), voice search, and translation.

## Architecture
- **CNN** — Local feature extraction from handwritten strokes
- **Vision Transformer (ViT)** — Global sequence modeling for character dependencies  
- **CTC Loss** — Sequence-to-sequence alignment without explicit segmentation
- **MC Dropout** — Uncertainty estimation for low-confidence predictions

## Datasets
- IAM (English handwriting)
- LAM (Italian handwriting)
- Devanagari handwritten characters

## Features
- Multi-script handwritten text recognition
- Uncertainty-aware predictions via MC Dropout
- Text-to-Speech (TTS) output
- Voice search and translation integration

## Tech Stack
`Python` `PyTorch` `CNN` `Vision Transformer` `CTC Loss` `Jupyter Notebook`

## How to Run
```bash
# Clone the repo
git clone https://github.com/Meenakshi-20/HTR-VT.git

# Install dependencies
pip install torch torchvision transformers

# Open the notebook
jupyter notebook From_Strokes_to_Sentences_HTR_VT.ipynb
```
