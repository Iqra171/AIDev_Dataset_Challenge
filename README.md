# AIDev_Dataset_Challenge
# Adoption and Practices of Coding Agents on GitHub using the AIDEV Dataset

## 🧠 Overview
This project investigates the adoption patterns and practices of **AI Coding Agents** (such as GitHub Copilot, Devin, Codex, Cursor, and Claude Code) in real-world software development. Using the **AIDEV dataset**—a large-scale collection of 932K agent-authored pull requests—we explore:
- Who adopts Coding Agents (newcomers vs. experienced developers)
- What practices correlate with the quality of Agentic Pull Requests (PRs)

This work contributes to understanding how Coding Agents shape modern software engineering and how developers can work effectively with AI teammates.

---

## 🗂️ Repository Structure
```
📂 Q2-Adoption-Practices/
 ┣ 📜 Q2.ipynb                # Main analysis notebook
 ┣ 📜 requirements.txt         # Dependencies
 ┣ 📜 README.md                # Documentation
 ┣ 📂 data/                    # (optional) subset or sample of dataset
 ┣ 📂 results/                 # plots, tables, metrics
 ┣ 📜 LICENSE (optional)
 ┗ 📜 report.pdf (optional summary)
```

---

## ⚙️ Requirements
Install the dependencies before running:
```bash
pip install -r requirements.txt
```

Example `requirements.txt`:
```
nbformat==5.10.4
nbconvert==7.16.6
pandas>=2.0
matplotlib>=3.8
seaborn>=0.13
scikit-learn>=1.4
```

---

## ▶️ How to Run

### Option 1 – Google Colab
1. Open the notebook in [Google Colab](https://colab.research.google.com).
2. Upload the `Q2.ipynb` file.
3. Run all cells sequentially.

Dataset access:
- [AIDEV Dataset on Hugging Face](https://huggingface.co/datasets/hao-li/AIDev)
- [Zenodo DOI: 10.5281/zenodo.16919051](https://doi.org/10.5281/zenodo.16919051)

---

## 📊 Key Results
- **Adoption Analysis:** Patterns by developer experience and repository maturity.
- **Practice Correlations:** Metrics like PR size, task type, and commit granularity analyzed for their impact on PR quality.
- Visualizations of adoption trends, developer engagement, and repository-level variations are provided in the `results/` folder.

---

## 🔁 Reproducibility Notes
- Random seed values (if used) are fixed in the notebook for consistent results.
- All data transformations are documented in code cells.
- Environment: Python 3.10, Jupyter/Colab, nbformat 5.10.4.

---

## 👩‍💻 Author
**Iqra Zafar**  
GitHub: [Iqra171](https://github.com/Iqra171)

---

## 🧩 Supplemental Project Materials

| Type | File | Description |
|------|------|--------------|
| **Notebook** | `Q2.ipynb` | Main analysis and visualizations |
| **requirements.txt** | — | List of dependencies |
| **Sample Data** | `data/sample_pull_requests.csv` | (Optional) small dataset subset |
| **Plots / Results** | `results/adoption_trends.png`, `results/pr_quality_table.csv` | Generated outputs |
| **Report / Summary** | `report.pdf` | Short written summary of findings |
| **LICENSE** | `LICENSE` | Usage terms |
| **README.md** | — | Main documentation (this file) |

---

## 🪪 Acknowledgment
This project uses the **AIDEV Dataset** introduced in:

> Hao Li, Haoxiang Zhang, Ahmed E. Hassan.  
> *AIDev: Studying AI Coding Agents on GitHub.*  
> Queen’s University, Canada, 2025.  
> [Dataset on Hugging Face](https://huggingface.co/datasets/hao-li/AIDev) | [DOI: 10.5281/zenodo.16919051](https://doi.org/10.5281/zenodo.16919051)

---

## 📜 License

```
MIT License
Copyright (c) 2025 Iqra Zafar
```
