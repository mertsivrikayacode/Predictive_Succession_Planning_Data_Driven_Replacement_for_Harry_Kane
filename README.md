# Predictive_Succession_Planning_Data_Driven_Replacement_for_Harry_Kane
An automated Python scouting pipeline using FBref data to isolate elite under-25 successors for Harry Kane. It applies linear regression and style quadrant modeling (xG vs xA) to filter global stars, delivering a balanced risk-reward transfer audit that contrasts premium targets (Sesko) against high-value buy-low assets (Gimenez).

# 📊 Data-Driven Succession Planning: Replacing Harry Kane via Predictive Recruitment Analytics

## 🎯 Executive Project Overview
Replacing a 'Complete 9' like **Harry Kane** is one of the most complex financial and tactical challenges in modern football. A complete forward must simultaneously sustain elite expected goals (xG) while dropping deep to operate as an advanced playmaker (generating heavy Expected Assists - xA). 

This project executes an automated, multi-layered recruitment pipeline utilizing **FBref scouting metrics** to isolate under-25 emerging talents across European football. By blending linear regression modeling with medical/financial risk audits, this framework presents a strategic, multi-tiered transfer recommendation for club executives.

---

## 🛠️ Tech Stack & Analytical Methodologies
*   **Data Sourcing & Standardization:** Programmatic parsing of European Top-5 league forward metrics via Python, standardizing all spatial metrics to a **Per 90 minute baseline**.
*   **Linear Regression Modeling (`SciPy` & `Matplotlib`):** Plotting shot volume against xG production to establish a market trendline and isolate high-efficiency overperformers.
*   **Stylistic Archetype Matching:** Mapping xG vs. xA to separate "Pure Poachers" from multi-dimensional "Complete Forwards".
*   **Profile Visualizations (`Mplsoccer` & `PyPizza`):** Generating high-contrast multi-player pizza charts across 8 key performance indicators (KPIs) to analyze the mechanical profile of the targets.

---

## 📈 Strategic Insights & Key Visualizations

### 1. The Under-25 Recruitment Matrix
By generating a dense scouting cohort of over 150 young European forwards and executing a strict under-25 filter, the linear regression trendline isolated targets generating disproportionately high xG relative to their shot volume.

### 2. Stylistic Quadrant Analytics (xG vs. xA)
The model mapped targets on a dual-threat axis to evaluate playmaking vs. finishing. While traditional "poachers" sat in the upper-left quadrant, the true stylistic heirs to Harry Kane were isolated in the upper-right quadrant (**High Scoring + High Playmaking**).

---

## 💼 Executive Scout Report: Final Shortlist

Based on our final data output, a two-pronged transfer strategy is recommended to the club's sporting directory:

### 📌 TARGET OPTION A: Benjamin Šeško (23yo | RB Leipzig)
*   **Statistical Reality:** Elite xG/90 (~0.68) with optimal physical and structural box dominance.
*   **Financial Profile:** High market valuation / Premium tier investment.
*   **Scout Verdict:** The premium, fully fit, and low-risk solution. Šeško represents the highest probability of immediate tactical adaptation at Bayern Munich. He is a physically dominant archetype ready to scale into a world-class elite striker with zero friction.

### 📌 TARGET OPTION B: Santiago Giménez (25yo | AC Milan)
*   **Statistical Reality:** High xG/90 (~0.55) with elite spatial tracking and structural chance generation.
*   **Financial Profile:** Low-cost / High-value **"Buy-Low"** arbitrage opportunity.
*   **Scout Verdict:** A highly calculated risk-reward target. Giménez's recent major ankle injury (November 2025) and subsequent adaptational goal-drought at Milan have artificially deflated his market valuation. Traditional scouts are dismissing him based on real-goal output. However, our FBref data verifies that his fundamental positioning capabilities remain fully intact. If physical medical clearance is vetted, he offers an elite-level false 9 capability at a massive market discount. However, he is a “classic center forward” with “false nine” potential.

> 💡 **Strategic Summary:** 
> * For guaranteed, immediate elite output: Invest heavily in **Benjamin Šeško**.
> * For maximum financial efficiency & market arbitrage: Capitalize on **Santiago Giménez**.

---

## 💻 How to Run the Pipeline locally
Colab Link: https://colab.research.google.com/drive/1Pn5fU--rdJk3eodq_EIvtHIRlqNcbmx3?usp=sharing
1. Clone this repository and open the script inside Google Colab or Jupyter Notebook.
2. Ensure you install the optimized visualization frameworks:
```bash
pip install pandas matplotlib seaborn scipy mplsoccer adjustText
