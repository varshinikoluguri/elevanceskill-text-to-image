# elevanceskill-text-to-image
Text-to-Image Generation using GANs, Transformers and Stable Diffusion

Project Overview

This project explores a complete text-to-image generation workflow by combining Generative Adversarial Networks (GANs), Transformers, attention mechanisms, and Stable Diffusion with LoRA fine-tuning.

The project was completed as part of the ElevanceSkills internship and consists of six tasks that cover different components of text-to-image generation.

Tasks Completed

Task 1 — Stable Diffusion LoRA Fine-Tuning

A Stable Diffusion model was fine-tuned using LoRA with a custom image dataset. The trained LoRA weights were then used to generate a sample image.

Task 2 — Conditional GAN

A Conditional GAN (CGAN) was implemented to generate images based on category labels such as square, triangle, and circle.

Task 3 — Text Embeddings

Text descriptions were tokenized and converted into numerical embeddings using a Transformer-based text encoder.

Task 4 — Oxford-102 Flowers Dataset Exploration

The Oxford-102 Flowers dataset was explored by examining its classes, images, resolutions, and text descriptions.

Task 5 — Attention Mechanism

Attention mechanisms were implemented to help the model focus on relevant information during image generation.

Task 6 — Complete Text-to-Image Pipeline

The components were combined into a text-to-image workflow involving text preprocessing, text embeddings, text conditioning, GAN-based generation, and generated image output.

Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Diffusers
- Stable Diffusion
- LoRA
- Conditional GAN
- Attention Mechanisms
- Google Colab

Project Outcome

The project demonstrates the major stages involved in text-to-image generation, from text processing and embeddings to conditional generation and Stable Diffusion fine-tuning.
