# DNN_Final_template

## Overview

This project explores multimodal story reasoning using deep learning techniques that combine computer vision and natural language processing. The system is designed to understand relationships between image sequences and textual narratives, enabling machines to interpret stories more effectively.

The implementation is built using PyTorch, Hugging Face Transformers, and pretrained deep learning models. The notebook processes visual and textual information together to learn meaningful connections between images and story descriptions.

The project was developed and tested in Google Colab with GPU acceleration support.

---

# Project Objectives

The main objective of this project is to build a multimodal deep learning pipeline capable of understanding and reasoning over stories represented through both images and text.

The project focuses on:

- Loading and preprocessing multimodal datasets
- Extracting visual features from image sequences
- Processing textual story descriptions
- Building a custom dataset pipeline for multimodal learning
- Training a vision-language reasoning model
- Learning shared representations between images and text using contrastive learning
- Evaluating generated outputs using ROUGE metrics
- Saving and restoring model checkpoints efficiently

---

# Technologies Used

## Programming Language

- Python 3

## Frameworks and Libraries

- PyTorch
- Torchvision
- Hugging Face Transformers
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- ROUGE Score

---


## Dataset

The project uses the following dataset:

`daniel3303/StoryReasoning`

The dataset contains:

- Sequential story images
- Story descriptions
- Multimodal reasoning samples
- Image-text relationships

Both training and testing splits are loaded for experimentation and evaluation.


---

# Project Workflow

## 1. Environment Setup

The notebook begins by importing all required libraries and configuring the runtime environment.

Key setup steps include:

- Importing PyTorch modules
- Detecting GPU availability
- Loading NLP and dataset utilities
- Initializing visualization libraries
- 
---


# Model Architecture

## Visual Encoder

The project uses a pretrained ResNet50 model for visual feature extraction.

Key features include:

- Pretrained ImageNet weights
- Deep visual feature extraction
- Sequential image representation learning
- Embedding generation for multimodal fusion

---

## Text Encoder

The text encoder processes story descriptions and transforms them into semantic representations.

The text pipeline handles:

- Tokenized inputs
- Attention masks
- Text embeddings
- Semantic understanding

---





# Project Structure

```text
Story-Reasoning-Project/
│
├── notebooks/
│   └── experiment_notebook.ipynb
│
├── datasets/
│   └── storyreasoning_dataset/
│
│
├── outputs/
│   ├── generated_results/
│   └── evaluation_scores/
│
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

---


# Conclusion

This project presents a complete multimodal deep learning pipeline for story reasoning tasks involving both images and text. By combining computer vision techniques with natural language processing, the system learns meaningful relationships between visual and textual information.

The implementation provides a strong foundation for further research in multimodal AI, vision-language understanding, and intelligent storytelling systems.

---


```text

