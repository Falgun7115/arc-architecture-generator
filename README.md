# 🏗️ RAG + GAN Architecture Image Generator

## 📌 Overview
This project generates architectural images using a combination of:

- 🎨 GAN (Generator + Discriminator)
- 🧠 CLIP (for text-image understanding)
- 🔍 FAISS (for Retrieval-Augmented Generation - RAG)

The system takes a text prompt and generates realistic building designs.

---

## 🚀 Features
- Text-guided image generation
- CLIP-based semantic alignment
- Retrieval of similar architectural images
- GAN-based image synthesis

---

## 🛠️ Tech Stack
- Python
- PyTorch
- OpenCLIP
- FAISS
- Google Colab

---

## ▶️ How to Run

1. Open the notebook in Google Colab  
2. Mount Google Drive  
3. Set dataset path  
4. Run all cells  

---
## Dataset Setup

Download dataset:
https://www.kaggle.com/datasets/wwymak/architecture-dataset

Place it in:
/content/drive/MyDrive/arcDataset



## ⚠️ Limitations

The generated images are slightly blurry due to:

- Low image resolution (64×64)
- Limited training epochs
- Use of basic GAN architecture (DCGAN)
- Limited dataset size

---

## 🔧 Future Improvements

- Use higher resolution (128×128 or 256×256)
- Train for more epochs
- Use advanced models (StyleGAN / Diffusion Models)
- Improve dataset quality
- Increase CLIP guidance strength

## OUTPUT

<img width="387" height="393" alt="Screenshot 2026-04-05 at 2 21 03 PM" src="https://github.com/user-attachments/assets/6d0253f3-9ec8-4e93-ba1e-9c64ce673fe1" />
