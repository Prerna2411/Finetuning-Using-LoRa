# Fine-tuning DistilBERT with LoRA

This repository demonstrates **parameter-efficient fine-tuning** of the [DistilBERT (uncased)](https://huggingface.co/distilbert-base-uncased) model using **LoRA (Low-Rank Adaptation)**.  
LoRA reduces the number of trainable parameters, making fine-tuning faster, cheaper, and more memory-efficient compared to full fine-tuning.

---

## 🚀 Features
- Fine-tunes **DistilBERT-base-uncased** using **LoRA adapters**  
- Built with **🤗 Hugging Face Transformers + PEFT**  
- Training and evaluation scripts included  
- Supports inference with the fine-tuned LoRA model  

---

🛠️ Requirements

Python 3.8+

PyTorch

Transformers

PEFT (Parameter-Efficient Fine-Tuning library)
----

Results-

It achieves the following results on the evaluation set:

Loss: 0.6438

Accuracy: 0.887

------
🔗 Model Checkpoints

👉  Fine-tuned model:Hugging Face Model Hub-https://huggingface.co/Prerna43/distilbert-base-uncased-lora-text-classification
