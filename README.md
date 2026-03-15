# Quamrul Hoda

**AI/ML Engineer · MLOps · LLM Systems**

I build end-to-end machine learning systems — from data pipelines to deployed APIs — with a strong focus on reproducibility, observability, and production readiness. I care deeply about closing the gap between experimentation and deployment, and I bring that discipline to every project I work on.

Based in Jalandhar, Punjab, India. Founder of **[Cognefy](https://www.cognefy.tech/)**, a technology studio focused on AI/ML application development and web products.

📬 [Gmail](qhoda489@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/quamrl-hoda/) &nbsp;·&nbsp; [DagsHub](https://dagshub.com/quamrl-hoda)

---

## Work

### AI English Tutor *(Active)* &nbsp;·&nbsp; [GitHub](https://github.com/quamrl-hoda/ai-english-tutor)
> Conversational tutoring service for Indian language speakers, built on FastAPI.

Designing an adaptive dialogue system that adjusts to a learner's native language context — Hindi, Bengali, and others. The architecture prioritizes low-latency responses and works within constrained network environments common in Tier-2 and Tier-3 Indian cities.

`FastAPI` `LLM APIs` `Python`

---

### Multi-Agent Article Generation System *(Active)* &nbsp;·&nbsp; [GitHub](https://github.com/quamrl-hoda/multi-agent-article-generator)
> Orchestrated multi-agent pipeline for automated research and content publishing.

Building with the Agno framework, routing requests through OpenRouter to Gemini models. Each agent handles a distinct role — research, drafting, editing — with inter-agent coordination managed at the orchestration layer. Target output is publishable Medium articles.

`Agno` `OpenRouter` `Gemini` `Python`

---

### Zomato Delivery Time Prediction &nbsp;·&nbsp; [GitHub](https://github.com/quamrl-hoda/zomato-delivery-time-prediction)
> End-to-end regression pipeline predicting food delivery ETAs with full MLOps infrastructure.

Built a modular ML pipeline using LightGBM with MLflow for experiment tracking, DVC for data and artifact versioning, and DagsHub as the remote backend. The project follows a strict `config → entity → component → pipeline` architecture, making it reproducible and maintainable. Served via a Flask REST API.

`LightGBM` `MLflow` `DVC` `DagsHub` `Flask` `Python` `uv`

---

### Swiggy Delivery Time Prediction &nbsp;·&nbsp; [GitHub](https://github.com/quamrl-hoda/swiggy-delivery-time-prediction)
> Production-style ML pipeline with Dockerized deployment and tracked model registry.

Similar in scope to the Zomato project but extended with Docker containerization for consistent deployment environments. Focused on model registry workflows — promoting the best experiment run to production via MLflow.

`LightGBM` `MLflow` `DagsHub` `Docker` `Flask` `Python`

---

### PlateVision — Automatic License Plate Recognition &nbsp;·&nbsp; [GitHub](https://github.com/quamrl-hoda/PlateVision)
> Real-time computer vision pipeline for vehicle plate detection and OCR.

Trained a YOLOv8 object detection model to localize license plates, then passed crops through Tesseract OCR for character recognition. DVC manages the preprocessing and training stages. Exposed as a Flask API for downstream integration.

`YOLOv8` `Tesseract OCR` `DVC` `Flask` `OpenCV` `Python`

---

### EmotionVision — Real-Time Facial Emotion Detection &nbsp;·&nbsp; [GitHub](https://github.com/quamrl-hoda/EmotionVision)
> Webcam-based emotion recognition system using deep learning on FER2013.

Integrated DeepFace with OpenCV for live inference from a webcam feed. Flask serves the interface with real-time frame processing. Trained and evaluated on the FER2013 multi-class emotion dataset.

`DeepFace` `OpenCV` `Flask` `FER2013` `Python`

---

## Technical Skills

**Machine Learning**
LightGBM, scikit-learn, YOLOv8, DeepFace, Transformers, feature engineering, model evaluation, regression, classification, computer vision

**MLOps & Infrastructure**
MLflow (experiment tracking, model registry), DVC (data & artifact versioning), DagsHub (remote storage & collaboration), Docker (containerization & deployment)

**LLM & Agent Systems**
Agno (multi-agent orchestration), OpenRouter, Gemini API, Anthropic Claude API, prompt engineering, agent role design

**Backend & APIs**
Flask, FastAPI, REST API design, Python, uv (package management)

**Engineering Practices**
Modular pipeline architecture (`config / entity / component / pipeline`), reproducible ML workflows, experiment versioning, Git, Linux

---

## Currently

- 🎯 Preparing for **ML Engineer / AI Engineer** roles — structured DSA study (Arrays, Two Pointers, Prefix Sum, Sliding Window), ML system design, and production project portfolio
- 🏗️ Building **Cognefy** — AI-powered products and web applications
- 📖 Deepening knowledge in RAG pipelines, vector databases, and RLHF fundamentals

---

## GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=quamrl-hoda&show_icons=true&theme=default&hide_border=true&count_private=true)
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=quamrl-hoda&layout=compact&hide_border=true)

---

*Open to full-time ML/AI Engineer roles, research collaborations, and interesting problems in production machine learning.*
