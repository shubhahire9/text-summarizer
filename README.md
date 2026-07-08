# 📝 Text Summarizer using Hugging Face Transformers

An AI-powered text summarization web application built using Hugging Face Transformers, FastAPI, and PyTorch. The application generates concise summaries from long text while preserving the key information.

---

## 🚀 Features

- Abstractive text summarization
- Built using Hugging Face Transformers (T5)
- FastAPI backend
- Simple and responsive web interface
- Uses a fine-tuned T5 model for generating summaries

---

## 🛠️ Tech Stack

- Python
- Hugging Face Transformers
- PyTorch
- FastAPI
- HTML
- CSS
- Jinja2

---

## 📂 Project Structure

```text
text_sum_app/
│
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
├── text_summarizer.ipynb
│
├── templates/
│   └── index.html
│
└── saved_summary_model/
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/shubhahire9/text-summarizer.git
cd text-summarizer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
uvicorn app:app --reload
```

Open your browser and visit:

```
http://127.0.0.1:8000
```

---
## Note

The trained model is not included in this repository because it exceeds GitHub's file size limit. Place the trained model inside the `saved_summary_model/` directory before running the application.

## 📸 Screenshots

Add screenshots of:

- Home page
- Input text
- Generated summary

Example:

```
screenshots/
├── home.png
└── summary.png
```

---

## 🔮 Future Improvements

- PDF summarization
- Document upload support
- Multi-language summarization
- Deploy on Hugging Face Spaces
- Deploy on Render

---

## 👨‍💻 Author

**Shubh Ahire**
