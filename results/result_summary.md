## 🧩 Results

### 🔹 1a. Adoption of Coding Agents on GitHub

Analysis of the **AIDEV dataset** (≈940K Agentic Pull Requests) shows that **AI coding agents are widely adopted by experienced developers**, not just newcomers.

- **Experience levels**
  - 🧠 Experienced developers (>5 yrs): **43.3%** of Agentic-PRs  
  - 🌱 Newcomers (<1 yr): **21.3%**
  - Median developer experience: **4.4 years**

This indicates broad integration of AI tools across the developer spectrum.

- **Agent usage**
  - **Codex:** 87.0%  
  - **GitHub Copilot:** 5.4%  
  - **Cursor:** 3.5%  
  - **Devin:** 3.2%  
  - **Claude Code:** <1%

Codex dominates adoption, largely due to strong GitHub and ecosystem integration.

- **Ecosystem trends**
  - **Top languages:** Python (27%), TypeScript (18.5%), JavaScript (15.9%)
  - **Project size:** 79% of Agentic-PRs come from repos with <100 stars

> **Insight:** AI-assisted coding is most prevalent in small-to-medium projects, especially those using Python and TypeScript.

- **Adoption pattern**
  - Newcomers favor **Codex** and **Cursor** for simpler onboarding.
  - Senior developers experiment with **Devin** or use **Copilot** for code support and documentation.

**Takeaway:**  
AI coding agents are becoming integral across all skill levels, but their strongest foothold remains in **lightweight, Python-centric repositories**.

---

### 🔹 1b. Practices Correlated with Agentic-PR Quality

Empirical results highlight several practices that **strongly correlate with PR quality and merge success**.

| Factor | Observation | Impact |
|:-------|:-------------|:--------|
| **PR Size** | <150 lines | ✅ Highest quality (0.695), 82% merge rate |
| **Commit Granularity** | 1 focused commit | ✅ +0.14 quality improvement |
| **Testing Practices** | Tests included | ✅ +7.7% higher merge success |
| **Description Length** | 200–500 chars | ✅ Best clarity-to-detail balance |
| **Task Type** | Docs, CI, style | ✅ Highest avg. quality (>0.67) |
| **Agent Differences** | Codex > Cursor > Devin | ✅ Codex avg. 0.69 quality |

- **Negative correlation:** Larger PRs and multiple commits (>5) lower review speed and acceptance.  
- **Positive correlation:** Including tests and concise, descriptive messages boosts both quality and merge likelihood.

A multivariate regression confirms that **commit message clarity, PR size, and test presence** are the most predictive of PR success (**R² = 0.083**).

**Practical Guidelines**
1. Keep PRs small and focused.  
2. Write clear, medium-length descriptions (200–500 chars).  
3. Include tests whenever possible.  
4. Use fewer, well-scoped commits.

> Following these practices improves PR quality, review speed, and merge success across ecosystems.

---

### ⚙️ Summary

- Experienced developers dominate AI agent adoption.  
- Codex remains the primary engine of Agentic-PRs.  
- High-quality PRs are **small, test-driven, and well-documented.**  
- Best practices derived here can guide future **developer-AI collaboration frameworks**.

---
