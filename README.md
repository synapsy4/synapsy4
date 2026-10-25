# 👋 Hi, I'm Adrian

**M.Sc. Cognitive Science** with a focus on **spatiotemporal modeling**.  
Interested in computer vision, applied deep learning with PyTorch, and end-to-end ML engineering.

---

## 🔍 About Me

I develop **end-to-end machine learning pipelines**, from data collection and preprocessing to model training, evaluation, and deployment-oriented development. My main focus is computer vision applications in scientific and real-world domains.

My background in cognitive science shapes how I approach modeling. Rather than relying on model complexity alone, I aim to identify useful inductive biases and structure learning problems to extract meaningful signals efficiently, especially when working with limited or imperfect data.

Alongside my computer vision projects, I have expanded my skills through MLOps training, with a growing focus on reproducible workflows, maintainable ML systems, and turning trained models into usable services.

## 🛠 Technical Focus

- Deep learning: PyTorch, transfer learning, pretrained models
- Computer vision: Object detection, classification, segmentation
- ML pipelines: Data processing, training, evaluation, prediction
- MLOps: Reproducible workflows and deployment-oriented ML development
- Data challenges: Limited datasets, imperfect annotations, overfitting mitigation
- Experimentation: Model iteration, validation, and performance analysis  

---

## 🚀 Featured Projects

### 🌱 Weed- and Crop-Detector (Work in Progress)
**Goal:** Develop a weed detection system for a deployable ML service.


- Applying pretrained **YOLO** models to a weed-and-crop dataset
- Building data, training and evaluation pipelines
- Adding a **prediction API** endpoint to make model inference accessible
- Progressively developing the project toward a maintainable, deployable service

---

### 🌿 Trichome Counter (Work in Progress)
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

I take a deliberate, review-driven approach to AI-assisted development. I continue to build hands-on engineering skills by designing systems, implementing core functionality, debugging, and evaluating models, while also experimenting with AI coding tools and agentic workflows.

I use these tools selectively for tasks such as exploring implementation approaches, supporting documentation, and automating repetitive development work. AI-generated code is reviewed before use, and I aim to understand the resulting implementation rather than treating generated output as a black box.

My goal is to combine independent engineering skills with effective AI-assisted workflows while maintaining ownership of the technical decisions, code quality, and behavior of the resulting systems.

---

## 📫 Contact

- LinkedIn: https://www.linkedin.com/in/adrianwelter/