# Statistical Analysis of Customer Churn in the Iranian Telecom Market 

## Introduction / Background  
In the competitive telecommunications sector, customer retention is critical for business sustainability. A major Iranian telecom company faced increased customer churn, prompting an in-depth statistical analysis. This project leverages statistical techniques such as hypothesis testing, ANOVA, bootstrapping, and regression modeling to identify key factors influencing churn.  

## Research Questions  
1. Are there differences in usage duration among customers on different tariff plans? *(T-Test)*  
2. Do long-term subscribers have distinct calling and messaging behaviors? *(EDA)*  
3. How do service quality perceptions and engagement impact churn likelihood? *(Chi-Squared Test)*  
4. Can demographic segmentation identify high-value customer groups? *(ANOVA, EDA)*  
5. How do predictor variables affect Customer Lifetime Value (CLV) predictions? *(Regression Analysis)*  
6. What plan modifications can help reduce churn? *(Bootstrapping & Confidence Intervals)*  

## Methods and Data Collection  
### Dataset Source  
- **UCI Machine Learning Repository**  
- **3,150 customer records**, spanning 12 months, including:  
  - Call failures, SMS frequency, complaints, subscription length  
  - Churn label indicating retention status  

### Statistical Techniques Used  
- **T-tests**: Compare mean usage duration across tariff plans  
- **ANOVA**: Examine behavioral differences across age groups  
- **Regression Modeling**: Analyze predictor variables’ impact on CLV  
- **Chi-Squared Test**: Assess relationship between activity levels and churn  
- **Bootstrapping**: Estimate confidence intervals for retention strategies  

## Results and Insights  
### Exploratory Data Analysis (EDA)  
- **Churn Rate**: 15% of customers churned (imbalanced dataset)  
- **Age Groups**: Higher churn among younger (10-19) and older (50-59) customers  
- **Usage Trends**: Preference for calls over texts; service dissatisfaction linked to lower usage  
- **Subscription Model**: Higher churn in pay-as-you-go plans vs. contractual plans  
- **Behavioral Shifts**: Long-term subscribers favor SMS over calls  

### Key Statistical Findings  
#### Research Question 1: Tariff Plan Impact  
*T-test (\( t = -7.4271 \), \( p = 1.295 \times 10^{-12} \)) confirmed significant usage differences, suggesting pay-as-you-go enhancements could improve retention.*  

#### Research Question 2: Subscription Duration  
*EDA revealed longer-term customers preferred SMS, indicating a need for customized offers.*  

#### Research Question 3: Service Quality & Engagement  
*Chi-squared test (\( \chi^2 = 781.11 \), \( p < 0.05 \)) showed active customers were less likely to churn, emphasizing the need for engagement strategies.*  

#### Research Question 4: Demographics & Churn  
*ANOVA confirmed significant churn variance across age groups, suggesting targeted marketing strategies.*  

#### Research Question 5: CLV Accuracy  
*Regression analysis showed dynamic predictor variable changes influenced CLV reliability.*  

#### Research Question 6: Plan Modifications  
*Bootstrapping confirmed that optimized plan features could statistically reduce churn.*  

## Conclusion  
This study provided statistical insights into customer churn in the Iranian telecom sector. Findings emphasized **targeted retention strategies, customer engagement, and demographic-based marketing** to reduce churn and boost profitability.  

