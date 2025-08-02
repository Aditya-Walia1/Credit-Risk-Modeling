# Credit Risk Modeling: PD, LGD, EAD & Expected Loss

Understanding and managing credit exposure is central to modern financial systems. This project presents a modular framework for assessing credit risk by estimating core risk components and simulating expected losses based on customer-level financial data.

---

## 🔍 Project Highlights

- Modeled **Probability of Default (PD)** using logistic regression  
- Estimated **Loss Given Default (LGD)** via linear regression techniques  
- Predicted **Exposure at Default (EAD)** using relevant borrower and loan features  
- Combined the outputs to compute **Expected Loss** and simulate credit exposure  
- Incorporated **regulatory capital logic** for stress-adjusted scenarios  
- Designed a scoring structure to monitor default risk across segments

---

## 📊 Methodology

- Data Cleaning & Feature Engineering  
- Handling class imbalance using synthetic sampling  
- Regression modeling for PD, LGD, and EAD  
- Metric evaluation using ROC-AUC, RMSE, decile performance  
- Final aggregation to simulate exposure and credit loss distribution

---

## 🛠️ Tools & Libraries

- Python (pandas, numpy, scikit-learn)
- Matplotlib & Seaborn for visual analytics
- Imbalanced-learn for SMOTE techniques

---

## 📈 Sample Outputs

> 📌 *Add screenshots here after running notebooks locally*

- ROC Curve for Default Probability  
- Expected Loss heatmap across risk tiers  
- Default probability distribution  
- Borrower segmentation by score decile

---

## 🧩 Business Relevance

The modeling logic reflects real-world practices used in credit risk functions across banking institutions. With scalable structure and interpretable metrics, the framework is adaptable for regulatory, operational, or capital forecasting purposes.

---

## 📁 Repository Structure

```bash
├── data/                           # Raw and processed data
├── notebooks/                     
│   ├── PD_Model.ipynb             # Logistic regression model
│   ├── LGD_Model.ipynb            # Linear regression for LGD
│   ├── EAD_Model.ipynb            # EAD estimation
│   └── Expected_Loss.ipynb        # Final aggregation
├── visuals/                       # Screenshots and plots
├── README.md
