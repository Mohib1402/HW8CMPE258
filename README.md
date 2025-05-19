# 🧠 Assignment 8 — Computer Vision (Contrastive Learning, Transfer Learning, and More)

This repository contains four comprehensive Google Colab notebooks demonstrating supervised contrastive learning, multi-modal transfer learning, and advanced video and image classification techniques using state-of-the-art deep learning models.

---

## 🔗 Colab Notebooks

| Part | Title | Link |
|------|-------|------|
| ✅ Part 1 | **Supervised Contrastive Learning vs Softmax** | [Colab](https://colab.research.google.com/drive/1mKNmaaAs77CTVvauHENq8DbJYoThsLFI?usp=sharing) |
| ✅ Part 2 | **Image, Audio, Video Transfer Learning** | [Colab](https://colab.research.google.com/drive/1h_RcbAnGY3GRQ2BYxWU9LPK72dX_vTsV?usp=sharing) |
| ✅ Part 3 | **Zero-Shot Learning using CLIP + BigTransfer** | [Colab](https://colab.research.google.com/drive/1LYEVUwzjCX1HOtsYutUSDZZNespQr4s1?usp=sharing) |
| ✅ Part 4 | **Vision Classifiers: MNIST, Fashion-MNIST, CIFAR-10, X-ray, CT** | [Colab](https://colab.research.google.com/drive/1FJkFMJUf-tV2IuJKhLUIropM-QKi4iKx?usp=sharing) |

---

## 📌 Assignment Breakdown

### ✅ Part 1: Supervised Contrastive Learning
- Dataset: CIFAR-10
- Comparison between:
  - Traditional Softmax classifier
  - Supervised Contrastive Learning with frozen encoder + classifier
- Visualizations: t-SNE, Accuracy Curves, Confusion Matrix

---

### ✅ Part 2: Transfer Learning (Multimodal)
- **Image**: Transfer learning with EfficientNetB0 (feature extraction + fine-tuning)
- **Audio**: YAMNet-based zero-shot inference on a custom WAV file
- **Video**: I3D model from TensorFlow Hub with a custom uploaded video

---

### ✅ Part 3: Zero-Shot Transfer Learning
- Used OpenAI’s CLIP model for image-text matching
- Explored BigTransfer (BiT) with flower classification dataset
- Demonstrated zero-shot and fine-tuned classification workflows

---

### ✅ Part 4: Vision Classifiers (Multiple Datasets)
- Implemented classifiers for:
  - MNIST
  - Fashion-MNIST
  - CIFAR-10
  - X-ray Pneumonia detection
  - 3D CT Scan classification
- Models used:
  - EfficientNet
  - BiT (BigTransfer)
  - MLP-Mixer
  - ConvNeXt-v2

---

## Walkthrough
[Demo]()

---

## 📊 Technologies & Frameworks
- TensorFlow / Keras
- TensorFlow Hub
- Hugging Face Transformers
- CLIP
- t-SNE, Matplotlib, Seaborn
- PyTorch (for optional zero-shot inference)

---

## 📁 How to Run
All notebooks are self-contained and runnable in Google Colab. Simply click any notebook link and follow the execution cells in order. If using your own data (video/audio), upload it manually in the corresponding cells.

---

## ✍️ Author
**Mohibkhan Pathan** — MS Software Engineering @ SJSU  
[LinkedIn](https://www.linkedin.com/in/mkpathan/) | [GitHub](https://github.com/mohib1402)

---

