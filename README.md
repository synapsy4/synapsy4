# 👋 Hi, I'm Adrian

**M.Sc. Cognitive Science** with a focus on **spatiotemporal modeling**.  
Interested in **computer vision** and **applied deep learning with PyTorch**.

---

## 🔍 About Me

I build end-to-end deep learning pipelines — from **data preprocessing** to **model training** and **evaluation** — with a focus on solving real-world problems in scientific domains.

My background in cognitive science shapes how I approach modeling: Instead of wildely experimenting with fancy models, I think about how the human brain would approach a given problem so that I can include carefully chosen inductive biases into the modeling pipeline that enable efficient extraction of meaningful signals.

---

## 🛠 Technical Focus

- Deep learning with PyTorch  
- Computer vision (classification, segmentation)  
- Handling imperfect / limited datasets  
- Training & evaluation pipelines  
- Experimentation and model iteration  

---

## 🚀 Featured Projects

### 🌱 Trichome Counter (Work in Progress)
**Goal:** Automate counting of leaf trichomes to reduce manual lab work

- Fine-tuning a **U-Net** for trichome detection on plant leaf images  
- Using **heatmaps derived from point annotations** instead of segmentation masks  
- Tackling a **weak supervision problem**: learning from approximate locations  
- Pipeline: annotation processing → training → prediction → counting  

**Key Challenge:**  
The dataset provides only *rough coordinate annotations*, not segmentation masks.  
This requires learning from **probabilistic spatial signals** instead of precise pixel labels.

---

### 🔬 Cell Tissue Classifier
**Goal:** Classify tissue type from microscopy images

- Fine-tuned **ResNet-50** on a small dataset  
- Focus on **transfer learning** and **overfitting mitigation**  
- Applied augmentation, regularization, and careful validation  

**Key Challenge:**  
- **Limited data** → high overfitting risk  
- **Limited domain knowledge** → reliance on robust training strategies  

---


## 🤖 A note on AI usage

I use generative AI tools as supportive development aids, mainly for documentation, discussing ideas, and verifying implementation approaches. 

However, I intentionally focus on designing and implementing projects largely myself in order to build hands-on experience with project structure, debugging, experimentation, and model development.


While modern AI tools can accelerate development significantly, I believe understanding the underlying systems and being able to reason about implementation decisions independently remains essential for building reliable machine learning solutions.

---

## 📫 Contact

- LinkedIn: https://www.linkedin.com/in/adrianwelter/