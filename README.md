# Customer Insights – Statistical Investigation

## 🎯 Project Overview
**Career247 Data Analytics Course Project** by **Tushar** – Analyzed **10,675 US customer transactions** (1,000 unique customers) to test relationships between **demographics** and **monthly spend** using statistical hypothesis testing.

## 📊 Research Questions Tested
| Test | Hypothesis | Method |
|------|------------|--------|
| Gender vs Spend | Do males/females spend differently? | **T-test** |
| Education vs Spend | Do education levels differ in spend? | **ANOVA** |
| Married vs Pets | Is marital status related to pets? | **Chi-square** |
| Age vs Recency | Does age correlate with interaction? | **Correlation** |
| State vs Spend | Do states spend differently? | **ANOVA** |

## 🔬 Key Findings
| Test | **P-value** | **Significant?** | **Business Insight** |
|------|-------------|------------------|---------------------|
| Gender T-test | 0.73 | ❌ No difference | Gender-neutral campaigns |
| **Married-Pets Chi-sq** | **0.00** | ✅ **Strong** | Target married pet owners |
| Education ANOVA | 0.92 | ❌ No difference | Education doesn't matter |
| Age Correlation | 0.68 | ❌ Weak | Age not predictive |
| State ANOVA | 0.35 | ❌ Similar | Focus high-spend states |

**Top 3 Spend States**: Arizona ($341), Ohio ($340), California ($339)

## 🛠️ Technical Stack
Python: Pandas, NumPy, Matplotlib, Seaborn
Statistics: SciPy (T-test), Statsmodels (ANOVA)
Data: 12 features × 10,675 records

## 📈 Visualizations
| **KDE Plots** (Spend by Education/Marital) | **Business Insights** |
|--------------------------------------------|----------------------|
| ![KDE Plots](KDE-PLOTS.jpg) | ![Business Insights](BUSINESS-IN-SG9HTS.jpg) |

| **Histograms & Boxplots** | **Correlation Heatmap** |
|---------------------------|-------------------------|
| ![Histograms](HISTOGRAMS-AND-BOXPLOTS.jpg) | ![Heatmap](HEATMAP.jpg) |

💼 Skills Demonstrated
Exploratory Data Analysis (EDA)

Hypothesis Testing (T-test, ANOVA, Chi-square)

Statistical Interpretation

Data Visualization

Python Data Science

Business Recommendations


📁 Files Included
Unlocking_Customer_Insights_A_Statistical_Investigation.ipynb – Complete analysis

US_Customer_Insights_Dataset.csv – 10k+ customer data

4 Visualizations (KDE, Heatmap, Histograms, Insights)

Built by Tushar
Data Analyst in Training | Career247 Data Analytics Course
📧 Open to feedback | 🔗 Portfolio projects welcome
#DataAnalytics #Python #Statistics #BusinessIntelligence


## ✅ Instructions:
1. **Delete everything** in the white box[1]
2. **Paste above content** 
3. **"Commit new file"** (green button bottom)
4. **Repo 100% ready** for LinkedIn!

**Your repo link**: `https://github.com/tushar27012001-hub/customer-insights-statistical-investigation`

## 🚀 Run Locally
```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scipy statsmodels

# Launch notebook
jupyter notebook "Unlocking_Customer_Insights_A_Statistical_Investigation.ipynb"
