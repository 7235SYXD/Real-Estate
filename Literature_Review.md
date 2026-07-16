#  Literature Review & References

All 13 sources are cited in Harvard format. Each entry includes a brief note
explaining **how it was used** in the project.

---

## References

---

### [1] Andrade-Girón et al. (2025)

**Andrade-Girón, D.C., Marin-Rodriguez, W.J. and Zuñiga-Rojas, M.G. (2025)**
'Intelligent Feature Selection Ensemble Model for Price Prediction in Real Estate Markets',
*Informatics*, 12(2), p. 52.
[ https://www.mdpi.com/2227-9709/12/2/52](https://www.mdpi.com/2227-9709/12/2/52)
*(Accessed: 25 June 2026)*

> **How used:** It is consistent with the use of  ensemble learning method and inspires the
> feature group analysis via ablation technique implemented in Notebook 6 (CELL 31). 
> Andrade-Girón et al. proved that intelligent feature selection prior to ensemble
> creation increases accuracy and reduces training time.

---

### [2] Bushuyev et al. (2024)

**Bushuyev, S. et al. (2024)**
'Machine learning model for house price predicting based on natural language text data analysis',
in *MoMLeT-2024: 6th International Workshop on Modern Machine Learning Technologies*,
CEUR Workshop Proceedings, Vol-3711.
[ https://ceur-ws.org/Vol-3711/paper20.pdf](https://ceur-ws.org/Vol-3711/paper20.pdf)
*(Accessed: 10 June 2026)*

>  **How used:** Reasons why the NLP features like (VADER Sentiment,
> Flesch Readability, Luxury Keywords) along with structured features. Bushuyev et al. discovered that
> the NLP features have an orthogonal price signal beyond the structural attributes.

---

### [3] Deng and Zhang (2025)

**Deng, L. and Zhang, X. (2025)**
'Boosting the accuracy of property valuation with ensemble learning and explainable
artificial intelligence: The case of Hong Kong',
*The Annals of Regional Science*.
[ https://doi.org/10.1007/s00168-025-01365-7](https://doi.org/10.1007/s00168-025-01365-7)
*(Accessed: 20 June 2026)*

>  **How used:** Justification for the SHAP interpretability study in notebook 7
> (CELL 32–33): Deng and Zhang showed that SHAP values derived from gradient
> boosting algorithms offer the actionable insight to property valuers,
> thus justifying the ablation + SHAP + permutation approach we adopted.

---

### [4] Dorogush, Ershov and Gulin (2018)

**Dorogush, A.V., Ershov, V. and Gulin, A. (2018)**
'CatBoost: Gradient boosting with categorical features support',
*Workshop on ML Systems at NeurIPS 2017*.
[ https://arxiv.org/abs/1810.11363](https://arxiv.org/abs/1810.11363)
*(Accessed: 27 May 2026)*

>  **How used:** Technical documentation for CatBoost — one of the four base learners.
> It talks about ordered boosting and ordered target statistics that avoid target
> leakage in categorical features. It is directly referred to while explaining the
> choice of CatBoost over gradient boosting.

---

### [5] Hancock and Khoshgoftaar (2020)

**Hancock, J.T. and Khoshgoftaar, T.M. (2020)**
'CatBoost for big data: an interdisciplinary review',
*Journal of Big Data*, 7(1), pp. 1–45.
[ https://doi.org/10.1186/s40537-020-00369-8](https://doi.org/10.1186/s40537-020-00369-8)
*(Accessed: 23 June 2026)*

>  **How used:** The empirical findings from 50 datasets demonstrate that CatBoost is 
> at least competitive and often better than XGBoost/LightGBM when handling 
> high-cardinality categoricals and missing data – precisely the scenario 
> in TX+NY dataset (3,018 unique cities; 30.4% of ZIPs missing).
---

### [6] Hutto and Gilbert (2014)

**Hutto, C.J. and Gilbert, E. (2014)**
'VADER: A parsimonious rule-based model for sentiment analysis of social media text',
*Proceedings of the 8th AAAI Conference on Weblogs and Social Media*,
pp. 216–225.
[ https://ojs.aaai.org/index.php/ICWSM/article/view/14550](https://ojs.aaai.org/index.php/ICWSM/article/view/14550)
*(Accessed: 29 May 2026)*

>  **How used:** Technical background of the NLP Pipeline in Notebook 1
> (CELL 10-13). Sentiment analysis using VADER is done through generating compound,
> positive, and negative sentiment scores for each listing description, without having
> to train the model – perfect for real estate listing descriptions.

---

### [7] Kania Štykar (2025)

**Kania Štykar, V. (2025)**
*Predictive Modeling for Real Estate Price Using Machine Learning and Textual Descriptions*.
Master's thesis. Charles University, Faculty of Social Sciences, Institute of Economic Studies.
[ https://dspace.cuni.cz/bitstream/handle/20.500.11956/204601/120521395.pdf](https://dspace.cuni.cz/bitstream/handle/20.500.11956/204601/120521395.pdf)
*(Accessed: 15 June 2026)*

>  **How used:** Most rigorous study possible regarding the role of NLP at row level
> in property pricing (1.3M Czech listings). Useful for understanding why the NLP SHAP
> share at state level is low (0.2%) in this project — description helps when structural factors are not enough.

---

### [8] Pastukh et al. (2025)

**Pastukh, O. et al. (2025)**
'Using ensemble methods of machine learning to predict real estate prices',
*arXiv preprint arXiv:2504.04303*.
[ https://arxiv.org/abs/2504.04303](https://arxiv.org/abs/2504.04303)
*(Accessed: 25 June 2026)*

>  **How used:** Background motivation for applying ensemble techniques. Shows
> definitively that tree-based ensembles (bagging & boosting) are superior to individual
> models in all geographically varied European property markets.

---

### [9] Pinero (2025)

**Pinero, R.G.M. (2025)**
'Machine Learning Model for Real Estate Price Prediction in Houston:
Comparing and Optimizing to Find a Higher Accuracy',
*National High School Journal of Science*.
[ https://nhsjs.com/wp-content/uploads/2025/11/Machine-Learning-Model-for-Real-Estate-Price-Prediction-in-Houston-Comparing-and-Optimizing-to-Find-a-Higher-Accuracy-1.pdf](https://nhsjs.com/wp-content/uploads/2025/11/Machine-Learning-Model-for-Real-Estate-Price-Prediction-in-Houston-Comparing-and-Optimizing-to-Find-a-Higher-Accuracy-1.pdf)
*(Accessed: 27 June 2026)*

>  **How used:** One-off analysis of Houston city alone which proves that using Optuna
> hyperparameter optimization increases R² score from 0.71 to 0.76 – thus confirming the
>  positive impact of Optuna in Notebooks 2-3 of this project.

---

### [10] Rani (2025)

**Rani, J. (2025)**
'Advanced Machine Learning Techniques for Real Estate Price Prediction: A Comprehensive Review',
in *Proceedings of the International Conference on Artificial Intelligence and
Applications (ICAAAI-25)*, Atlantis Press.
[ https://www.atlantis-press.com/proceedings/icaaai-25/126012641](https://www.atlantis-press.com/proceedings/icaaai-25/126012641)
*(Accessed: 29 June 2026)*

>  **Usage:** Review of more than 30 studies of machine learning applied to real estate prices.
> Shows that stacking tree-based models with linear meta-learners provides the
> best balance of generalization and complexity — hence the use of Ridge
> meta-learner in Notebook 4 (CELL 26).

---

### [11] Stojanović, Galić and Kahrić (2025)

**Stojanović, Z., Galić, D. and Kahrić, H. (2025)**
'Predicting Real Estate Prices Using Machine Learning in Bosnia and Herzegovina',
*Data*, 10(9), p. 135.
[ https://doi.org/10.3390/data10090135](https://doi.org/10.3390/data10090135)
*(Accessed: 10 June 2026)*

>  **Use of:** Ensures that Random Forest is able to deliver good generalization
> even with little training data from geographic regions — justifying use of RF as
> a base learner and its predominance in the stacking meta-learner coefficients
> (weight=0.765).

---

### [12] Xiao et al. (2025)

**Xiao, Z. et al. (2025)**
'NNLS; House Price Prediction; Ames Dataset',
*Journal of Data Science and Analytics*.
[ https://hbemdata.org/index.php/ojs/article/view/96](https://hbemdata.org/index.php/ojs/article/view/96)
*(Accessed: 1 July 2026)*

> **How used:** Uses NNLS (Non-Negative Least Squares) as the meta-learner for stacking. 
> This is compared to this project’s use of ridge regression, where negative
> coefficients can act as a diagnostic tool (base learner is hurting the
> model) because ridge allows negative values of the weights.

---

### [13] Zhao and Wang (2023)

**Zhao, H. and Wang, K. (2023)**
'Predicting real estate price using stacking-based ensemble learning',
*American Journal of Information Science and Technology*, 7(2), pp. 70–75.
[ https://doi.org/10.11648/j.ajist.20230702.14](https://doi.org/10.11648/j.ajist.20230702.14)
*(Accessed: 2 June 2026)*

>  **Usage:** Used as the primary architectural reference for the whole stacking process.
> Zhao and Wang proved that an ensemble stacking approach will always be better
> than any of the single base model — hence the introduction of 5-fold OOF stacking
> in the Notebook 4 (CELL 25-26) and the Ridge meta-learner in CELL 27.

---

##  Literature Summary Table

| # | First Author | Year | Key Contribution to This Project |
|---|-------------|------|----------------------------------|
| 1 | Andrade-Girón | 2025 | Feature selection + ensemble → ablation design |
| 2 | Bushuyev | 2024 | NLP features carry orthogonal price signal |
| 3 | Deng & Zhang | 2025 | SHAP interpretability for property valuation |
| 4 | Dorogush | 2018 | CatBoost ordered boosting — prevents leakage |
| 5 | Hancock | 2020 | CatBoost best for high-cardinality + missing data |
| 6 | Hutto & Gilbert | 2014 | VADER sentiment for short promotional text |
| 7 | Kania Štykar | 2025 | Row-level NLP > state-level NLP contribution |
| 8 | Pastukh | 2025 | Ensemble methods generalise across markets |
| 9 | Pinero | 2025 | Optuna tuning lifts R² significantly |
| 10 | Rani | 2025 | Stacking + linear meta-learner = best trade-off |
| 11 | Stojanović | 2025 | RF strong across diverse/low-data markets |
| 12 | Xiao | 2025 | NNLS vs Ridge as meta-learner — design contrast |
| 13 | Zhao & Wang | 2023 | OOF stacking ensemble design — core reference |

---

