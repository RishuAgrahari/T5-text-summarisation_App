# AI Text Summarizer Application 📝

A fast and efficient Text Summarizer Web Application built using **FastAPI** and Hugging Face's **T5 Model**.

## 🚀 Features
- **FastAPI Backend:** Lightweight and high-performance API processing.
- **Hugging Face T5 Model:** State-of-the-art Natural Language Processing (NLP) for abstractive text summarization.
- **Interactive UI:** Simple frontend interface built with HTML/JS.

## 🛠️ Project Structure
- `app.py`: FastAPI backend server.
- `text_summerizer.ipynb`: Model training and fine-tuning notebook.
- `index.html`: Web interface for summarizing text.
- `requirements.txt`: Python packages and dependencies.

## 💻 Local Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/RishuAgrahari/T5-text-summarisation_App.git](https://github.com/RishuAgrahari/T5-text-summarisation_App.git)
   cd T5-text-summarisation_App

2.Install Dependencies: pip install -r requirements.txt
3.Run the FastAPI Server: uvicorn app:app --reload
4.Access the Web App:Open your browser and navigate to http://127.0.0.1:8000

## ⚠️ Model Training & Hardware Note

- **Hardware Used:** Trained on **CPU** (No GPU/TPU used during local training).
- **Training Epochs Completed:** Currently trained for **2 Epochs**.
- **Recommended Epochs:** For optimal performance and precise summaries, fine-tuning for **6 Epochs** is strictly recommended. 

> *Note:* Higher epochs (up to 6) could not be executed locally due to CPU hardware constraints. Training can be further extended using GPU environments like Google Colab or Kaggle.

## ⚠️ Personal Recommendation & Model Training Note

* **Personal Recommendation:** Pehle aap 6 epochs tak data train karein, tabhi aapka model sahi response karega.
* **Current Model Status:** Maine laptop me CPU hone ke karan model ko sirf 2 epochs tak hi train kiya hai.
