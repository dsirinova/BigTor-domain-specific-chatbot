# BigTor: Development of a Domain-Specific Chatbot Using Synthetic Data and PEFT Techniques

**BigTor** is a domain-specific AI chatbot focused on Azerbaijani culture, history, society, and local knowledge.

## Overview

The project fine-tunes **DeepSeek-R1-Distill-Llama-8B** using synthetic Azerbaijani datasets and Parameter-Efficient Fine-Tuning techniques.

## Tech Stack

* DeepSeek-R1-Distill-Llama-8B
* LoRA / PEFT
* Unsloth
* TRL
* Weights & Biases
* Ollama
* FastAPI / Flask
* Vue.js
* PostgreSQL & MySQL

## Results

BigTorV1 was evaluated against Mistral-7B-Instruct:

| Metric                     |  BigTorV1 | Mistral-7B |
| -------------------------- | --------: | ---------: |
| Azerbaijani Music Accuracy |   **92%** |        45% |
| Cultural Context Accuracy  |   **94%** |        47% |
| Language Quality           | **4.7/5** |      3.2/5 |

## Goal

To demonstrate that efficient fine-tuning and synthetic data can create powerful AI systems for culturally and linguistically underrepresented domains.

## Future Work

* Multilingual support
* RAG integration
* Multimodal capabilities
* Larger-scale evaluation

## Author

**Dunya Shirinova**
MSc Data Science & Artificial Intelligence
