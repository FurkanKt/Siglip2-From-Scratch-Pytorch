# SigLIP2-From-Scratch-PyTorch

A clean and from-scratch PyTorch implementation of **SigLIP2**, Google’s multimodal vision-language model based on sigmoid contrastive learning for image-text representation learning.

---

## 📌 Overview

SigLIP2 is the successor to SigLIP and improves multimodal representation learning using a sigmoid-based contrastive objective instead of the standard softmax loss used in CLIP-style models.

Unlike traditional contrastive learning approaches, SigLIP2 scales efficiently and provides strong zero-shot and retrieval performance across vision-language tasks.

This repository provides a minimal and readable implementation focused on educational clarity and research experimentation.

---

## 🚀 Features

- From-scratch PyTorch implementation
- Modular Vision Transformer (ViT) encoder
- Transformer-based text encoder
- Sigmoid contrastive learning objective
- Clean and extensible codebase
- Easy dataset customization
- Research-friendly training pipeline

---

## 🧠 Architecture

SigLIP2 consists of:

### Vision Encoder
- Vision Transformer (ViT)
- Patch embeddings
- Multi-head self-attention
- Positional embeddings

### Text Encoder
- Transformer encoder
- Token embeddings
- Self-attention layers

### Training Objective
- Sigmoid contrastive loss
- Efficient pairwise optimization

## 📜 License
MIT License
