# 🤖 Nano R1 – A Lightweight Reasoning AI Model

**Nano R1** is a compact AI project inspired by the architecture of R1, designed to perform basic reasoning tasks using **reinforcement learning**. This project demonstrates how a minimal model can be trained from scratch to perform decision-making and reasoning using a simplified environment.

---

## 🧠 Core Idea

The goal of Nano R1 is to explore how reinforcement learning agents can learn logical or step-by-step reasoning behaviors, even with limited resources and a simplified architecture.

---

## 🚀 Features

- 📚 Trains on **GSM8K** (Grade School Math 8K) dataset
- 🧠 Trained using **Reinforcement Learning (RL)**
- 🧮 Performs step-by-step reasoning to solve math problems
- 🔬 Compact model size suitable for low-resource training
- 📈 Basic reward feedback loop for learning
- 📦 Modular code structure for ease of experimentation

---

## 📚 Tech Stack

- 🐍 Python
- 🧠 TensorFlow / PyTorch (whichever you used)
- 📊 NumPy
- 🤖 Hugging Face Datasets

---
base_model: unsloth/Qwen2.5-3B-Instruct-unsloth-bnb-4bit
library_name: peft
license: apache-2.0
pipeline_tag: text-generation
language:
- en
tags:
- unsloth
- grpo
- trl
- transformers
- qwen2.5
- text-generation-inference
- PyTorch
- gsm8k
---


### Model Description




- **Developed by:** Jeesan Abbas
- **License:** Apache license 2.0
- **Finetuned from model:** unsloth/Qwen2.5-3B-Instruct-unsloth-bnb-4bit

## 🙋‍♂️ Author
Made with ❤️ by Jeesan Abbas
