# Text-Summarizer-
AI-powered text summarization application using a pretrained Transformer model with Hugging Face Transformers and FastAPI.
# Text Summarizer
LIVE DEMO -http://127.0.0.1:8000
An AI-powered text summarization application that generates concise summaries from long text using a **pretrained Transformer model** from Hugging Face.

The application is built with **Python, Hugging Face Transformers, PyTorch, and FastAPI**.

## 🚀 Features

- 📝 Summarize long text into concise summaries
- 🤗 Uses a pretrained Transformer model
- ⚡ FastAPI-based backend
- 🧠 NLP-based text processing
- 💻 Simple web interface
- 🔄 Supports custom input text

## 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- FastAPI
- Jinja2
- HTML/CSS

## 📂 Project Structure

```text
Text_summarizer/
│
├── app.py
├── requirements.txt
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Navigate to the project folder

```bash
cd Text_summarizer
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

Start the FastAPI server using:

```bash
uvicorn app:app --reload
```

Then open the application in your browser:

```text
http://127.0.0.1:8000
```

## 🧠 How It Works

1. User enters a long piece of text.
2. The text is processed using a Hugging Face tokenizer.
3. The pretrained Transformer model generates a summary.
4. The generated summary is displayed to the user.

## 📌 Example

**Input:**

```text
Artificial Intelligence is a field of computer science that focuses
on creating systems capable of performing tasks that normally require
human intelligence...
```

**Output:**

```text
Artificial Intelligence focuses on creating systems that can perform
tasks requiring human intelligence.
```

## 📚 Learning

This project was created to understand the practical implementation of:

- Natural Language Processing (NLP)
- Tokenization
- Transformer architecture
- Pretrained models
- Hugging Face Transformers
- FastAPI
- Model inference

## 🔮 Future Improvements

- Add support for multiple languages
- Add text and document upload
- Improve the user interface
- Add summary length controls
- Deploy the application online

## 👨‍💻 Author

**Gyanendra Chauhan**

B.Tech – Artificial Intelligence & Machine Learning

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.
