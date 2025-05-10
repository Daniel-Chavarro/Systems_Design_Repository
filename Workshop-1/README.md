# Workshop 1 – Systemic Analysis of the Kaggle Competition "Drawing with LLMs"

This folder contains a **systemic analysis** of the Kaggle competition [Drawing with LLMs](https://www.kaggle.com/competitions/drawing-with-llms). The goal of this workshop is to understand and break down the components of a solution that leverages large language models (LLMs) to generate SVG drawings based on text prompts.

## 📊 Analysis Basis

The analysis was developed based on:

- The **public dataset** provided by the competition organizers.
- The **detailed competition description**, including the evaluation metric and example submissions.
- The **competitive nature** of the task, which aims to measure how effectively a system can generate SVGs that match human-like expectations, as judged by a comparison model.

## ⚙️ System Constraints

The solution must operate under several important constraints:

- **SVG limitations**: The competition imposes restrictions on the structure, size, and allowed elements within SVG files.
- **Notebook execution limits**: Submissions must run within a Kaggle Notebook, with restrictions on runtime and resources.
- **No internet access**: All models and data must be preloaded; dynamic downloads or API calls are not allowed during inference.

These constraints significantly impact system design, prompting the need for efficient, compact models and robust pre-processing strategies.

## 📁 Contents
- `Workshop 1.pdf` – Contains the system analysis of the competence 


## 📚 References

- Drawing with LLMs. (s. f.). *Kaggle*. [https://www.kaggle.com/competitions/drawing-with-llms](https://www.kaggle.com/competitions/drawing-with-llms)

---

Feel free to explore and contribute to the analysis!
