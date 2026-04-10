<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Text-to-Code%20Generation&fontSize=42&fontColor=00d9ff&fontAlignY=38&desc=LLMs%20%7C%20NLP%20%7C%20GPT-Neo%202.7B%20%7C%20LoRA%20Fine-Tuning&descAlignY=58&descSize=16&descColor=a78bfa" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&pause=1000&color=00D9FF&center=true&vCenter=true&width=750&lines=Transform+natural+language+into+Python+code+%F0%9F%A7%A0;Fine-tuned+GPT-Neo+2.7B+with+LoRA+%F0%9F%94%A5;BLEU+Score%3A+79.4+%E2%80%94+Trained+on+18K%2B+pairs+%F0%9F%8F%86;Real-time+Code+Generation+via+Flask+%F0%9F%9A%80" alt="Typing SVG" />

<br/><br/>

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co)
[![Flask](https://img.shields.io/badge/Flask-WebApp-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com)

[![GitHub stars](https://img.shields.io/github/stars/arryansharma1/Text-to-Code-Generation?style=for-the-badge&color=f59e0b&labelColor=0d1117&logo=github)](https://github.com/arryansharma1/Text-to-Code-Generation/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/arryansharma1/Text-to-Code-Generation?style=for-the-badge&color=00d9ff&labelColor=0d1117&logo=github)](https://github.com/arryansharma1/Text-to-Code-Generation/network)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge&labelColor=0d1117)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/arryansharma1/Text-to-Code-Generation?color=7c3aed&labelColor=0d1117&style=for-the-badge)](https://github.com/arryansharma1/Text-to-Code-Generation)

<br/>

> ### *"The best code is the code you don't have to write — just describe it."*

<br/>

📄 [View Full Documentation](https://github.com/aryansharma7341/Text-to-Code-Generation/blob/main/Documentation/Text_to_Code_Generator(Major_Project-01)_Group_Number_12.pdf)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Project Structure](#-project-structure)
- [Model Performance](#-model-performance)
- [Evaluation Insights](#-evaluation-insights)
- [Use Cases](#-use-cases)
- [Installation & Setup](#-installation--setup)
- [Contributors](#-contributors)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📌 Overview

<img align="right" width="280" src="https://media.giphy.com/media/zOvBKUUEERdNm/giphy.gif"/>

This project leverages **GPT-Neo 2.7B** to automatically generate Python code from natural language instructions. By fine-tuning on the **iamtarun/python_code_instructions_18k_alpaca** dataset, the model learns precise, contextual code generation from over 18,000 text-code pairs.

The system is optimized using **LoRA (Low-Rank Adaptation)** and **model quantization** — drastically reducing trainable parameters and computational cost without sacrificing output quality.

📄 For full methodology, refer to the [Documentation](https://github.com/aryansharma7341/Text-to-Code-Generation/blob/main/Documentation/Text_to_Code_Generator(Major_Project-01)_Group_Number_12.pdf).

<br clear="right"/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## ✨ Key Features

<div align="center">

| ⚡ Feature | 📋 Description |
|:---|:---|
| 🤖 **GPT-Neo 2.7B** | Fine-tuned large language model for Python code generation |
| 🔧 **LoRA Fine-Tuning** | Reduces trainable parameters by ~90% for efficient training |
| 📦 **Model Quantization** | Cuts memory usage and improves inference latency |
| 🌐 **Web Application** | Flask-based UI for real-time, interactive code generation |
| 📚 **18K+ Training Pairs** | Trained on diverse text-to-code instruction dataset |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🗂️ Project Structure

```
📦 Text-to-Code-Generation/
│
├── 📁 dataset_processing/
│   ├── preprocess_data.py
│   ├── dataset_statistics.py
│   └── tokenizer_setup.py
│
├── 📁 model_training/
│   ├── train_gpt_neo.py
│   ├── fine_tune_LoRA.py
│   ├── model_quantization.py
│   └── evaluation.py
│
├── 📁 inference/
│   ├── generate_code.py
│   ├── test_cases.py
│   └── performance_benchmark.py
│
├── 📁 web_application/
│   ├── app.py
│   ├── templates/
│   ├── static/
│   └── api.py
│
└── 📁 documentation/
    ├── model_architecture.md
    ├── dataset_details.md
    └── optimization_techniques.md
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📊 Model Performance

<div align="center">

| Model | Dataset | BLEU Score | Training Time | Status |
|:---:|:---:|:---:|:---:|:---:|
| 🏆 **GPT-Neo 2.7B (LoRA)** | Python_Code_18K | **79.4** | 8 hours | ✅ Best (local) |
| GPT-3.5 (API) | OpenAI Code Dataset | 82.1 | N/A | ☑️ Reference |
| CodeT5 | CodeSearchNet | 75.8 | 12 hours | ☑️ Tested |

</div>

<br/>

> 🏆 Our **fine-tuned GPT-Neo 2.7B with LoRA** achieves a **BLEU score of 79.4** — competitive with commercial API-based models while running fully locally with minimal compute.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🔍 Evaluation Insights

<div align="center">

| 🔎 Insight | 💡 Details |
|:---|:---|
| 📏 **BLEU Score** | Measures text similarity — not execution correctness |
| ⚙️ **LoRA Efficiency** | Reduces trainable parameters by ~90% vs full fine-tuning |
| 🚀 **Quantization** | Improves latency and cuts memory footprint significantly |
| 💬 **Prompt Quality** | Better-structured prompts yield higher-quality code output |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 💡 Use Cases

<div align="center">

| 🎯 Use Case | 📝 Description |
|:---:|:---|
| 🧑‍💻 **Beginner Coding** | Generate boilerplate code from plain English descriptions |
| 📚 **Education** | Help students learn by showing code for what they describe |
| ⚙️ **Script Automation** | Auto-generate utility scripts from task descriptions |
| 🧪 **Rapid Prototyping** | Quickly scaffold functions and modules for testing ideas |
| 🤖 **AI Coding Assistants** | Power next-gen developer tools and IDE plugins |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## ⚡ Installation & Setup

### Prerequisites

![Python](https://img.shields.io/badge/Python_3.8+-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![BitsAndBytes](https://img.shields.io/badge/BitsAndBytes-Quantization-7c3aed?style=flat-square)

### Steps

```bash
# 📥 Clone the repository
git clone https://github.com/arryansharma1/Text-to-Code-Generation.git

# 📂 Navigate into the folder
cd Text-to-Code-Generation

# 📦 Install dependencies
pip install -r requirements.txt

# 🚀 Run the web application
cd web_application
python app.py
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 👨‍💻 Contributors

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-arryansharma1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/arryansharma1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-arryansharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arryansharma/)
[![Email](https://img.shields.io/badge/Email-aryansharma7341.as@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aryansharma7341.as@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&text=Thanks+for+visiting!+%F0%9F%A4%96&fontSize=24&fontColor=00d9ff&fontAlignY=65"/>

<br/>

🌟 **If you find this project useful, don't forget to ⭐ the repository!**

![Visitor Count](https://komarev.com/ghpvc/?username=arryansharma1&color=00d9ff&style=for-the-badge&label=PROFILE+VIEWS)

</div>
