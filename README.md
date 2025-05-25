# Conditional GAN for Sketch-to-Face Generation 🧠🎨

This project implements a Conditional Generative Adversarial Network (CGAN) using PyTorch to convert grayscale sketch images into realistic face images. 
The generator learns to map input sketches to their corresponding face photos while the discriminator ensures the generated images look realistic by evaluating both real and fake pairs.

## 🔧 Features

- Custom data loader that preprocesses sketch-photo pairs from `train`, `val`, and `test` sets.
- Generator with Conv + TransposeConv layers for upsampling.
- Discriminator that conditions on sketch inputs.
- Visualization of generator and discriminator loss progression.
- Model saving for inference or reuse.

## 🚀 How to Use

1. Run the training script (included in notebook/code).
2. Sketch images are passed through the generator to produce realistic faces.
3. Trained models are saved as `generator3.pth` and `discriminator3.pth`.
