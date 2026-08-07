# FakeDetect: AI-Driven Multimodal Fake News and Deepfake Detection System

<p align="center">
  <img src="images/homepage.png" width="900">
</p>

<p align="center">
An AI-powered multimodal system that detects <b>fake news</b>, <b>deepfake images</b>, and <b>deepfake videos</b> using BERT, EfficientNetB0, and Multimodal Fusion.
</p>

---

## Overview

FakeDetect is an AI-driven multimodal fake news and deepfake detection system designed to analyze **text, images, and videos**. Unlike traditional systems that focus on a single modality, FakeDetect combines predictions from multiple AI models to provide a more reliable and accurate final decision.

The system consists of:

- 📰 Fake News Detection using Fine-tuned BERT
- 🖼️ Deepfake Image Detection using EfficientNetB0
- 🎥 Deepfake Video Detection using EfficientNetB0 + OpenCV
- 🤖 Multimodal Fusion Layer
- 🔥 Grad-CAM Explainability
- 🌐 Interactive Streamlit Web Application

---

# Features

- Detects fake news articles and headlines
- Detects AI-generated and manipulated images
- Detects deepfake videos
- Supports multimodal inputs
- Confidence score prediction
- Grad-CAM visualization for explainability
- Simple Streamlit web interface

---

# System Architecture

<p align="center">
  <img src="images/system_architecture.png" width="950">
</p>

The system processes text, images, and videos independently before combining their prediction scores using a weighted multimodal fusion strategy.

---

# Technologies Used

| Category | Technologies |
|-----------|--------------|
| Programming | Python |
| Deep Learning | PyTorch, TorchVision |
| NLP | Hugging Face Transformers, BERT |
| Computer Vision | EfficientNetB0, OpenCV |
| Data Processing | Pandas, NumPy, NLTK |
| Visualization | Matplotlib, Seaborn |
| Explainability | Grad-CAM |
| Deployment | Streamlit |
| Development | Google Colab, Jupyter Notebook |

---

# Datasets

The project uses multiple publicly available datasets.

| Dataset | Purpose |
|----------|----------|
| Fake and Real News Dataset | Fake News Detection |
| LIAR Dataset | Fake News Classification |
| Deepfake vs Real Images (60K) | Image Detection |
| 140K Real and Fake Faces | Face Manipulation Detection |
| AI Generated vs Real Images | AI Image Detection |
| Real/Fake Video Dataset | Video Detection |

### Kaggle Dataset Links

- 🔗 Fake and Real News Dataset  
  https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

- 🔗 LIAR Dataset  
  https://www.kaggle.com/datasets/doanquanvietnamca/liar-dataset

- 🔗 Deepfake vs Real Images (60K)  
  https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images

- 🔗 140K Real and Fake Faces Dataset  
  https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces

- 🔗 AI Generated vs Real Images Dataset  
  https://www.kaggle.com/datasets/cashbowman/ai-generated-images-vs-real-images

- 🔗 Real/Fake Video Dataset  
  (Add your dataset link)

---

# Model Performance

| Model | Accuracy |
|--------|----------|
| BERT Fake News Detection | **99.13%** |
| EfficientNetB0 Image Detection | **92.34%** |
| EfficientNetB0 Video Detection | **99.89%** |
| Multimodal Fusion System | **92.34%** |

---

# Project Structure

```
FakeDetect/
│
├── app.py
├── requirements.txt
├── README.md
│
├── models/
│   ├── image_model_v3.pth
│   ├── video_model_v3.pth
│
├── notebooks/
│
├── images/
│   ├── homepage.png
│   ├── system_architecture.png
│
├── datasets/
│
├── Project_Report.pdf
├── FakeDetect_Presentation.pdf
```

---

# Installation

Clone the repository

```bash
git clone https://github.com/USERNAME/FakeDetect.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Streamlit

```bash
streamlit run app.py
```

---

# Download Large Files

Due to GitHub's file size limitations, the following files are hosted separately.

## Demo Video

📹

**Google Drive**

(Add Demo Video Link)

---

## Fine-tuned BERT Model

The fine-tuned BERT model exceeds GitHub's file size limit.

Download here:

(Add Google Drive Link)

After downloading,

place it inside

```
models/
└── bert_model/
```

---

# Applications

- Social Media Monitoring
- Journalism & Fact Checking
- Cybersecurity
- Digital Forensics
- Content Verification
- Online News Platforms

---

# Future Improvements

- Live social media monitoring
- Browser extension support
- Mobile application
- Real-time API integration
- Multilingual fake news detection

---

# Author

**Your Name**

Bachelor of Technology (Artificial Intelligence & Data Science)

Final Year Project

---

# License

This project is licensed under the MIT License.
