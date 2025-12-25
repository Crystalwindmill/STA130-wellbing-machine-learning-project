# Social Interaction & Mental Wellbeing Analysis

## 🏆 Recognition
**"Best Tutorial Presentation"** — Analysis methodology shared with SFU professor as research reference.

---

## 📋 Project Overview
Statistical analysis examining how **verbal interaction, physical interaction, and community engagement** influence mental wellbeing among Canadians.

*University of Toronto STA130 Course Project (Oct–Dec 2024)*

**Dataset:** Canadian Social Connection Survey (GenWell & CASCH) — 10,000+ survey responses

---

## 🔬 Research Questions

### Question 1: Social & Virtual Interactions → Mental Health
How do face-to-face interactions (friends, coworkers, family) and virtual interactions (video chat, texting) influence self-rated mental health?

**Key Findings:**
| Variable | P-value | Effect |
|----------|---------|--------|
| Time with Family | 0.012 | +0.299 (Significant ✓) |
| Group Video Chat | 0.000 | +0.384 (Significant ✓) |
| Texting Friends | 0.000 | +0.334 (Significant ✓) |

- Family time shows **strongest positive effect** on mental health among in-person interactions
- Virtual group activities significantly boost mental wellbeing

### Question 2: Physical Touch (Hugs) → Happiness
Do hugs have a statistically significant effect on self-rated happiness?

**Key Findings:**
| Group | Mean Happiness | Sample Size |
|-------|---------------|-------------|
| No hugs (past month) | 4.14 | 266 |
| At least one hug | 5.00 | 537 |

- **0.86 point increase** in happiness score (p=0.000)
- Supports existing research on physical touch and serotonin/cortisol levels

### Question 3: Community Engagement → Life Satisfaction
Does frequency of community engagement affect life satisfaction?

**Key Findings:**
- **Weekly engagement** shows optimal life satisfaction (peak at 6.9/10)
- No engagement: lowest satisfaction (5.8/10)
- Daily engagement: satisfaction drops — possible burnout effect
- Statistically significant after correcting for class imbalance (p=0.000)

---

## 📊 Methods

- **Linear Regression** — Quantified relationships between predictors and outcomes
- **Random Forest** — Feature importance analysis
- **Hypothesis Testing** — Statistical significance assessment
- **Data Wrangling** — Feature engineering, encoding categorical → binary variables, handling class imbalance

---

## 🛠️ Tools & Technologies
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Statistical Methods**: Multiple regression, correlation analysis, p-value testing
- **Visualization**: Box plots, stacked bar charts, feature importance plots

---

## 📁 Repository Structure
```
├── README.md
├── STA130_analysis.ipynb       # Main analysis code
├── STA130_presentation.pdf     # Project slides
└── data/                       # Survey data (if applicable)
```

---

## 💡 Key Takeaways

1. **Family connections matter most** for in-person mental health benefits
2. **Virtual group interactions** (not 1-on-1) significantly improve wellbeing
3. **Physical touch** has measurable impact on happiness
4. **Moderate community engagement** is optimal — too much may cause burnout

---

## 👥 Team
- Crystal Li
- Yu-Hsuan Tsai
- Zachary Tianyi Tang
- Howard Zhang

**Course:** STA130 (LEC0101) | **TA:** Nicholas William Susanto

---

## 📚 References
- Canadian Social Connection Survey (GenWell & CASCH)
- Sumioka et al. (2013) — Physical touch and cortisol levels
- Denison (2004), Tabatabaee et al. (2016) — Therapeutic touch research

---

## 👤 Contact
**Crystal W Li**  
B.Sc. Statistics & Actuarial Science, University of Toronto  
[LinkedIn](http://linkedin.com/in/crystal-li-baa648351) | [Email](mailto:crystalw.li@mail.utoronto.ca)
