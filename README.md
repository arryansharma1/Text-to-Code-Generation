<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:141e30,50:243b55,100:0f2027&height=220&section=header&text=Text-to-Code%20Generation&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=LLMs%20%7C%20NLP%20%7C%20Automated%20Python%20Code%20Generation&descAlignY=60&descSize=18&descColor=c9d1d9"/>

<br/>

[![Python](https://img.shields.io/badge/Python-3.8+-306998?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-EE4C2C?style=for-the-badge&logo=pytorch)](https://pytorch.org)
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-ffcc00?style=for-the-badge&logo=huggingface)](https://huggingface.co)
[![Flask](https://img.shields.io/badge/Flask-WebApp-000000?style=for-the-badge&logo=flask)](https://flask.palletsprojects.com)

<br/>

> <b>Transform natural language instructions into executable Python code using NLP & Large Language Models</b>

<br/>

📄 <a href="https://github.com/aryansharma7341/Text-to-Code-Generation/blob/main/Documentation/Text_to_Code_Generator(Major_Project-01)_Group_Number_12.pdf">Documentation</a>

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Model Performance](#-model-performance)
- [Evaluation Insights](#-evaluation-insights)
- [Use Cases](#-use-cases)
- [Installation & Setup](#-installation--setup)
- [Contributors](#-contributors)

---

<h2>📌 Overview</h2>

<p>
  This project leverages <strong>GPT-Neo 2.7B</strong> to automatically generate Python code from text-based instructions. 
  By fine-tuning the model with the <strong>iamtarun/python_code_instructions_18k_alpaca dataset</strong>, we enable precise 
  and contextual code generation.
</p>

<p>
  The system is optimized using <strong>LoRA (Low-Rank Adaptation)</strong> and <strong>model quantization</strong> 
  to ensure efficient training and inference with reduced computational cost.
</p>

---

<h2>✨ Key Features</h2>

<ul>
  <li>🔹 Fine-tuned <strong>GPT-Neo 2.7B</strong> for optimized code generation</li>
  <li>🔹 Utilizes <strong>LoRA (Low-Rank Adaptation)</strong> for efficient fine-tuning</li>
  <li>🔹 <strong>Model Quantization</strong> for reduced computational requirements</li>
  <li>🔹 <strong>Web Application</strong> for real-time code generation</li>
  <li>🔹 Trained on a dataset of <strong>18,000+ text-code pairs</strong></li>
</ul>

---

## 🛠️ Project Structure

<pre>
📂 Text-to-Code-Generation
│
├── 🗂️ dataset_processing
│   ├── preprocess_data.py
│   ├── dataset_statistics.py
│   ├── tokenizer_setup.py
│
├── 🏗️ model_training
│   ├── train_gpt_neo.py
│   ├── fine_tune_LoRA.py
│   ├── model_quantization.py
│   └── evaluation.py
│
├── 🚀 inference
│   ├── generate_code.py
│   ├── test_cases.py
│   └── performance_benchmark.py
│
├── 🌐 web_application
│   ├── app.py
│   ├── templates/
│   ├── static/
│   └── api.py
│
└── 📖 documentation
    ├── model_architecture.md
    ├── dataset_details.md
    ├── optimization_techniques.md
</pre>

---

## 📊 Model Performance

<table>
  <tr>
    <th>Model</th>
    <th>Dataset</th>
    <th>BLEU Score</th>
    <th>Training Time</th>
  </tr>
  <tr>
    <td><b>GPT-Neo 2.7B (LoRA Fine-Tuned)</b></td>
    <td>Python_Code_Instructions_18K</td>
    <td><b>79.4</b></td>
    <td>8 hours</td>
  </tr>
  <tr>
    <td>GPT-3.5 (API-based)</td>
    <td>OpenAI Code Dataset</td>
    <td>82.1</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>CodeT5</td>
    <td>CodeSearchNet</td>
    <td>75.8</td>
    <td>12 hours</td>
  </tr>
</table>

<p>🔹 <strong>Fine-tuned GPT-Neo achieved a BLEU score of 79.4</strong>, demonstrating strong performance.</p>

---

## 🔍 Evaluation Insights

- BLEU score measures **text similarity**, not execution correctness  
- LoRA reduces **trainable parameters significantly (~90%)**  
- Quantization improves **latency and memory efficiency**  
- Better prompts → better generated code  

---

## 💡 Use Cases

- 🧑‍💻 Code generation for beginners  
- 📚 Educational assistance  
- ⚙️ Script automation  
- 🧪 Rapid prototyping  
- 🤖 AI coding assistants  

---

## ⚡ Installation & Setup

<h3>🛠 Prerequisites</h3>
<ul>
  <li>✅ Python 3.8+</li>
  <li>✅ PyTorch</li>
  <li>✅ Hugging Face Transformers</li>
  <li>✅ Flask</li>
  <li>✅ BitsAndBytes</li>
</ul>

<h3>🚀 Steps</h3>

<pre>
# Clone repository
git clone https://github.com/aryansharma7341/Text-to-Code-Generation.git

cd Text-to-Code-Generation

pip install -r requirements.txt

cd web_application
python app.py
</pre>

---

<h2>👨‍💻 Contributors</h2>

<div align="left">

[![GitHub](https://img.shields.io/badge/GitHub-arryansharma1-181717?style=for-the-badge&logo=github)](https://github.com/arryansharma1)<br /><br />
[![LinkedIn](https://img.shields.io/badge/LinkedIn-arryansharma-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/arryansharma/)<br /><br />
[![Email](https://img.shields.io/badge/Email-aryansharma7341.as%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aryansharma7341.as@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:243b55,100:141e30&height=120&section=footer"/>

🌟 <strong>If you find this project useful, don't forget to ⭐ the repository!</strong>

</div>
