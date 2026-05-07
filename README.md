# 🧪 Toxic Comment Classifier
A lightweight NLP model that detects toxic and offensive language in user comments.

## ⭐ Overview
This project fine-tunes DistilBERT on the Kaggle Toxic Comment dataset to classify whether text contains abusive language.
The model is served through a Gradio interface and packaged with Docker.

## 🔍 Features
- DistilBERT fine-tuned model
- Web UI with Gradio
- Docker-ready
- Training notebook included

## 🚀 Run with Docker

docker pull nishchithabk/toxic-comment-classifier:latest
docker run -p 7860:7860 nishchithabk/toxic-comment-classifier:latest


Visit: http://localhost:7860

## ▶️ Run Locally

pip install -r requirements.txt
python app/app.py


## 📁 Structure

app/
model/
notebooks/
requirements.txt
Dockerfile
README.md


## 📊 Dataset
- Kaggle Toxic Comment Classification dataset
- Not included — must download separately

## 🛡 Ethical Use
For learning purposes only — not production moderation.

## 👨‍💻 Author
Nishchitha B K (CSE-AIML)

