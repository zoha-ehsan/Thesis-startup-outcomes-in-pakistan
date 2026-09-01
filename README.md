# Predicting Startup Outcomes in Pakistan

## 📊 Overview
This repository contains my BS (Hons) Statistics thesis submitted to **GC University, Lahore**. 
The study uses an integrated econometric and multidimensional statistical approach to predict 
startup outcomes in Pakistan, focusing on survival status and revenue performance.

## 🔍 Research Questions
1. What are the main characteristics of startups operating in Pakistan?
2. Which factors significantly predict whether a startup survives or closes?
3. Which factors significantly predict how much revenue a startup generates?
4. Can statistical models accurately predict startup closure and revenue levels?
5. How effective are multidimensional statistical methods in analyzing startup data?

## 📈 Key Findings
| Finding | Result |
|---------|--------|
| **Negative Growth** | 15.17x higher hazard of closure |
| **Revenue Protection** | Each 1% revenue increase reduces closure hazard by 25% |
| **Funding Paradox** | Higher funding slightly increases closure risk (B = 0.003, p = 0.029) |
| **Survival Rate** | Only 30.6% of negative-growth startups survive past 7 years |

## 🛠️ Methods Used
- **Cox Proportional Hazards Regression** — Survival analysis
- **Kaplan-Meier Survival Analysis** — Survival curves & hazard functions
- **MANOVA** — Multivariate analysis by startup size & status
- **Linear Regression** — Revenue prediction
- **K-Means Clustering** — Startup segmentation
- **ANOVA & T-Tests** — Group comparisons
- **Distribution Fitting (EasyFit)** — Probability distributions

## 📂 Files
| File | Description |
|------|-------------|
| `thesis-pakistan-startups.pdf` | Full thesis document |
| `code/` | R scripts for all analyses |
| `data/startup_data.csv` | Dataset (anonymized) |
| `presentation/` | Defense slides |
| `images/` | Visualizations from the study |

## 📊 Sample Visualizations
![Kaplan-Meier Survival Curve](images/kaplan_meier_curve.png)
*Survival probability by growth status. Only 30.6% of negative-growth startups survive past year 7.*

![Cluster Plot](images/cluster_plot.png)
*High Growth (8.7%) vs Mainstream (91.3%) clusters.*

## 🎯 Business Implications
- **Entrepreneurs:** Prioritize growth over fundraising
- **Investors:** Exercise caution funding startups without positive growth
- **Policymakers:** Focus on growth-enabling infrastructure

## 📝 Author
**Zoha Ehsan**  
BS (Hons) Statistics, GC University, Lahore  
Supervised by: Dr. Hina Khan

## 📄 License
This work is for academic and professional reference purposes.
