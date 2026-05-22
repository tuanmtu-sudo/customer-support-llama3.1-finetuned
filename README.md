# Customer Support AI Assistant - Fine-tuned Llama 3.1 8B

A domain-specific customer support chatbot fine-tuned from **Meta-Llama-3.1-8B-Instruct** using **QLoRA** (Unsloth).

This model is specialized in handling customer inquiries professionally and empathetically.

---

### 🚀 Live Demo
*(Add your Gradio public link here after launching)*

### 🏷️ Model on Hugging Face
[victor-tu-customer-support-llama3.1-8b](https://huggingface.co/victor-tu-customer-support-llama3.1-8b)

---

### 📋 Project Overview
- **Goal**: Adapt a general-purpose LLM into a specialized customer support agent
- **Base Model**: Meta-Llama-3.1-8B-Instruct
- **Fine-tuning Method**: QLoRA (4-bit quantization)
- **Dataset**: Bitext Customer Support LLM Training Dataset
- **Training Steps**: 100 steps (initial version)

---

### 🛠️ Technologies Used
- Unsloth (Fast fine-tuning)
- Hugging Face Transformers + PEFT + TRL
- PyTorch
- Google Colab (GPU)
- Gradio (Demo Interface)

---

### 📁 Repository Structure
