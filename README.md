# Marketing Campaign Analysis (Classification Models)

This repository contains the work for **Module 17** of the **UC Berkeley Engineering / Berkeley Haas Professional Certificate in Machine Learning and Artificial Intelligence**. The project focuses on analyzing a bank marketing dataset to predict customer responses and optimize campaign strategies using machine learning models.

## Project Objective

The objective of this analysis is to identify factors that influence whether a customer subscribes to a term deposit and to provide actionable insights to improve marketing efficiency.

The results help financial institutions:
- optimize customer targeting
- reduce marketing costs
- improve campaign success rates
- better understand customer behavior

## Repository Contents

- `MarketingCampaignAnalysis.ipynb` — main notebook with data cleaning, EDA, modeling, and results
- `data/` — dataset files used in the project
- `images/` — visualizations generated during analysis

## Business Understanding

Marketing campaigns often suffer from low conversion rates and high costs. By understanding customer behavior and campaign effectiveness, organizations can:
- focus on high-value customers
- reduce unnecessary outreach
- improve ROI on marketing spend

## Summary of Findings

### Model Performance Insights:
- False Positive Rate: ~17.7%
- False Negative Rate: ~0.5%
- High recall ensures minimal missed opportunities
- Trade-off: increased marketing cost due to over-targeting

### Key Observations:
- Dataset is highly **imbalanced**, skewed toward unsuccessful campaigns
- Models can be used to:
  - identify factors driving unsuccessful campaigns
  - identify high-potential customers

### Customer Insights:
- Customers contacted via **cellular channels** show higher success rates
- Indicates effectiveness of modern communication channels

## Recommendations

Based on the analysis, financial institutions should:

- Focus on **high-probability customer segments**
- Optimize model thresholds to balance cost vs recall
- Adopt modern communication channels such as:
  - SMS campaigns
  - Social media platforms (Facebook, Instagram, etc.)
- Continuously evaluate campaign performance using data-driven approaches

## Additional Data to Collect

To improve future modeling and business insights:

- Customer income or financial profile
- Previous interaction history
- Customer engagement behavior
- Cost of campaign outreach

## Tools and Methods

This project was developed using:

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- matplotlib / seaborn
- Classification models (Logistic Regression, SVM)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/rsatsangi/UCBEHass-PCMLAI-MOD17.git
   ```
2. Navigate into the project folder:
   ```bash
   cd UCBEHass-PCMLAI-MOD17
   ```
3. Open the notebook:
   ```bash
   jupyter notebook MarketingCampaignAnalysis.ipynb
   ```

## Conclusion

This project demonstrates how machine learning can improve marketing effectiveness by balancing customer targeting and operational costs. By leveraging model insights, organizations can enhance campaign performance and make more informed business decisions.

## Author
**Rupanshu Satsangi**  
UC Berkeley – ML/AI Professional Certificate Program
