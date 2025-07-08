# LLM_Comparison_Project
LLM Comparison using ML &amp; Ensemble Learning
# 🧠 LLM Comparison using ML & Ensemble Learning

This project dives deep into evaluating Large Language Models (LLMs) using **machine learning classifiers**, **ensemble methods**, and a custom **composite scoring system** based on speed and latency.

Built fully in **Google Colab**, it explores model accuracy, performance tradeoffs, and which LLMs outperform others in practical use.

---

## 📌 Key Features

- ✅ ML models: **SVC**, **Decision Tree**, **Random Forest**, **Logistic Regression**
- 🔁 **Ensemble models**: Voting, Stacking, AdaBoost, GradientBoost
- ⚙️ Preprocessing: Feature scaling, normalization, polynomial features
- 📊 Accuracy comparison and visualization
- 🧠 Composite scoring combining **speed** & **latency** with tunable weights

---

````markdown
# 🔍 LLM Performance Analyzer with Ensemble Learning

A powerful, plug-and-play Google Colab notebook that compares Large Language Models (LLMs) based on **accuracy**, **latency**, **speed**, and **composite performance score**. Built with Ensemble Learning strategies to deliver data-driven insights for LLM selection.

---

## 📌 Overview

This project allows researchers and developers to evaluate multiple LLMs on a structured dataset, generating comparison plots and composite scores for:

- ✅ Model Accuracy
- 🚀 Inference Speed (tokens/sec)
- ⏱️ Latency (seconds)
- 🧠 Composite Score (Normalized)

No complex setup required—just upload your dataset and run the notebook in Google Colab.

---

## 📊 Output Previews

### 📈 Accuracy Comparison
<img src="https://raw.githubusercontent.com/SanikaSavade025/LLM_Comparison_ML/main/assets/model_accuracy.png" width="700"/>

### ⚖️ Composite Score Evaluation
<img src="https://raw.githubusercontent.com/SanikaSavade025/LLM_Comparison_ML/main/assets/composite_score_output.png" width="600"/>

---

## 🚀 Quick Start

### 🔗 Run in Colab  
> [Click here to open in Google Colab](https://colab.research.google.com/)

### 📂 Upload Your LLM Dataset  
When prompted in the notebook, upload your `.csv` dataset:

```python
from google.colab import files
files.upload()
````

### ▶️ Run All Cells

Let the notebook do the work: it will generate visualizations, compute composite scores, and highlight the top-performing LLMs.

---

## 🛠️ Built With

* 🐍 **Python**
* 📚 **Scikit-learn**, **Pandas**, **Matplotlib**
* 📊 **Ensemble Learning** (Weighted Scoring)
* ☁️ **Google Colab** (Zero setup execution)

---

## 📁 Dataset Format

Your input CSV should contain at least the following columns:

| Model    | Accuracy | Speed (tokens/sec) | Latency (sec) |
| -------- | -------- | ------------------ | ------------- |
| GPT-4    | 0.91     | 310                | 3.12          |
| Gemini-6 | 0.89     | 292                | 3.17          |
| Claude   | 0.87     | 250                | 2.90          |

*Additional fields like cost can be added if desired.*

---

## 🧠 Composite Scoring Logic

We normalize and combine metrics using this formula:

```
Composite Score = w1 * normalized_accuracy 
                + w2 * normalized_speed 
                - w3 * normalized_latency
```

You can customize the weights `w1`, `w2`, and `w3` inside the notebook based on your priorities (e.g., favoring accuracy over speed).

---

## 🌟 Features

* 📤 Easy dataset upload
* 📈 Auto-generated comparison plots
* 🧮 Weighted scoring system
* 🔁 No code changes required – just run!

---

## 📄 License

This project is licensed under the MIT License
© 2025 Sanika Savade

---

## 📬 Contact

For queries, reach out via GitHub or email: `sanikasavade025@gmail.com`

```

Let me know if you’d like:
- A matching `notebook.ipynb` file template.
- Automatic CSV format validator.
- Deployment on GitHub with link setup.
```


✨ Author
Made with ❤️ by Sanika Savade
🎓 Final Year CSIT | ML Enthusiast | Future Engineer
📧 sanikasavade@gmail.com
