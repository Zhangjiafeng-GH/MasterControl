
# MasterControl
## Business Problem
  MasterControl’s Mx product underperforms in converting sales leads compared to its Qx line, with limited insight into which opportunities drive success.
  This project uses data analysis and predictive modeling to identify high-value prospects and key factors influencing deal conversion, helping improve sales prioritization, increase win rates, and shorten sales cycles.

## Group solution to the business problem
  We developed a predictive lead scoring model using historical Mx sales data to estimate the likelihood of deal progression. A LASSO model (AUC ~0.79) was selected for its strong performance and interpretability. 
  Based on model outputs, we recommended prioritizing the top 25–30% of leads, supported by an ideal customer profile (ICP) and a clear implementation roadmap.
  
## Contribution to the project
* Performed data cleaning by handling missing values, standardizing key features, and removing inconsistent or duplicate records.  
* Built and tuned a Random Forest model (trees, depth, mtry) and evaluated performance using cross-validation and AUC.  
* Generated feature importance insights to identify key risk drivers.  
* Compared models and helped determine that XGBoost outperformed Random Forest as the final model.  

## The business value of the solution
* Increased conversion rates to ~42–46% by prioritizing high-probability leads.  
* Generated an estimated $9M–$10.6M in pipeline value through improved targeting.  
* Reduced wasted sales effort by focusing on the top 25–30% of leads.  
* Enabled more efficient and data-driven sales decision-making.  

## Difficulty
Key challenges included handling missing and imbalanced data, selecting interpretable yet high-performing models, and aligning model outputs with realistic sales capacity constraints.

## Take Away
I strengthened my skills in predictive modeling, feature engineering, and model evaluation, and gained experience translating data insights into actionable business strategies.
