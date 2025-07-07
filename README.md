# PDF_Chatbot
# 🧠 PDF Chatbot with Local LLM (Phi-2)

Talk to any PDF using a free, local large language model — no OpenAI API key required!

---

## 📌 Overview

This project allows you to upload a PDF (like a resume, textbook, or notes), extract its content, and ask natural language questions about it. It uses microsoft/phi-2, a powerful open-source language model hosted on Hugging Face.

---

## 🚀 Features

- 🔍 Upload and extract text from PDFs
- 🤖 Ask questions using a local LLM (Phi-2)
- 🔐 No internet API or OpenAI key required
- ✅ Runs fully inside *Google Colab*
- ⚡ Works with GPU or CPU (GPU recommended)

---

## 🧰 Tech Stack

- [Transformers](https://huggingface.co/docs/transformers/index)
- [Hugging Face – Phi-2 Model](https://huggingface.co/microsoft/phi-2)
- [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/) (for PDF text extraction)
- Google Colab (for execution)

---

## 📂 How to Use

1. *Open the Colab Notebook*

   [🔗 Run in Google Colab](https://colab.research.google.com/drive/1E1QHLZh3SOY5KZnE4o1u6TnaWRZ0uY9J?usp=sharing)

2. *Steps in Notebook*
   - Install dependencies
   - Load the Phi-2 model from Hugging Face
   - Upload your PDF file
   - Extract the text
   - Ask your question in plain English

---

## 💡 Example Usage

```python
question = "What are the main projects mentioned in this resume?"
ask_question(question, pdf_text)
