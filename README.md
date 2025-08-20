# Taxi Fare Prediction from Distance

## Project Overview
This project predicts taxi fares based on trip distance using **linear regression**. The model identifies:  

- **Base Fare (Fixed cost)** – the minimum fare even for very short trips  
- **Fare per Kilometer** – additional fare charged per km  

The dataset includes trips with columns like `Distance_km`, `Fare_Rs`, `Duration_min`, `Traffic_Level`, `Driver_Rating`, and more. For this analysis, only `Distance_km` is used as input.

---

## Visualization
The relationship between distance and fare is visualized in the plot below:

- **Red dots** → Actual fares from the dataset  
- **Blue line** → Predicted fares from the regression model  

![Taxi Fare Regression](plots/linear_regression_graph.png)  
*Figure: Linear regression prediction of taxi fare based on distance*

> The plot shows a clear linear trend, validating the use of linear regression for predicting taxi fares.

---

## Model Interpretation
- **Intercept (Base Fare)**: Represents the minimum fare charged regardless of distance.  
- **Coefficient (Fare per km)**: Indicates how much the fare increases for each additional kilometer.  
- The linear trend confirms that the fare structure is mostly **proportional to distance**, making linear regression an appropriate model.  
- Outliers or deviations in the scatter plot can indicate unusual trips or data entry errors.

---

## Conclusion
- Linear regression effectively models the taxi fare structure: **fixed base fare + variable per km**.  
- Visualization confirms the **strong linear relationship** between distance and fare.  
- Model interpretation helps understand the **underlying fare calculation** and detect anomalies in the data.