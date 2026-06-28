# Hi, I'm Krrish Kumar 👋

**Data Science | Quantitative Analysis**

Dual-degree student in Chemical Engineering (BIT Mesra) and Data Science & Applications (IIT Madras). I build end-to-end ML pipelines and like to verify my own numbers before I trust them — most of the projects below involved catching and fixing a real bug or a false claim along the way, and I think that process is worth showing, not hiding.

---

## 📂 Data Science Portfolio (Summer 2026)

Four end-to-end projects built through the Consulting & Analytics Club, IIT Guwahati. Each one was audited against its original brief, rebuilt where needed, and every reported number was re-verified by re-running the code - not assumed.

- 🏦 **[Digital Lending Portfolio Optimization](https://github.com/krrishkumar333333/Digital-Lending-Optimization)** - Self-generated synthetic lending dataset with explicit causal logic, calibrated XGBoost/CatBoost risk model (AUC 0.71, calibration gap fixed from 0.345 → 0.006), and a financial simulation showing why manual underwriting review outperforms auto-decline.

- 🚛 **[Delivery ETA Prediction](https://github.com/krrishkumar333333/Delivery-ETA-Prediction)** - Graph-based network intelligence (betweenness centrality, Node2Vec embeddings) for logistics ETA prediction. Found a real, counter-intuitive routing result: Carting beats FTL on speed in 15 of 17 corridor profiles tested, contradicting the default assumption that FTL is faster.

- ✈️ **[Airline Loyalty Retention](https://github.com/krrishkumar333333/Airline-Loyalty-Retention)** - Behavioral + demographic churn segmentation (5 silhouette-validated, stability-tested clusters) and a calibrated XGBoost early-warning model. Validated the churn definition against real cancellation records (92.4% overlap) before trusting it.

- 🛍️ **[D2C Customer Value Decoding](https://github.com/krrishkumar333333/D2C-Customer-Value-Decoding)** — Built and tested two competing loyalty definitions on real transactional data, then picked one using measured evidence (correlation with promo dependency), not intuition. Found and documented a data quality issue (two columns that were 100% duplicates) before it could distort the analysis.

---

## 🛠️ Technical Toolkit

**Languages:** Python, SQL
**Machine Learning:** XGBoost, CatBoost, Scikit-learn, model calibration (isotonic regression)
**Graph & Network Analysis:** NetworkX, Node2Vec, betweenness centrality
**Data Engineering:** Pandas, NumPy, synthetic data generation, feature engineering
**Visualization & BI:** Power BI, Streamlit, Matplotlib
**Tools:** Jupyter, Git, WorldQuant BRAIN

---

## A note on how I work

Most of these projects went through a real audit-and-rebuild cycle: checking real column names against data dictionaries instead of assuming them, re-running models to confirm reported numbers are reproducible, and checking probability calibration before trusting any model's output for a business decision. A few times this meant discovering a number I'd previously reported was wrong, or that a brief's stated hypothesis just didn't hold on real data - I'd rather report an honest null result than force a story onto the data.

📫 Reach me at: krrishkumar333333@gmail.com
