# Vehicle Insurance Sales Prediction

Determining the intention of vehicle owners to purchase car insurance is of great importance for insurance companies. Accurate forecasts create an opportunity for insurance companies to reach potential customers, optimize their business model and revenue by planning a communication strategy.

An insurance company that provides health insurance to its customers plans to sell car insurance to policyholders of the previous year. Company data to be used to estimate whether customers are interested in vehicle insurance includes demographic information (age, gender, province etc.), vehicle characteristics (age and damage status) and policy information (premium and channel information).

The table below contains the features used in the data set and their explanations.

| Attribute | Description |
| --------- | -------- |
| Musteri_no | Anonymous customer number |
| Cinsiyet | Customer gender (Y / K) |
| Yas | Customer year of birth |
| Ehliyet | Customer license status (Yes / No) |
| Sehir | City where the customer is located |
| Gecmis_police | Does the customer already have car insurance? (Yes / No) |
| Vehicle_yasi | Vehicle age (<1 Year, 1-2 Years, 2-5 Years, 5-10 Years,> 10 Years) |
| Hasar_durumu | Has the customer vehicle damaged in the past? (Y / H) |
| Yillik_prm | Annual premium price |
| Acenta_no | Sales responsible code number (anonymous) |
| Sure | Duration of being insured (health insurance) (days) |
| Sonuc | Customer request (target): interested (1), not interested (0) |


### Data files
**one. `Arac_train.xlsx` ** (254687 observations, 11 attributes, 1 target): The training data you will use to choose your best model.

**2nd. `Arac_test.xlsx` ** (63672 observations, 11 attributes): Note that there is no` Sonuc` column in the test data. This file will be used to generate estimates of the model you selected using training data and upload the results to the Kaggle site.

### Success metric
Your assessment metric for this hackathon is "** ROC_AUC Score **".

### Notes, warnings and suggestions
1. Do not forget to apply any "pre-processing" on the "Train" data, also on the "Test" data.
2. There are no restrictions on the solution to be applied. You can try to solve the problem with any of the Machine Learning models. Remember that it is useful to be flexible about the methods to be used and the techniques to try.
3. The initiative to derive a new feature is entirely left to you.
