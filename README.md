# Causal Inference Analysis on Airline Satisfication Dataset
````diff 
+ (airline-satisfaction-causal-inference)
````
### Quick Summary
***
- **Purpose:** Implement a causal inference analysis on airline passenger satisfaction data to study customer segregation.
- **Dataset Source:**
  - [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
<br><br>

### Detailed Description
***
1. Two treatments are selected: Inflight wifi service and Online boarding.
2. Three learners are implemented: S, T, and X learners.
3. CATE (Conditional Average Treatment Effect) is studied for both treatments. Conditions includes: 
    - whether a customer is travelling for business or not, 
    - whether a customer is a loyal passenger or not, 
    - the flight distance, and 
    - the age of the customer.
4. Visualization: feature importance, SHAP value, and 3D treatment effect plot.
<br><br>

### Preview
***
- Feature Importance using T Learner (Treatment: Inflight Wifi Service)<br>
![Feature Importance](https://user-images.githubusercontent.com/111717563/236928629-fefbc720-d984-4636-b2a5-149695fb9159.png)

- SHAP Value Plot of Good Wifi Service<br>
![SHAP](https://user-images.githubusercontent.com/111717563/236928802-efd82ba8-850b-4412-b83b-48e053ff8e65.png)

- 3D Treatment Effect Plot (Treatment: Inflight Wifi Service, Flight Distance versus Age)<br>
![3D TE Plot](https://user-images.githubusercontent.com/111717563/236931785-b8eea3e6-5efb-485b-9a7a-37b4014a3fa4.png)
