# Live Ops Game Balance & Meta Analysis

## 📌 Project Overview
This project simulates a **Live Ops game balance analysis** commonly used in the gaming industry to maintain a fair and healthy competitive meta.  
By normalizing card statistics using **Damage per Elixir (DPE)** and **Health per Elixir (HPE)**, the project identifies **overpowered, underpowered, and balanced cards** and proposes data-driven balance changes.

The analysis mirrors real-world **game analytics and Live Ops workflows**, focusing on cost efficiency rather than raw stats.

---

## 🎯 Objectives
- Analyze offensive and defensive efficiency of game cards
- Detect balance anomalies using statistical thresholds
- Classify cards into balance categories
- Recommend balance actions (buffs, nerfs, cost changes)
- Present insights in a structured, developer-friendly format

---

## 📊 Dataset
- Card-level game statistics including:
  - Elixir cost
  - Damage per second
  - Health (including shields)
  - Card type

---

## 🧮 Metrics Used
### Damage per Elixir (DPE)

Represents **offensive efficiency**.

### Health per Elixir (HPE)
Represents **defensive efficiency**.

---

## 📐 Methodology
1. Data cleaning and numeric type validation  
2. Creation of a clean working dataset for efficiency metrics  
3. Calculation of DPE and HPE  
4. Statistical benchmarking using **mean ± standard deviation**  
5. Classification of cards into:
   - High / Normal / Low DPE
   - High / Normal / Low HPE
6. Balance diagnosis based on combined efficiency states
7. Generation of balance recommendations
8. Visualization of balance issue distribution

---

## 🧠 Balance Diagnosis Logic
| DPE | HPE | Diagnosis |
|----|----|----|
| High | High | Overpowered |
| Low | Low | Underpowered |
| High | Low | Glass Cannon |
| Low | High | Tanky but Weak |
| Normal | Normal | Balanced |

---

## 🛠 Suggested Balance Actions
- **Overpowered:** Nerf damage or increase elixir cost  
- **Underpowered:** Buff stats or reduce elixir cost  
- **Glass Cannon:** Reduce damage or increase survivability  
- **Tanky but Weak:** Increase damage output  
- **Balanced:** No change needed  

---

## 📈 Visualizations
- Bar chart showing distribution of balance diagnoses
- Highlights which balance categories require the most attention

---

## 🧰 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🚀 Key Takeaways
- Cost-normalized metrics are essential for fair balance evaluation
- Statistical thresholds provide objective balance detection
- The approach closely resembles real Live Ops decision-making
- The framework is extensible to other games or live balance systems

---

## 📎 Use Cases
- Game Analytics portfolios
- Live Ops / Game Designer collaboration
- Research-oriented game balance studies
- Entry-level Game Analyst demonstrations

---

## 👤 Author
**Anshika Rawat**  
Aspiring Game / Data Analyst

