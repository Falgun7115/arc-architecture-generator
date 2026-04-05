🏗️ CLIP-Guided GAN Architecture Image Generator


📌 Overview

This project implements a CLIP-guided Generative Adversarial Network (GAN) to generate architectural building images from text prompts.
It combines:
🎨 GAN for realistic image generation
🧠 OpenCLIP for text-image understanding
The model ensures generated images are not only realistic but also semantically aligned with the input prompt.




🚀 Features

->📝 Text-to-Image generation (e.g., modern building, glass skyscraper)

->🧠 CLIP-based semantic guidance

->🎨 GAN-based image synthesis (DCGAN)

->⚡ GPU support using PyTorch

->📊 Visualization of generated images




🧩 How It Works


Random Noise → Generator → Fake Image
                           ↓
                    Discriminator
                     (Real/Fake)
                           ↓
                 CLIP → Text Similarity
                           ↓
                    Combined Loss





🛠️ Tech Stack


Python

PyTorch

OpenCLIP

NumPy

Matplotlib

Torchvision

Google Colab





▶️ How to Run

git clone https://github.com/your-username/clip-gan-architecture.git

cd clip-gan-architecture

pip install -r requirements.txt

Run in Google Colab

Open notebook in Colab

Mount Google Drive

Set dataset path

Run all cells





📂 Dataset


Download from Kaggle:

https://www.kaggle.com/datasets/wwymak/architecture-dataset

Place your Dataset here:

/content/drive/MyDrive/arcDataset





📊 Training Details

Model: DCGAN + CLIP Loss

Image Size: 64×64

Loss Functions:

Binary Cross Entropy (GAN)

CLIP Similarity Loss

Optimizer: Adam





🖼️ Sample Prompts

"modern architectural building"

"futuristic skyscraper"

"minimalist house design"






🖼️ Sample Outputs

<img width="387" height="393" alt="Screenshot 2026-04-05 at 2 21 03 PM" src="https://github.com/user-attachments/assets/cdfb7c6a-96d6-4121-bfb4-9bf9a49047cd" />





⚠️ Limitations
Output images may appear blurry due to:

Low resolution (64×64)

Limited training epochs

Basic GAN architecture

Dataset size




🔧 Future Improvements

Higher resolution (128×128 / 256×256)

More training epochs

Use StyleGAN / Diffusion models

Better dataset quality

Improve CLIP tuning
