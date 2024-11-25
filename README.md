# CLABSI-Prediction-using-ML
Predicting Central Line Associated Bloodstream Infection using ML Algorithms - A Project of Texas Children's Hospital

This project synthesizes insights from two key assignments focusing on Central Line-Associated Bloodstream Infections (CLABSI) in Pediatric Intensive Care Units (PICUs). These reports encompass the financial, clinical, and predictive modeling aspects of CLABSI, along with advanced sampling techniques to improve data-driven analysis and outcomes.

1. Financial and Clinical Impact of CLABSI in PICUs**
Study 1: Financial Burden 
  - Conducted at St. Louis Children’s Hospital, this prospective cohort study quantified the economic impact of nosocomial bloodstream infections.
  - Findings revealed a significant cost difference between infected and non-infected patients, with an attributable cost of $39,219 per infection. Key drivers included severity of illness, congenital heart disease, and ventilator support.
  - The study emphasized the need for effective infection prevention strategies to reduce costs and improve patient outcomes.

Study 2: Risk Factor Analysis**  
  - A case-control study at Boston Children’s Hospital identified independent risk factors for CLABSI, such as prolonged ICU stays, ICU central line placement, and gastrostomy tubes.
  - Patients receiving parenteral nutrition or blood transfusions were particularly vulnerable, with CLABSI patients experiencing higher mortality rates (20.7% vs. 4.9% for controls).
  - Targeted interventions, like antibiotic-coated catheters and rigorous infection control protocols, were recommended for high-risk groups.

Study 3: Predictive Models for CLABSI and Mortality
  - Utilizing data from the MIMIC-III database, this study evaluated logistic regression, gradient-boosted trees, and deep learning for predicting CLABSI, central line placement, and mortality.
  - Gradient-boosted trees excelled in CLABSI prediction (AUC 0.722), while deep learning outperformed in mortality prediction (AUC 0.885).
  - Machine learning demonstrated potential to identify high-risk patients early, but challenges like overfitting and data quality were highlighted.

---

Sampling Strategies for CLABSI Data
The second report focused on selecting optimal sampling methods to improve the representativeness of a highly skewed dataset with over 5000 observations, where only 3% involved CLABSI events.

Key Sampling Methods
Simple Random Sampling:
  - Provided an unbiased snapshot of the population, capturing outliers and overall trends.
  - However, it exhibited high variability due to extreme values, making it less stable for predictive modeling.

Stratified Sampling
  - Divided the population into subgroups (patients with and without CLABSI) and ensured proportional representation.
  - Reduced skewness, variability, and kurtosis, creating a balanced dataset ideal for modeling rare events like CLABSI.

Results and Insights
- Stratified sampling improved the representation of rare events and supported the development of more accurate and generalizable predictive models.
- Simple random sampling, while easier to implement, was less effective for datasets with significant subgroup diversity.

Unified Insights
1. Economic and Clinical Importance:
- CLABSI imposes a substantial financial and clinical burden on PICUs. Effective prevention strategies and predictive modeling can significantly mitigate these impacts.

2. Predictive Modeling:
   - Machine learning models show promise in predicting CLABSI and mortality but require balanced and representative data for accuracy.

3. Sampling as a Foundation:
   - Stratified sampling offers a robust foundation for predictive modeling by addressing data skewness and ensuring representation of rare but critical events.

4. Integrating Approaches:
   - Combining insights from financial analysis, risk factor identification, machine learning, and tailored sampling strategies creates a comprehensive framework for improving CLABSI outcomes.

Conclusion
The findings underscore the urgency of addressing CLABSI in PICUs through data-driven strategies. By leveraging advanced sampling techniques and predictive models, healthcare providers can implement targeted interventions, optimize resource use, and enhance patient care. These combined efforts pave the way for more effective infection control measures and improved healthcare outcomes.
