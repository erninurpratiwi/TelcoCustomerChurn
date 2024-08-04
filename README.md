# TelcoCustomerChurn

## Business Problem Understanding
**Context**

A telecommunications company faces challenges in retaining its customers. In the telecommunications industry, churn is a situation where customers stop using the services provided by the company. This data consists of various customer features such as subscription duration, type of service used, and monthly costs. This information is important to analyze the reasons for customer churn and help companies develop strategies to improve customer retention.

**Problem Statement**

A telecommunications company is experiencing a high level of customer churn, which has the potential to reduce revenue and hinder business growth. This problem requires identifying the factors that cause churn so that the company can take appropriate actions to reduce it. Understanding these factors will help the company design a more effective customer retention program.

In the business world, there are terms Acquisition Cost and Retention Cost. Acquisition Cost is the cost incurred by the company to get new buyers or customers. Retention Cost is the cost incurred by the company to retain existing customers.

In reality, we as humans cannot predict which customers will stay and which will leave our product. If we wrongly predict which customers will actually churn, but we are sure they will stay, then the costs incurred will be greater. Some sources say that the cost of taking is five times greater than the cost of handling.

**Goals**
The objectives of this analysis are:

- Characteristics of customers who leave the service (`yes` Churn / class:1 )
- Prediction of the chances of customers to churn (Stop using the service)
- Strategy on how to prevent customers from moving
- The most significant factors that influence customers to churn

**Conclusion**
1. **TechSupport_No internet service**:
- Customers who do not have internet service have a strong negative SHAP value, indicating they are less likely to churn.
- Conversely, having technical support (but no internet service) has a strong positive impact on churn.

2. **Tenure**:
- Longer tenure has a strong negative impact on churn, indicating customers who have been with the company for a long time are less likely to churn.
- Short tenure is associated with a higher likelihood of churn.

3. **InternetService_Fiber optic**:
- Customers with fiber optic internet service are more likely to churn, as indicated by the positive SHAP value.

4. **MonthlyCharges**:
- Higher monthly charges are associated with a higher likelihood of churn, as indicated by the positive SHAP value for high monthly charges.

5. **Contract (One year, Two year)**:
- One year and two year contracts both have negative SHAP values, indicating that longer contracts reduce the likelihood of churn.
- The impact is more pronounced for two year contracts.
