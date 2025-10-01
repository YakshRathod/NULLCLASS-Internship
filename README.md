# Text-to-Image Generation Internship Project

This repository contains the implementation of a text-to-image generation pipeline using GANs and related techniques. The project demonstrates a multi-task workflow simulating real-world applications.

## Project Overview
The main goal is to generate images from textual descriptions using GANs. The project covers:

- Text preprocessing and tokenization
- GAN-based image generation
- Attention mechanisms
- Custom dataset training
- Evaluation and visualization of generated images

## Tasks Implemented
1. **Text-to-Image GAN Pipeline**  
   - Complete pipeline with image generation, text preprocessing, and embedding creation.

2. **Attention Strategies**  
   - Applied self-attention/cross-attention in the GAN to improve image quality.

3. **Custom Dataset Fine-Tuning**  
   - Fine-tuned the GAN on a custom dataset to generate domain-specific visuals.

4. **Public Dataset Analysis**  
   - Explored dataset statistics (e.g., COCO, Oxford-102 Flowers) and visualized text-image pairs.

5. **Text Embedding Preprocessing**  
   - Used a simple tokenizer to encode captions for GAN input.

6. **Conditional GAN (CGAN)**  
   - Generated images from textual labels/categories (e.g., shapes like "circle" or "square").

## Folder Structure
- Task1_TextToImageGAN.ipynb
- Task2_Attention.ipynb
- Task3_CustomDataset.ipynb
- Task4_DatasetAnalysis.ipynb
- Task5_TextEmbeddings.ipynb
- Task6_CGAN.ipynb
- GAN_samples/ # Generated images
- README.md


## How to Run
1. Open the respective task notebook in Google Colab.
2. Mount your Google Drive if using a dataset stored there.
3. Update the dataset path in the notebook if required.
4. Run cells sequentially to train models and visualize outputs.

## Requirements
- Python 3.8+
- PyTorch
- torchvision
- PIL (Pillow)
- matplotlib
- numpy

## Results
- GAN-generated images are saved in `GAN_samples/`.
- Training progress and loss curves are plotted in notebooks.

## Notes
- All code is commented and structured for readability.
- The project is fully reproducible with the provided notebooks and dataset.

