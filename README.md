🏗️ CLIP-Guided GAN Architecture Image Generator
📌 Overview
This project generates architectural building images from text prompts by combining:
🎨 GAN (Generative Adversarial Network) for image synthesis
🧠 OpenCLIP for text-image semantic alignment
The model enhances traditional GANs by integrating CLIP-based loss, ensuring that generated images are not only realistic but also semantically aligned with the input text prompt.
🚀 Features
📝 Text-to-Image Generation (e.g., modern architecture, glass skyscraper)
🧠 CLIP-guided training for better semantic accuracy
🎨 GAN-based image synthesis (DCGAN architecture)
⚡ GPU acceleration using PyTorch
🧩 How It Works
Text Prompt
     ↓
CLIP → Text Embedding
     ↓
Generator → Create Image
     ↓
Discriminator → Check Realism
     ↓
CLIP Loss → Align Image with Text
➡️ The generator learns to produce images that are both visually realistic and contextually relevant to the input prompt.
🛠️ Tech Stack
Python
PyTorch
OpenCLIP
NumPy
Matplotlib
Google Colab
▶️ How to Run
1. Open the notebook in Google Colab  
2. Mount Google Drive  
3. Set dataset path  
4. Run all cells  
📂 Dataset Setup
Dataset:
https://www.kaggle.com/datasets/wwymak/architecture-dataset
Place it in:
/content/drive/MyDrive/arcDataset
⚠️ Limitations
Generated images may appear slightly blurry due to:
Low resolution (64×64)
Limited training epochs
Use of basic DCGAN architecture
Dataset size constraints
🔧 Future Improvements
Increase image resolution (128×128 / 256×256)
Train for more epochs
Use advanced models (StyleGAN / Diffusion Models)
Improve dataset diversity and quality
Tune CLIP loss weighting for better alignment
