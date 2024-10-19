# Vision Transformer from Scratch

This project implements a Vision Transformer (ViT) from scratch, demonstrating the complete process of building the ViT architecture, optimizing it with built-in PyTorch functionalities, and applying transfer learning to fine-tune the model on a custom dataset (Pizza, Steak, Sushi classification). 


## Introduction
The Vision Transformer is a powerful deep learning model that leverages the transformer architecture, initially popularized in Natural Language Processing (NLP), for image classification tasks. This project aims to:
1. Build the Vision Transformer blocks from scratch.
2. Use PyTorch's built-in `nn.TransformerEncoder` for optimization.
3. Fine-tune a pretrained Vision Transformer model on a custom dataset using transfer learning.

## Features
- Implementation of Vision Transformer blocks from scratch.
- Use of PyTorch's `nn.TransformerEncoder` for optimized training.
- Transfer learning to fine-tune the model on a Pizza, Steak, and Sushi dataset.
- End-to-end pipeline including data preprocessing, model training, and evaluation.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Piyush12800/VisionTransformer.git
    cd VisionTransformer
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure you have a CUDA-capable GPU for faster training (optional).

## Dataset
The project uses a custom dataset for classifying images of three classes: Pizza, Steak, and Sushi. You can download the dataset from utils or use your own dataset with the following structure:

