# Customer-Churn-Risk
# 📊 Customer Churn Prediction System

A machine learning solution to predict customer churn using the Telco Customer Churn dataset. This system helps businesses identify customers at risk of leaving and provides actionable insights for retention strategies.

## 🎯 What This Does

- **Predicts Customer Churn**: Identifies customers likely to cancel their service
- **Risk Scoring**: Categorizes customers into Low, Medium, and High risk groups
- **Feature Analysis**: Shows which factors most influence customer churn
- **Business Insights**: Provides actionable recommendations for customer retention

## 📈 Performance

- **Accuracy**: ~80% prediction accuracy
- **Precision**: ~67% (of predicted churners, 67% actually churn)
- **Recall**: ~54% (catches 54% of actual churners)
- **AUC Score**: ~0.85 (good discriminative ability)

## 🚀 Quick Start
**Download the dataset**: 
   - Get the "Telco Customer Churn" dataset from Kaggle
   - Place the CSV file in your project directory

## 📊 What You'll Get

### Visualizations
- Customer churn distribution charts
- Feature importance plots
- Model performance metrics (ROC curve, confusion matrix)
- Risk category breakdowns

### Key Insights
- **High-Risk Factors**: Month-to-month contracts, electronic check payments, fiber optic service issues
- **Low-Risk Factors**: Long tenure, higher total charges, annual contracts
- **Customer Segmentation**: Automatic categorization into risk levels

### Business Recommendations
- Target month-to-month customers for contract upgrades
- Improve payment method options
- Focus on new customer onboarding
- Develop loyalty programs for high-value customers

## 🔧 Key Features

### Data Processing
- Handles missing values automatically
- Converts categorical variables to numerical format
- Scales features for optimal model performance

### Model Features
- **Algorithm**: Logistic Regression (interpretable and reliable)
- **Risk Scoring**: Probability-based customer risk assessment
- **Feature Importance**: Identifies top factors driving churn


## 📁 Dataset Format

The system expects the standard Telco Customer Churn dataset with columns:
- Customer demographics (gender, age, partner, dependents)
- Account information (tenure, contract type, payment method)
- Services (phone, internet, streaming, security features)
- Charges (monthly charges, total charges)
- Target variable (Churn: Yes/No)

## 🎯 Business Impact

### Risk Categories
- **High Risk (≥70% probability)**: Immediate intervention needed
- **Medium Risk (40-70% probability)**: Targeted retention campaigns  
- **Low Risk (<40% probability)**: Standard customer care

### Expected Outcomes
- Identify customers at risk before they churn
- Reduce customer acquisition costs
- Increase customer lifetime value
- Optimize retention campaign targeting

## 📊 Key Insights from Analysis

### Top Churn Risk Factors
1. **Month-to-month contracts** - Highest churn risk
2. **Electronic check payments** - Less convenient payment method
3. **Fiber optic service issues** - Service quality problems
4. **Low tenure** - New customers more likely to leave
5. **No additional services** - Less customer stickiness

### Retention Strategies
- **Contract Incentives**: Offer discounts for annual/2-year contracts
- **Payment Simplification**: Promote automatic payments
- **Service Quality**: Address fiber optic service issues
- **New Customer Care**: Enhanced onboarding for first 6 months
- **Value-Added Services**: Bundle services for better retention

## 🔍 Model Interpretation

The logistic regression model provides clear, interpretable results:
- **Positive coefficients** = factors that increase churn risk
- **Negative coefficients** = factors that decrease churn risk
- **Coefficient magnitude** = strength of the factor's influence

## 🤝 Contributing

Feel free to submit issues and enhancement requests! 

**Perfect for**: Data science portfolios, business analytics projects, customer retention studies, and machine learning practice.
