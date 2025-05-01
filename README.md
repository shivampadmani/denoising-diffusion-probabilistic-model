# 🌫️ Diffusion Models in Representation Learning

Welcome to this repository of practical implementations of **diffusion models** from my Representation Learning course at IISc. These Jupyter notebooks aim to provide clean, minimal, and understandable code for key models in the diffusion family — including **Denoising Diffusion Probabilistic Models (DDPMs)**, **Improved Diffusion Models**, and **DDIM Inversion Techniques**.

> 📚 These implementations are meant to help fellow students, researchers, and enthusiasts understand and experiment with the foundational ideas in generative modeling using diffusion processes.

---

## 📁 Repository Structure

```bash
diffusion-models-representation-learning/
│
├── ddpm.ipynb                  # Vanilla Denoising Diffusion Probabilistic Model
├── improved_diffusion.ipynb    # Advanced model with classifier-free guidance
├── ddim_inversion.ipynb        # DDIM Inversion and Latent Interpolation
└── README.md                   # You're here!
```
🚀 Highlights
✅ ddpm.ipynb
Implements the original DDPM model with forward and reverse noising processes.

Trains a simple UNet-based architecture to learn denoising steps.

Visualizes the diffusion process and sample generation.

✅ improved_diffusion.ipynb
Includes techniques from "Improved Denoising Diffusion Probabilistic Models".

Classifier-free guidance for conditional generation.

Enhanced sampling quality and flexibility.

✅ ddim_inversion.ipynb
Implements the DDIM inversion algorithm.

Extracts latent representations of real images.

Enables latent-space interpolation and image reconstruction.

🛠️ How to Run
Clone the repo:


```
git clone https://github.com/yourusername/diffusion-models-representation-learning.git
cd diffusion-models-representation-learning
```
Install requirements (if needed):

bash
```
pip install -r requirements.txt
```
jupyter notebook
🎓 Learn More
DDPM (Ho et al., 2020)

Improved Diffusion Models (Nichol & Dhariwal, 2021)

DDIM (Song et al., 2020)

🙌 Contribution & Credits
These notebooks were developed as part of the Representation Learning course at IISc Bangalore. Feel free to fork, modify, or extend the notebooks for your own use. If you find these helpful, a star ⭐ or share is appreciated!

📬 Contact
Feel free to reach out via:

GitHub Issues

LinkedIn

Let’s build open, understandable AI together! 🤖
