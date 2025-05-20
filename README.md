# ⚙️ Prompt Efficiency Sandbox

This project compares different prompt engineering strategies by measuring:

- ⏱️ Latency
- 📦 Token usage
- 🧠 Output quality

It demonstrates how prompt structure impacts performance, cost, and readability — essential for designing reliable LLM-based applications.

---

## 🧠 Prompt Variants Tested

1. **Simple Prompt**  
   `"Summarize the French Revolution."`

2. **Instructional Prompt**  
   `"Please provide a concise and well-structured summary of the key events..."`

3. **Chain-of-Thought Prompt**  
   `"Let's think step by step. First, outline the causes..."`

---

## 📊 Metrics Captured

| Metric         | Source                                 |
|----------------|----------------------------------------|
| Latency (s)    | Simulated, via `time.sleep()`          |
| Tokens Used    | Simulated integer range                |
| Output Quality | Manual scores (see `/evals`)           |

---

## 📁 Project Structure

prompt-efficiency-sandbox/
├── scripts/
│ └── prompt_latency_comparison.ipynb # Main notebook
├── results/
│ └── prompt_eval_results.csv # Latency + token metrics
├── models/
│ └── prompt_templates.json # Prompt definitions
├── evals/
│ └── manual_output_scores.md # Manual evaluation
└── README.md

yaml
Copy
Edit

---

## 📓 How to Run

```bash
cd scripts
jupyter notebook prompt_latency_comparison.ipynb
You’ll see:

Table with prompt efficiency comparison

Charts for latency, token count, and output quality

🔗 Key Files
📓 Example Notebook

📄 Prompt Templates

📊 Prompt Evaluation CSV

🧾 Manual Quality Scores

💡 Related Projects
✨ LLM Evaluation Toolkit — structured GPT-based output evaluation

👤 Author
Eva Paunova
🔗 LinkedIn
📂 Portfolio

