# 🤖 Mistral AI Assistant — Fine-tuned with Unsloth 🔥

🚀 One-shot fine-tuning of [Mistral-7B](https://huggingface.co/mistralai/Mistral-7B-v0.1) using [Unsloth](https://github.com/unslothai/unsloth) — blazing fast, memory-efficient, and fully open-source!  
🎯 Built to create your **own smart AI assistant**, trainable in minutes, and deployable anywhere (Hugging Face, local, or cloud).

---
- ✅ Cloning the repo
- ✅ Cleaning metadata widgets issues
- ✅ Running in Jupyter or Colab safely

---
## 📌 Features
- ✅ Single `.ipynb` file to **train & upload to Hugging Face**
- ✅ Based on `unsloth/mistral-7b-bnb-4bit`
- ✅ Instruction tuning format (prompt + response)
- ✅ Hugging Face integration (`push_to_hub`)
- ✅ Customizable for any task (chatbot, Q&A, support bot)

---

## 🧠 Model Info

| Property       | Value                                  |
|----------------|----------------------------------------|
| Base Model     | `unsloth/mistral-7b-bnb-4bit`          |
| Trainer        | 🤗 `transformers.Trainer`              |
| Fine-tuning    | LoRA + 4-bit quantization              |
| Use case       | Chat Assistant / Q&A / Task Agent      |
| Hugging Face   | [[aswin/mistral-ai-assist](https://huggingface.co/Aswinkumarr/Finetuned_mistral) *(after upload)* |

---

## 🧪 Run Notebook

1. Clone the repo:
```bash
git clone https://huggingface.co/Aswinkumarr/Finetuned_mistral
cd Finetuned_mistral
