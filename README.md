# 🎩 Alfred - AI Butler Agent

An intelligent AI Agent built using Hugging Face's `smolagents` framework to help **Alfred** (Batman's butler) plan and schedule party preparations dynamically.

## 🌟 Features
- **Dynamic Task Scheduling:** Calculates party readiness time based on parallel/sequential prep tasks[cite: 1].
- **Custom Tools:** Integrates specialized tools (`suggest_menu`) for tailored menu recommendations[cite: 1].
- **Web Search Integration:** Powered by `DuckDuckGoSearchTool` for real-time query resolution[cite: 1].
- **Code Execution:** Uses `Qwen/Qwen2.5-Coder-32B-Instruct` to generate and run Python code safely[cite: 1].
- **Gradio UI:** Interactive web interface for seamless communication[cite: 1].

## 🛠️ Tech Stack
- **Framework:** `smolagents`[cite: 1]
- **LLM Engine:** `Qwen2.5-Coder-32B-Instruct` via HF Inference API[cite: 1]
- **Interface:** Gradio[cite: 1]
- **Language:** Python[cite: 1]

## 🚀 Live Demo
Check out the live interactive space on Hugging Face:
👉 [AlfredAgent Space](https://huggingface.co/spaces/abdallahkh1/AlfredAgent)[cite: 1]

## 📦 Installation & Setup
```bash
git clone [https://github.com/abdallahkhaled1/AlfredAgent.git](https://github.com/YOUR_USERNAME/AlfredAgent.git)
cd AlfredAgent
pip install -r requirements.txt
