Factors Affecting Health Insurance Claims
## 1️⃣ Introduction

This project examines the **factors affecting health insurance claims** using Microsoft Excel analytics tools. The study focuses on identifying the major variables that influence **insurance charges**, such as age, BMI, smoking status, number of children, sex, and region.
## 2️⃣ Background of the Study
Health insurance plays a vital role in the healthcare system, it makes individuals have access to healthcare by providing protection against unexpected medical bills. claims amount differs among indidiuals due to demographic, regional differences e.t.c. older individuals or those with high BMI or smokers pays more medical bills, insight from such analysis insurance companies to develop a fair model and design a wellness programme to reduce preventable health risks. The data set was Imported from kaggle. convert data into table. clean data by checking for duplicate, check and remove blank spaces, converting smokers to text, sorting of sex and region. converting of age, BMI and charges to numbers and creating a new column called smokers code using the if function. With the use of pivot table and pivot chart  i was able to know that the higher  BMI leades to higher charges.  smokers pay 75% of charges while non smokers pay 21% of charges which shows that smokers pay her charges than non-smokers. the number of children has a moderate effect. there is a little variation between regions. This research will enable health insurance companies in making better decision and also creating awareness to the public. 
## 3️⃣ Project Objectives

* To identify key factors influencing health insurance charges
* To analyze relationships between variables (e.g.age vs charges)
* To determine which factors have the strongest impact on claims.
* To build simple predictive insights using Excel tools.
## 4️⃣ Business Questions
1. Does age affect health insurance charges?
2. Does having more children increase insurance costs?
3. How does smoking status influence claims?
4. Which factor has the strongest effect on charges?
5. Are there regional differences in insurance costs?

## 5️⃣ Dataset Description

The dataset contains the following variables:

* **Age**
* **Sex**
* **BMI**
* **Children**
* **Smoker**
* **Region**
* **Charges**

---

## 6️⃣ Methodology

### 🔹 Data Cleaning

* Removed duplicates
* Checked missing values
* To examine data distribution and visualise realtionships using charts and graphs.
* use of correlation and regression analysis to know the infuence of each of the variables on how it affects isurance cost.

* creation of visualisation using excel and power bi to show the average of charges, age, BMI, smokers statues, regionals, differences in claims and gender.
 
*

### 🔹 Exploratory Analysis

* Pivot tables
* Summary statistics


### 🔹 Correlation Analysis

Measured the relationship between:

* Age and Charges
* BMI and Charges
* Children and Charges

### 🔹 Regression Analysis

Used regression models to determine the significance and effect size of predictors on claim cost.


## 7️⃣ Analysis Workflow

```text
Uncleaned Dataset → Cleaned Dataset → Business Questions → Dataset Working → Analysis → Dashboard → Interpretation → Executive Summary

## 8️⃣ Dashboard Features

* KPI cards
* Pivot charts
* Age vs charges trend
* Smoker vs non-smoker comparison
* Regional claim analysis
* Children vs cost insights

## 9️⃣ Interpretation of Results

* **AGE AND INSURANCE CHARGES: The chart shows showed that insurance charges increases as age alos increase. this implies older individuals tends to make more claims than the younger indidual. Age is an iportant factor because health risks and medical needs generally rise with age.
* ** . BMI AND CHARGES: There is a positive realtionship between BMI and Charges especially with individuals with higer BMI values because peple higer body mass are likey to face health-related issues, which will increase insurance expenses. 
* ** SMOKERS: Smoking had the stronedt visible effect on charges, smokers has 79% of charges while non-smokers has 21% of charges theses shoes that smoker pay four times more than the non smokers. smoking increases the risk of  chronic disease and hospital visit making it the  major drivers of insurance claims.
* ** CHILDREN: The study revealed that children has a moderate effect on health insurance charges.
* ** REGION: Regional differences are minimal with only slight variations in average charges. this means location contributes less to insurance cost diffeneces compared to personal health and lifestyle factors.
* ** AGE:Regression analysis shows a significant positive relationship between age and insurance charges. As age increases, insurance costs tend to rise, indicating that older individuals are likely to incur higher claims.
Number of children: The correlation coefficent between children and chareges is 0.068 which indicates a very weak positive relationship between number of children and insurance charges. the regression analysis shows that only 0.46 % of the variation insurance charges is explained by the number of children is not an important predictor of insurance chargs. However, The effect is not statistically significant, suggesting that the number of dependents minimally impacts insurance costs.
* **Children show a weaker positive relationship**.
* BMI moderately contributes to claim increase.
* Regression confirms the statistical significance of major predictors.
## 🔟 Executive Summary

The project shows that **age, smoking status, and BMI are the major factors affecting health insurance claims**, while children have a smaller but positive effect.

The analysis shows that lifestyle factors, especially smoking and BMI, significantly influence health insurance charges. Age also plays an important role, while region has less impact. The regression analysis reveal that the number  of children has a statiscallysignificant but very weak positive effect on the insurance charges. the Model R square is 0.0046 indicates that children explains only 0.46% of variation charges. Although the coefficent suggest that each addidtional child increase charges by approximately 1252, the overall predictive power is low. it is not a major factor affecting health insurance  costs compared to stronger predictors such as smoking,BMI and Age
## 👤 Author

**Beye Bogofanyo**
*Healthcare Data Analytics Portfolio Project*
