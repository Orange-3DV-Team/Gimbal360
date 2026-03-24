# Gimbal360: Differentiable Auto-Leveling for Canonicalized $360^\circ$ Panoramic Image Completion

<div align="center">
  <img src="asset\gimbal360.png" alt="Gimbal360" width="200"/>
</div>

**TL;DR:** Gimbal360 robustly canonicalizes unposed perspective images using differentiable auto-leveling, enabling structurally consistent and seamless 360° panorama generation.

## 📖 Abstract

Diffusion models excel at 2D outpainting, but extending them to $360^\circ$ panoramic completion from unposed perspective images is challenging due to the geometric and topological mismatch between perspective projections and spherical panoramas.
We present **Gimbal360**, a principled framework that explicitly bridges perspective observations and spherical panoramas. We introduce a Canonical Viewing Space that regularizes projective geometry and provides a consistent intermediate representation between the two domains. To anchor in-the-wild inputs to this space, we propose a Differentiable Auto-Leveling module that stabilizes feature orientation without requiring camera parameters at inference.
Panoramic generation also introduces a topological challenge. Standard generative architectures assume a bounded Euclidean image plane, while Equirectangular Projection (ERP) panoramas exhibit intrinsic $S^1$ periodicity. Euclidean operations therefore break boundary continuity. We address this mismatch by enforcing topological equivariance in the latent space to preserve seamless periodic structure.
To support this formulation, we introduce Horizon360, a curated large-scale dataset of gravity-aligned panoramic environments. Extensive experiments show that explicitly standardizing geometric and topological priors enables Gimbal360 to achieve state-of-the-art performance in structurally consistent $360^\circ$ scene completion.

## 🖼️ Framework
<div align="center">
  <img src="asset\Framework.jpg" alt="framework"/>
</div>

## 🔗 Links

- 🌐 **Project Page**: [https://orange-3dv-team.github.io/Gimbal360](https://orange-3dv-team.github.io/Gimbal360)
- 📄 **Paper**: Coming Soon
- 💻 **Code**: Coming Soon
- 🤗 **Dataset**: Coming Soon

## 📅 Open Source Plan

The following content of this project will be open-sourced at the appropriate time:

### ⏳ Coming Soon

- **📝 Paper**: The research paper will be publicly available on arxiv soon.
- **💾 Code & Dataset**: The release of this code and dataset are subject to a corporate compliance and security review.


## 🎥 Preview

Visit our [Project Page](https://orange-3dv-team.github.io/Gimbal360/) to view complete demo videos and visual results.

## ⭐ Star

If you're interested in this project, please give us a Star ⭐ to receive timely open-source notifications!

---

<div align="center">
  <sub>Built with ❤️ by Orange Team</sub>
</div>
