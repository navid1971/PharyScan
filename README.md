---
title: PharyScan
emoji: 🩺
colorFrom: blue
colorTo: green
sdk: docker
app_port: 7860
pinned: false
---

# PharyScan

PharyScan is an AI-powered Flask web app for pharyngitis screening using throat image analysis.

It uses a trained ResNet18 PyTorch model to classify images as:

- no_pharyngitis
- pharyngitis

The app also displays confidence scores through a professional medical-themed interface.

## Files

- `app.py` — Flask backend and model prediction API
- `pharyscan_web_app.html` — frontend web interface
- `requirements.txt` — Python dependencies
- `Dockerfile` — Docker setup for Hugging Face Spaces

## Run locally

```bash
pip install -r requirements.txt
python app.py