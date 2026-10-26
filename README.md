# Sulat at Marka: Automated Multilingual Essay Scoring Application

Sulat at Marka is an automated essay evaluation system designed to grade student essays written in English, Tagalog, and Taglish. The project uses a fine-tuned multilingual transformer model to generate instant rubric-based scores.

---

## Overview

Checking and scoring essays manually takes a significant amount of time, especially when dealing with multilingual or code-switched text. This project was built to automate that process by evaluating essay structure, mechanics, and content clarity based on a standard 1 to 6 rubric scale.

---

## Tech Stack

- Primary Language: Python 3
- Machine Learning Frameworks: PyTorch, Hugging Face Transformers
- Model Architecture: XLM-RoBERTa (Fine-tuned)
- Data Processing: Pandas, NumPy
- User Interface: Gradio

---

## Key Features

- Multilingual Evaluation: Handles essays written in Tagalog, English, or Taglish using the fine-tuned XLM-RoBERTa model.
- Standardized Scoring: Maps text inputs to a 1-6 rubric scale for consistent grading.
- Interactive Interface: Built with Gradio so users can easily paste essay drafts and review scores instantly.

---

## How It Works

1. Essay Submission: The user inputs an essay into the Gradio interface.
2. Text Tokenization: The text is processed through the XLM-RoBERTa tokenization pipeline.
3. Scoring & Inference: The fine-tuned transformer model analyzes semantic structure and predicts the essay score.
4. Result Display: The calculated rubric score and score details are displayed on screen.

---

*Developed as an applied NLP and machine learning software project.*
