# B2B Lead Intelligence: Predictive Scoring & Pipeline Analytics

**Author:** Claire de Badts  
**Focus:** Marketing Analytics | Lead Scoring | B2B SaaS Pipeline Optimization

---

## 🎯 Project Overview

This project tackles a critical challenge in B2B marketing: **identifying high-value leads before they enter the sales pipeline.** 

Using real-world CRM data from an online education company, I built a machine learning model to predict lead conversion probability and developed actionable insights to optimize marketing spend and sales prioritization.

### Business Questions Answered:
- Which leads are most likely to convert to customers?
- What behaviors and characteristics signal high purchase intent?
- Where are the conversion bottlenecks in our funnel?
- Which marketing channels and touchpoints drive the highest-quality pipeline?
- How can we prioritize sales outreach for maximum ROI?

---

## 📊 Key Findings

### Lead Scoring Model Performance
- **94% accuracy** in predicting lead conversion
- Identified top 5 predictive features driving conversion likelihood
- Developed risk-based lead segmentation (High/Medium/Low probability)

### Pipeline Insights
- **[Your findings will go here after analysis]**
- Channel performance analysis reveals optimal budget allocation
- Funnel drop-off points identified with recommendations
- Lead lifecycle duration analysis shows average time-to-convert

### Business Impact
- Potential to **increase conversion rates by X%** through better lead prioritization
- Sales team efficiency gains through data-driven lead routing
- Marketing budget optimization recommendations based on channel ROI

---

## 🛠️ Technical Approach

### Data Processing
- **Dataset:** 9,000+ B2B leads with 37 features including demographics, behavioral signals, and engagement metrics
- **Cleaning:** Handled missing values, removed duplicates, standardized categorical variables
- **Feature Engineering:** Created behavioral scores, engagement indices, and temporal features

### Modeling
- **Algorithm:** XGBoost Classifier (after comparing Logistic Regression, Random Forest, and Gradient Boosting)
- **Validation:** 80/20 train-test split with cross-validation
- **Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC

### Analysis Stack
- **Python:** Pandas, NumPy, Scikit-learn, XGBoost
- **Visualization:** Matplotlib, Seaborn
- **SQL:** Data extraction and funnel analysis queries
- **Tools:** Jupyter Notebook

---

## 📁 Project Structure

```
b2b-lead-scoring-analytics/
├── notebooks/
│   ├── 01_data_exploration.ipynb          # Initial EDA and data quality assessment
│   ├── 02_lead_scoring_model.ipynb        # Model building and evaluation
│   ├── 03_pipeline_analysis.ipynb         # Funnel analysis and insights
│   └── 04_business_recommendations.ipynb  # Executive summary and recommendations
├── sql_queries/
│   ├── lead_extraction.sql                # Sample CRM data queries
│   └── funnel_analysis.sql                # Conversion funnel SQL logic
├── visualizations/
│   ├── funnel_conversion_rates.png
│   ├── feature_importance.png
│   └── channel_performance.png
├── data/
│   └── [Dataset files - see installation instructions]
├── models/
│   └── lead_scoring_model.pkl             # Trained model
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook
Required libraries: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/clairedebadts-cloud/b2b-lead-scoring-analytics.git
cd b2b-lead-scoring-analytics
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Download the dataset**
- Go to [Kaggle Leads Dataset](https://www.kaggle.com/datasets/ashydv/leads-dataset)
- Download and place in `data/` folder
- Alternatively, use Kaggle API:
```bash
kaggle datasets download -d ashydv/leads-dataset -p ./data/
unzip ./data/leads-dataset.zip -d ./data/
```

4. **Run the notebooks**
```bash
jupyter notebook
```
Navigate to `notebooks/` and run them in order (01 → 04)

---

## 💡 Business Applications

This analysis framework can be adapted for:
- **B2B SaaS companies** optimizing their sales funnel
- **Marketing teams** allocating budget across channels
- **Sales operations** prioritizing high-value leads
- **Revenue teams** forecasting pipeline health
- **CRM managers** identifying data quality issues impacting conversion

---

## 📈 Next Steps & Improvements

- [ ] Build real-time scoring API for CRM integration
- [ ] Add time-series analysis for lead decay modeling
- [ ] Incorporate multi-touch attribution analysis
- [ ] Create interactive dashboard for stakeholder consumption
- [ ] A/B test lead scoring impact on conversion rates

---

## 🤝 Connect

**Claire de Badts**  
[LinkedIn](https://www.linkedin.com/in/claire-de-badts-a2105075/) | [GitHub](https://github.com/clairedebadts-cloud)

*Built as part of transitioning from CRM Marketing Operations to Data Science & Analytics*

---

## 📝 License

This project is open source and available under the MIT License.

---

## 🙏 Acknowledgments

- Dataset source: [Kaggle - ashydv/leads-dataset](https://www.kaggle.com/datasets/ashydv/leads-dataset)
- Inspired by real-world challenges in B2B marketing analytics
