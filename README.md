# 🧠 Finetuning on 5B Parameters on Custom Dataset – Microsoft Phi | LLM Fine-Tuning

## PEFT Fine-Tuning Project 🚀

Welcome to the **PEFT (Parameter-Efficient Fine-Tuning)** project! This repository focuses on **efficiently fine-tuning large language models (LLMs)** using **LoRA** and Hugging Face's **Transformers** library on a custom dataset. The target model is **Microsoft's Phi-2** model with **5 billion parameters**.

---

## 📌 Project Goals

- Fine-tune **Microsoft Phi-2 (5B parameters)** on a domain-specific/custom dataset.
- Use **LoRA (Low-Rank Adaptation)** for memory- and compute-efficient fine-tuning.
- Employ **PEFT** and **Hugging Face Transformers** libraries to streamline the process.

---
<!-- README.md -->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&width=500&lines=🚀+Finetuning+on+5B+Parameters;💻+Fine-Tuning+Microsoft+Phi-2;⚙️+PEFT+%7C+LoRA+%7C+Transformers" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://media.giphy.com/media/xT0Gqjs0y0iXc5Yw0s/giphy.gif" width="350" alt="finetuning gif" />
</p>

---

# 🧠 **Finetuning on 5B Parameters with Microsoft's Phi-2 – LLM Fine-Tuning**

Welcome to the **PEFT (Parameter-Efficient Fine-Tuning)** project! This repository is designed to efficiently fine-tune the **Microsoft Phi-2** model with **5 billion parameters** on a custom dataset using the power of **LoRA (Low-Rank Adaptation)** and Hugging Face’s **Transformers** library.

---

## 📌 **Project Goals**

- Fine-tune **Microsoft Phi-2 (5B parameters)** on a domain-specific/custom dataset.
- Leverage **LoRA (Low-Rank Adaptation)** for memory- and compute-efficient fine-tuning.
- Use **PEFT** and **Hugging Face Transformers** libraries to streamline and optimize the fine-tuning process.

---

## 📁 **Directory Structure**



## 📁 Directory Structure

```
.
├── dataset/                  # Custom dataset files
├── scripts/                 # Training and evaluation scripts
├── config/                  # LoRA and training configurations
├── outputs/                 # Model checkpoints and logs
├── README.md                # This file
```

---

## ⚙️ Tech Stack

- 🏗 **Model**: Microsoft Phi-2 (5B)
- 🧩 **Fine-Tuning Strategy**: LoRA (via `peft` library)
- 🧠 **Frameworks**: Hugging Face Transformers, Datasets, Accelerate
- 🚀 **Training**: Optimized for GPU environments (A100 recommended)

---

## 📝 Installation

```bash
git clone https://github.com/yourusername/Finetuning-on-5b-parameters-on-Custom_data_set-Microsoft-phi-.git
cd Finetuning-on-5b-parameters-on-Custom_data_set-Microsoft-phi-
pip install -r requirements.txt
```

---

## 🏃‍♂️ Quick Start

```bash
python scripts/train_lora.py \
  --model_name microsoft/phi-2 \
  --dataset_path ./dataset/custom_data.json \
  --output_dir ./outputs \
  --peft_config ./config/lora_config.json
```

---

## 🧪 Evaluation

Use the evaluation script to test your fine-tuned model:

```bash
python scripts/eval_model.py --model_dir ./outputs
```

---

## 📊 Results

| Metric       | Value     |
|--------------|-----------|
| Perplexity   | XX.XX     |
| F1 Score     | XX.XX     |
| Accuracy     | XX.XX%    |

*Note: Results depend on dataset quality and training duration.*

---

## 🧠 Acknowledgements

- Microsoft for the **Phi-2** model.
- Hugging Face for the **Transformers** and **PEFT** libraries.
- LoRA by Microsoft Research.

---

## 📄 License

This project is licensed under the MIT License.
.

