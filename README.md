Fine-Tuning a Lightweight LLM with LoRA

This project demonstrates parameter-efficient fine-tuning of a lightweight Large Language Model using LoRA (Low-Rank Adaptation) on a custom dataset. The goal of this project is to show how large language models can be adapted to specific tasks while using minimal computational resources.
The base model used is TinyLlama, and the implementation is built using the Hugging Face Transformers ecosystem. The entire pipeline is designed to run on Google Colab using limited GPU resources, making LLM experimentation accessible without expensive infrastructure.

Project Overview
Fine-tuning large language models traditionally requires significant computational power. This project uses LoRA adapters, which allow training only a small number of additional parameters while keeping the base model frozen. This approach significantly reduces memory usage and training time.
The model is trained on a small question–answer dataset and evaluated using an interactive prompt interface.

Features
Lightweight LLM fine-tuning
Parameter-efficient training using LoRA
Custom question–answer dataset
Interactive prompt-based testing
Compatible with Google Colab free GPU

Tech Stack
Python
PyTorch
Hugging Face Transformers
PEFT (LoRA)
Datasets
Google Colab

Example Prompts
Example questions used to test the fine-tuned model:
Question: What is machine learning? Answer:
Question: What is deep learning? Answer:
Question: What is overfitting in machine learning? Answer:
Question: What is RAG in artificial intelligence? Answer:

Project Workflow
Custom Dataset
      │
      ▼
Tokenization
      │
      ▼
Base Model (TinyLlama)
      │
      ▼
LoRA Adapter Training
      │
      ▼
Fine-Tuned Model
      │
      ▼
      
Interactive Question Answering
