# TP 3 Summary: Hugging Face, Unsloth, and LLM Fine-Tuning

In today's class, we explored the Hugging Face ecosystem, an efficient training tool called Unsloth, and the concept of fine-tuning Large Language Models (LLMs).

---

## Section 1: Hugging Face

Hugging Face is the central platform for open-source AI. It provides several core tools and services:

* **Models:** A large hub of pre-trained models (for text, image, and audio) that we can download and use directly.
* **Datasets:** Ready-to-use data collections for training, fine-tuning, and testing machine learning models.
* **Spaces:** A hosting service to deploy and share interactive AI web apps quickly using Gradio or Streamlit.
* **Buckets:** Cloud storage buckets used to store large files, model weights, and custom data safely.
* **Docs:** Official documentation and tutorials that explain how to use libraries like `transformers` and `datasets`.
* **Pricing:** Free for basic community use, with paid tiers for dedicated hardware, faster cloud GPUs, and enterprise features.

---

## Section 2: What is Unsloth?

Unsloth is an open-source library designed to make fine-tuning LLMs faster and use much less memory. It can train models like Llama, Mistral, and Gemma 2x to 5x faster and cuts memory (VRAM) usage by up to 80% without losing model accuracy. This allows developers to fine-tune modern LLMs even on budget or free GPUs like Google Colab.

---

## Section 3: Fine-Tuning LLMs

Fine-tuning is the process of taking a pre-trained base LLM—which already knows general grammar and knowledge—and training it further on a smaller, targeted dataset.

Instead of training a model from zero (which requires huge data and compute), fine-tuning adapts the model to perform a specific job, follow instructions better, or understand domain-specific topics such as medical diagnosis, legal advice, or customer support.
