<h1 align="center">Hi, I'm Prerak Patel 👋</h1>

<h3 align="center">
AI/ML Engineer | Python Developer | Deep Learning, XAI, Forecasting, and HPC
</h3>

<p align="center">
  <a href="mailto:patel.prerak2798@gmail.com">Email</a> •
  <a href="https://www.linkedin.com/in/prerakpatel51020021998/">LinkedIn</a> •
  <a href="https://github.com/prerakpatel51">GitHub</a>
</p>

---

## About Me

I’m a graduate student in **Computer Engineering at Florida Institute of Technology** with experience building **deep learning systems, explainable AI pipelines, forecasting models, and geospatial machine learning applications**.

My work sits at the intersection of:

- **Explainable AI**
- **Climate and weather forecasting**
- **Remote sensing and satellite/radar data**
- **Diffusion and latent diffusion models**
- **High-performance computing**
- **Python-based ML systems**

I’m currently working on research involving **flash flood prediction, climate nowcasting, generative modeling, and scalable multi-GPU training workflows on HPC clusters**.

---

## Featured Projects

### 🔹 PKCast: Probabilistic Radar Nowcasting with VAE and Conditional Flow Matching

Developed **PKCast**, a PyTorch-based probabilistic radar nowcasting system for the **SEVIR VIL dataset** that predicts future storm activity from historical radar sequences.

- Built a **VAE-style autoencoder** to compress radar frames into latent representations
- Generated large-scale **HDF5 latent datasets** for efficient model training
- Trained a **Conditional Flow Matching forecasting model** using a **Cuboid Transformer UNet backbone**
- Implemented distributed training workflows for scalable GPU training
- Added **MLflow experiment tracking**, checkpointing, and streaming nowcasting metrics
- Generated inference outputs including **GIFs, NPZ files, and Cartopy-based visualizations**
- Created **Slurm scripts** for HPC-based training and experimentation

[Repository](https://github.com/prerakpatel51/Pkcast.git)

---

### 🔹 Context-Shift XAI Analysis

Built an explainable AI research pipeline to analyze how deep learning models behave when visual context changes between training and evaluation environments.

- Studied model reasoning under **context shift and distribution shift**
- Compared explanation behavior across different input conditions
- Used XAI methods to inspect whether the model focuses on meaningful object evidence or misleading contextual shortcuts
- Designed experiments to evaluate explanation quality, robustness, and model reliance on visual context
- Focused on understanding **trustworthiness, shortcut learning, and explanation stability**

[Repository](https://github.com/prerakpatel51/Context-shift-XAI-analysis.git)

---

### 🔹 Cross-Domain Attribution Analysis under Domain Shift

Built a cross-domain XAI pipeline on **DomainNet** using **ResNet-152** to study model behavior under distribution shift across **real** and **sketch** domains.

- Compared **Grad-CAM, Grad-CAM++, Integrated Gradients, and LIME**
- Evaluated explanations using **stability, faithfulness, cross-domain consistency, and representation behavior**
- Found that **sketch-trained models learned more transferable, shape-based features**, while **real-trained models showed stronger texture bias under shift**
- Focused on whether explanations remain trustworthy when inputs shift away from the training distribution

[Repository](https://github.com/prerakpatel51/xai_cross_domain_attribution_analysis)

---

### 🔹 3D Variational Autoencoders for Satellite IMERG and IR Data

Designed and trained **3D β-VAE models** on HPC clusters for large-scale satellite data compression and climate modeling.

- Processed large-scale **IMERG precipitation and IR satellite datasets**
- Built preprocessing workflows for spatiotemporal geospatial data
- Trained VAE models for compact latent representation learning
- Supported downstream climate nowcasting and flash flood prediction research
- Worked with multi-GPU training workflows on Slurm-based HPC infrastructure

---

### 🔹 Satellite Image Segmentation for Environmental Monitoring

Built a **U-Net-based segmentation system** for satellite imagery with an interactive web interface.

- Developed an end-to-end image segmentation pipeline
- Achieved strong segmentation performance for environmental monitoring tasks
- Reduced manual image analysis effort through automated land-use classification
- Built a user-facing interface for easier model interaction and visualization

[Repository](https://github.com/prerakpatel51/satellite-image-segmentor)

---

### 🔹 Rainfall Forecasting with STL Decomposition and Deep Learning

Developed rainfall prediction workflows using **STL decomposition**, **GRU**, and **multi-task GRU** models.

- Combined statistical decomposition with deep learning forecasting
- Built time-series forecasting pipelines for rainfall prediction
- Compared standard GRU and multi-task GRU modeling approaches
- Focused on improving temporal pattern learning in rainfall data

[Repository](https://github.com/prerakpatel51/Rainfall_prediction_using_STL_decomposition_GRU_MTGRU_)

---

## Tech Stack

**Languages:**  
Python, C++, Java, SQL, JavaScript

**Machine Learning / Deep Learning:**  
PyTorch, TensorFlow, Keras, Scikit-learn, Captum, OpenCV

**Data and Scientific Computing:**  
NumPy, Pandas, Matplotlib, Plotly, SciPy, Statsmodels, HDF5, Xarray

**Web and Backend:**  
Django, REST APIs, Redis, PostgreSQL, HTML, CSS, Bootstrap

**Infrastructure and Deployment:**  
Git, Docker, Kubernetes, AWS, Gradio, Slurm, HPC Clusters, MLflow

**Domains:**  
Explainable AI, Forecasting, Geospatial Data Processing, Remote Sensing, Variational Autoencoders, Diffusion Models, Time-Series Analysis

---

## Research and Interests

I’m especially interested in:

- Trustworthy and explainable deep learning
- Climate AI and weather nowcasting
- Scientific machine learning
- Diffusion models and generative modeling
- Remote sensing and geospatial intelligence
- Scalable training on GPU and HPC infrastructure

---

## Current Focus

- Building robust forecasting systems for real-world climate applications
- Studying how deep learning models behave under domain shift and context shift
- Designing efficient training pipelines for large-scale spatiotemporal data
- Applying XAI methods to understand model reasoning in high-impact ML systems

---

## Connect With Me

- **Email:** patel.prerak2798@gmail.com
- **LinkedIn:** <a href="https://www.linkedin.com/in/prerakpatel51020021998/">Prerak Patel</a>
- **GitHub:** <a href="https://github.com/prerakpatel51">prerakpatel51</a>

If you're working on **AI/ML, forecasting, XAI, climate AI, or geospatial deep learning**, I’d be happy to connect.
