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

## 📖 References

### Papers

1. Zhai, X. et al.  
   **Sigmoid Loss for Language Image Pre-Training (SigLIP)**  
   arXiv, 2023  
   https://arxiv.org/abs/2303.15343

2. Google Research  
   **SigLIP2: Multilingual Vision-Language Encoders with Improved Semantic Understanding**  
   arXiv, 2024  
   https://arxiv.org/abs/2502.14786

---

### Hugging Face Resources

- Hugging Face SigLIP Documentation  
  https://huggingface.co/docs/transformers/model_doc/siglip

- Hugging Face SigLIP2 Models  
  https://huggingface.co/docs/transformers/model_doc/siglip2

---

### Official Implementations

- Google Research Big Vision Repository  
  https://github.com/google-research/big_vision

- Hugging Face Transformers  
  https://github.com/huggingface/transformers

## 📜 License
MIT License
