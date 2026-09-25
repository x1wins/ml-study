# 🤖 ML Study — AI/ML Learning Path

A beginner-friendly, self-contained set of guides covering the math, code, and concepts
you need to become an AI/ML developer. Every page explains the *why*, includes diagrams,
and (where useful) runnable Python code.

**🌐 Live site:** https://x1wins.github.io/ml-study/

---

## 📚 Guides

| # | Topic | What it covers |
|---|-------|----------------|
| 1 | [Math Foundations](math-foundations.html) | Linear algebra, calculus, gradients, probability |
| 1a | [Euler's Number e](euler-number.html) | What e is, compounding, why AI uses it (softmax/sigmoid) |
| 1b | [Derivatives](derivatives.html) | Differentiation: slope, rules, partials, gradient, chain rule |
| 1c | [Integration](integration.html) | Area under a curve, fundamental theorem, probability/AUC |
| 1d | [Logarithms](logarithms.html) | Inverse of exponentials, ln, log rules, log-likelihood & cross-entropy |
| 1e | [Trigonometry](trigonometry.html) | sin/cos/tan, unit circle, transformer positional encoding |
| — | [Math Quiz](math-quiz.html) | Interactive self-check on e, derivatives, integration |
| 2 | [Programming](programming.html) | Python, NumPy, Pandas, Jupyter |
| 3 | [Neural Networks](neural-networks.html) | Weights, bias, activation, backpropagation |
| 4 | [Loss Functions](loss-functions.html) | MSE/MAE, cross-entropy, why loss drives learning |
| 5 | [Training & Optimization](training-optimization.html) | SGD, momentum, Adam, learning rate, overfitting |
| 6 | [CNNs](cnn.html) | Convolution, filters, pooling, feature maps |
| 7 | [RNNs & LSTMs](rnn-lstm.html) | Sequences, hidden state, vanishing gradients, gates |
| 8 | [Transformers](transformers.html) | Self-attention (Q/K/V), multi-head, positional encoding |
| 9 | [Prompt Engineering](prompting.html) | Zero/few-shot, roles, chain-of-thought |
| 10 | [RAG](rag.html) | Embeddings, vector search, grounding LLMs on your data |
| 11 | [Fine-Tuning](fine-tuning.html) | Full vs LoRA/QLoRA (PEFT), data prep, RAG vs fine-tuning |
| 12 | [Tools & Frameworks](tools-frameworks.html) | scikit-learn, PyTorch/TensorFlow, Hugging Face |
| 13 | [ML Workflow](ml-workflow.html) | Data → train → evaluate → deploy → monitor |
| 14 | [Evaluation Metrics](evaluation-metrics.html) | Accuracy, precision/recall, F1, ROC/AUC, regression metrics |
| 15 | [Ethics & Safety](ethics-safety.html) | Bias & fairness, privacy, responsible AI |

## 🪜 The LLM ladder

When prompting isn't enough, climb only as far as you need:

**Prompting → RAG → Fine-tuning**

- Need better output? → **Prompt** first (free, instant)
- Need knowledge / fresh facts? → **RAG** (low setup)
- Need consistent behavior/format/skill? → **Fine-tune** (high setup)

## 🛠️ Tech

- Plain, dependency-free **HTML/CSS** (dark theme), inline **SVG** diagrams.
- Hosted on **GitHub Pages** (`.nojekyll`, served from `main` branch root).
- Code examples use **Python + NumPy**; GPU/library-heavy snippets are marked *reference only*.

## 📖 How to use

Start at [`index.html`](index.html) (the learning path) and work top-to-bottom, or jump to any
topic via the sticky nav. Suggested order:

1. Learn Python → 2. Brush up on Math → 3. Classic ML → 4. Deep Learning → 5. Work with LLMs → 6. Build a project

---

*Created as an AI study journey. Contributions/notes welcome.* 🚀
