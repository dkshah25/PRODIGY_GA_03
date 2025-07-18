# Pix2Pix Image-to-Image Translation using cGAN

This project implements a Pix2Pix model using Conditional GANs (cGAN) for image-to-image translation. The task was completed as part of my internship with **Prodigy InfoTech**. The dataset used is the **CMP Facade** dataset, where the model learns to translate building facade labels into realistic building images.

---

## 📌 Project Objective

- Implement Pix2Pix using a Conditional GAN (cGAN).
- Perform paired image-to-image translation using a pre-trained dataset.
- Visualize results: input image, ground truth, and predicted image.

---

## 🧠 Technologies Used

- Python
- TensorFlow
- Google Colab
- Matplotlib
- CMP Facades Dataset

---

## 📁 Dataset

- Dataset: [CMP Facades](https://people.eecs.berkeley.edu/~tinghuiz/projects/pix2pix/datasets/)
- Format: Paired images (labels and facades)
- Structure:
  ```
  facades/
  ├── train/
  ├── test/
  └── val/
  ```

---

## ⚙️ Steps Performed

1. ✅ Set up environment (TensorFlow, image utils)
2. ✅ Downloaded and extracted the CMP Facades dataset
3. ✅ Preprocessed paired images: resizing, normalization
4. ✅ Built Generator and Discriminator models
5. ✅ Trained model using cGAN loss and generator loss
6. ✅ Visualized predictions (input vs ground truth vs generated)
7. ✅ Saved sample result to `results/epoch_20_sample.png`

---

## 🖼️ Sample Output

| Input Image | Ground Truth | Predicted Image |
|-------------|---------------|------------------|
| ![input](results/epoch_20_sample.png) | ![gt](results/epoch_20_sample.png) | ![pred](results/epoch_20_sample.png) |

(*Note: All 3 images in a row are included in the single output image*)

---

## 📦 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/pix2pix-facades.git
   cd pix2pix-facades
   ```

2. Upload to [Google Colab](https://colab.research.google.com/) or run locally with GPU.

3. Install dependencies (if running locally):
   ```bash
   pip install tensorflow matplotlib
   ```

4. Run `pix2pix_facades.ipynb` step by step.

---

## 📁 Folder Structure

```
pix2pix-facades/
├── facades/                   # Dataset folder
│   ├── train/
│   ├── test/
│   └── val/
├── results/
│   └── epoch_20_sample.png    # Output image
├── pix2pix_facades.ipynb      # Main notebook
└── README.md
```

---

## ✅ Internship Task Completed

This repository was created for the **"Image-to-Image Translation with cGANs"** task of my **Generative AI Internship** at **Prodigy InfoTech**.

---

## 🙋‍♂️ Author

**Dharmit Shah**  
[LinkedIn](https://www.linkedin.com/in/dharmit-shah2508) • [GitHub](https://github.com/dkshah25)

---

## 📃 License

This project is open-source and free to use for educational purposes.
