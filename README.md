# Sulat at Marka: Bilingual Automated Essay Scoring System

An automated, transformer-based essay scoring web platform developed to evaluate English, Tagalog, and Taglish argumentative essays on a **0–2 performance rubric scale** using a fine-tuned XLM-RoBERTa architecture.

## System Overview

* **Model Architecture:** Fine-tuned XLM-RoBERTa (Cross-Lingual Language Model)
* **Language Support:** English, Tagalog, and Taglish (Code-Switched)
* **Scoring Rubric Scale:**
  * **Bin 0 (Below Average):** Lacks clear structure, logical flow, or sufficient supporting evidence.
  * **Bin 1 (Average):** Demonstrates a clear argument with adequate organization and bilingual proficiency.
  * **Bin 2 (Above Average):** Shows sophisticated reasoning, strong evidence, and high structural coherence.
* **User Interface:** Interactive Gradio Web Application featuring real-time logit score visualization and bin classification.

---

## Gradio Web Interface & Test Cases

<p align="center">
  <h3>1. English Evaluation (Bin 2 - Above Average)</h3>
  <img src="Assets-Sulat-At-Marka/gradio-english-bin2.jpg" alt="Gradio English Evaluation" width="85%"/>
  <br><br>
  <h3>2. Tagalog Evaluation (Bin 1 - Average)</h3>
  <img src="Assets-Sulat-At-Marka/gradio-tagalog-bin1.jpg" alt="Gradio Tagalog Evaluation" width="85%"/>
  <br><br>
  <h3>3. Taglish Evaluation (Bin 0 - Below  Average)</h3>
  <img src="Assets-Sulat-At-Marka/gradio-taglish-bin0.jpg" alt="Gradio Taglish Evaluation" width="85%"/>
</p>

---

## Technical Features

* **Bilingual & Code-Switched Processing:** Optimized for multi-language essay evaluation without requiring separate pre-translation pipelines.
* **Real-time Logit Analytics:** Provides transparent debug metrics and performance meters alongside predicted scoring bins.
* **Gradio Web Integration:** Clean, responsive UI for input submission and visual performance tracking.
