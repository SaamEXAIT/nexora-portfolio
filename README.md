# Nexora — 4-Year Portfolio Selection & Schedule  

[![View Live Report](https://saamexait.github.io/nexora-portfolio/)

---

### Executive Summary  
This portfolio transforms Nexora’s strategy into measurable action.  
Each selected project contributes uniquely to financial strength, sustainability, and organizational learning — no duplication, no waste.  
The optimization logic balances ambition and feasibility, turning abstract strategy into a verifiable sequence of results.

---

### Conclusion  
By aligning evidence with purpose, Nexora proves that strategic coherence and human-centered efficiency can coexist.  
The selected configuration is not a static plan, but a living system — adaptive, data-informed, and accountable to both performance and people.

---

### Project Overview  
- **Objective:** Develop one cohesive project portfolio that meets Nexora’s strategic goals while balancing financial return, sustainability impact, and workforce capacity.  
- **Methodology:** Greedy optimization under constraints (NPV ≥ 50 000 k€, Strategic Value ≥ 80, FTE ≤ 200), balanced weighting:  
  \[
  0.33 \times \text{NPV} + 0.33 \times \text{Strategic} + 0.34 \times \text{Sustainability} + 0.05 \times \text{Motivation} - 0.05 \times \text{FTE}
  \]
- **Outputs:**  
  - Interactive tables and plots  
  - 48-month Gantt schedule  
  - Correlation-based mutual exclusivity diagnostic  

---

### Reproduce Locally  
```bash
git clone https://github.com/SaamEXAIT/nexora-portfolio.git
cd nexora-portfolio
quarto render
