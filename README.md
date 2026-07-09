# AI Operations & NLP Portfolio

Welcome! This repository showcases my engineering work at the intersection of Computational Linguistics and Workflow Automation.

---

## 📈 Project 1: BERT Sentiment Analysis Pipeline

### 🤖 Objective & Model Architecture
Adapted a pre-trained bidirectional encoder for binary sequence classification using `bert-base-uncased` (12-layer encoder, ~110M parameters). 

### 📊 Dataset & Metrics
* **Dataset:** Real-world Twitter Sentiment Stream.
* **Key Achievements:** Achieved a **66% accuracy** score and a **0.6610 F1-score**, successfully breaking previous baseline metrics.

### 🎛️ Evaluation Confusion Matrix
| Metric | Count |
| :--- | :--- |
| **True Positives** | 20 |
| **True Negatives** | 13 |
| **False Positives** | 8 |
| **False Negatives** | 9 |

---

## 🧠 Project 2: Sequence Classification using Causal Decoders (GPT-2)

### 🤖 Objective & Architecture
Forced a generative autoregressive language model (`gpt2`, ~548MB architecture) into a sequence classification task to evaluate uni-directional processing limitations.

### 🛠️ Engineering Takeaways & Fixes
* **The Challenge:** Documented the structural limitations of using uni-directional causal masking (left-to-right processing) for classification tasks compared to BERT's global bidirectional context window.
* **The Fix:** Engineered a custom tokenization fix for GPT-2's missing pad token by dynamically remapping it to the `<eos>` (End of Sequence) token.
* **Metrics:** Achieved **64% accuracy** and an **0.6195 F1-score**.

---

## 💼 Contact & Roles
I am an AI Operations Engineer & Master's Candidate in Computational Linguistics at the University of Ibadan. Open to remote AI/Ops internship and specialist roles.
