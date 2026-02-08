

# Proyek Image Generation

This repository contains my submission for **Belajar Fundamental Generative AI** on Dicoding.  
The project focuses on understanding the **image generation process** using Stable Diffusion — not just producing visually appealing outputs, but exploring how different parameters and sampling strategies affect the results.

---

##  Project Overview

The main goal of this project is to explore and implement an end-to-end image generation pipeline using **Stable Diffusion**, covering:

- Text-to-Image generation
- Image-to-Image generation
- Inpainting & Outpainting
- Scheduler experimentation
- Interactive deployment using Streamlit

This project emphasizes **process understanding**, parameter tuning, and experimentation rather than prompt-only usage.

---

##  Features

### 1. Text-to-Image

- Prompt & negative prompt input
- CFG scale tuning
- Inference steps control
- Seed reproducibility
- Output analysis based on parameter changes

### 2. Scheduler Experiments

- Euler A
- DPM++
- DDIM

Same prompt and seed can produce different results depending on the scheduler, highlighting the importance of the **sampling process**.

### 3. Image-to-Image

- Manual masking (trial & error)
- Auto masking
- Inpainting
- Outpainting (progressive zoom-out)

Image-to-image is more sensitive compared to text-to-image, especially in mask accuracy and strength configuration.

### 4. Streamlit Interface

The entire pipeline is wrapped into a simple Streamlit app:

- Prompt & negative prompt input
- CFG scale & inference steps sliders
- Scheduler selection
- Batch generation (2×2 grid)

This makes the project closer to a **real GenAI engineering workflow**, not just experimentation in notebooks.

---

##  Tech Stack

- Python
- PyTorch
- Diffusers
- Transformers
- Stable Diffusion
- Streamlit
- NumPy
- Pillow
- Matplotlib

---

## 📂 Project Structure

```
├── submission_BFGAI_Muhamad_Hamzah.ipynb
├── Streamlit_submission_BFGAI_Muhamad_Hamzah.ipynb
├── requirements.txt
└── README.md
```

---


## 🔗 Author

**Muhamad Hamzah**  
Learning Generative AI & Machine Learning Engineering

---
