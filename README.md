# Hi, I'm Yijin

**PhD in Statistics & Machine Learning (Imperial College London)**  
My PhD research focuses on developing novel methodologies for statistical two-sample hypothesis testing, statistical association, and change point detection in the presence of missing data, especially when the missing data are informative. Applications include A/B testing, clinical trials, information retrieval, and continual learning. A key goal of my work is to enable valid and robust statistical inference in the presence of missing data, a common challenge in real-world scenarios. Make sure to check my work listed in the references if you are interested!

- 🔬 Research interests: 
- 🧪 Methods I work with: MMD, WMW, Spearman/Kendall, permutation/bootstraps, encoder–decoder RNNs
- ⚙️ Values: clarity, reproducibility, small APIs, measured claims

---

## 🔗 Start here

- **Open-source packages**
  Part of my PhD is about coding my methodologies into open-source packages for real-world impact.
  - **wmwm (Python)** — Wilcoxon–Mann–Whitney test with arbitrary missing data.
    ↳ <https://github.com/Yijin-Zeng/wmwm>
  - **wmwm (R)** — Wilcoxon–Mann–Whitney test with arbitrary missing data.
    ↳ <https://github.com/Yijin-Zeng/Wilcoxon-Mann-Whitney-Test-with-Missing-data>
  - **bosfr (R)** — Right bounds for Spearman’s footrule with missing data  
    ↳ <https://github.com/Yijin-Zeng/bosfr>

- **Applied projects (selected)**
  Besides my PhD work, I enjoy working on real world data science projects.
  - **Signal Predictive Power Evaluation** — leak-free evaluation of a daily trading signal (walk-forward, costs)  
    ↳ <https://github.com/Yijin-Zeng/Signal-Predictive-Power-Evaluation>
  - **E-Commerce Order Cancellation Prediction** — imbalanced learning, cost-sensitive metrics, FP reduction  
    ↳ <https://github.com/Yijin-Zeng/E-CommerceOrderCancellationPrediction>
  - **Stock Clustering** — correlation networks → clusters; stability + downstream utility  
    ↳ <https://github.com/Yijin-Zeng/StockClustering>
  - **Hangman Game (NN)** — LSTM baseline + frequency heuristic for masked-word guessing  
    ↳ <https://github.com/Yijin-Zeng/HangmanGame>
  - **Weather Forecasting** *(rename from “WeatherForcasting”)* — tidy pipelines for time-series forecasting  
    ↳ <https://github.com/Yijin-Zeng/WeatherForecasting>

  - **Understanding Machine Learning & Deep Learning**
  I am curious about machine learning and deep learning, and try to understand how & why they work.
  - **A review for change point detection methods** — focusing on core methodologies and mathematical foundations
    ↳ <https://github.com/Yijin-Zeng/A-review-for-change-point-detection-methods>
  - **A review of deep Gaussian Process** — earning meaningful embedding with extreme small dataset (10-50 training samples).
    ↳ <https://github.com/Yijin-Zeng/A-Review-of-Deep-Gaussian-Process>
    

---

## 📦 Research & code
- Repos include **README-first** docs, minimal APIs, and examples.
- Where possible I add: `requirements.txt` / `environment.yml`, seeds, `Makefile`/`justfile`, and CI.
- I’m adding `CITATION.cff` and LICENSE files across projects so others can cite & reuse.

---

## 📈 What I’m up to
- Tight bounds + tests for rank-based statistics with missing data (Spearman footrule, Kendall’s τ, Spearman’s ρ)
- Robust two-sample testing with MMD under MNAR
- Practical evaluations: walk-forward validation and cost-aware metrics


## References
[1] **Zeng Y**, Adams NM, Bodenham DA. On two-sample testing for data with arbitrarily missing values. arXiv preprint arXiv:2403.15327. 2024 Mar 22.

[2] **Zeng Y**, Adams NM, Bodenham DA. MMD Two-sample Testing in the Presence of Arbitrarily Missing Data. arXiv preprint arXiv:2405.15531. 2024 May 24.

[3] **Zeng Y**, Adams NM, Bodenham DA. Exact Bounds of Spearman's footrule in the Presence of Missing Data with Applications to Independence Testing. arXiv preprint arXiv:2501.11696. 2025 Jan 20.
