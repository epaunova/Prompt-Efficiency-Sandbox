# ⚙️ Prompt Efficiency Sandbox

This project compares different prompt engineering strategies by measuring:

- ⏱️ Latency
- 📦 Token usage
- 🧠 Output quality

It helps identify which prompts are more efficient and effective when interacting with large language models (LLMs) — balancing cost, speed, and clarity.

---

## 🧠 Prompt Variants Tested

1. **Simple Prompt**  
   _"Summarize the French Revolution."_

2. **Instructional Prompt**  
   _"Please provide a concise and well-structured summary of the key events and consequences of the French Revolution in under 100 words."_

3. **Chain-of-Thought Prompt**  
   _"Let's think step by step. First, outline the causes... Then describe key events... Finally, summarize outcomes."_

---

## 📊 Metrics Captured

- `Latency (s)` – simulated response time
- `Tokens Used` – simulated output length
- `Output Quality` – scored on a 0.0–1.0 scale

All values are mocked for reproducibility, but the structure can be adapted for real LLM calls via OpenAI or other APIs.

---

## 📂 Project Structure

prompt-efficiency-sandbox/
├── scripts/ # Jupyter notebook and benchmark code
│ └── prompt_latency_comparison.ipynb
├── results/ # Evaluation logs, token counts, latency samples
├── models/ # Prompt templates, prompt-style configs
├── evals/ # Manual or automated quality scoring
└── README.md

yaml
Copy
Edit

---

## 📓 Run the Notebook

```bash
cd scripts
jupyter notebook prompt_latency_comparison.ipynb
You’ll see:

Tabular comparison of 3 prompts

Bar charts for latency, token usage, and quality

🔗 Related Project
💡 For full-scale evaluation with GPT-assisted grading, check out my LLM Evaluation Toolkit

🧪 Note
This is a sandbox project to demonstrate prompt efficiency benchmarking. Can be extended with:

Real LLM API integration

Token tracking (via tiktoken)

Output evaluation pipeline (manual or model-based)

👤 Author
Eva Paunova
🔗 LinkedIn
📂 Portfolio
