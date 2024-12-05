# LIFE EXPECTANCY ANALYSIS USING SOCIOECONOMIC AND HEALTH INDICATORS

This project analyzes global life expectancy data to uncover the socioeconomic and health factors influencing disparities in longevity. The analysis aims to provide actionable insights to policymakers, NGOs, and global health organizations. This comprehensive analysis can serve as the foundation for Elite Global AI's public health initiatives and predictive modeling strategies. 

## TABLE OF CONTENT
- [PROJECT TITLE](PROJECT-TITLE)
- [AIMS](AIMS)
- [OBJECTIVES](OBJECTIVES)
- [PROPOSED INSIGHTS](PROPOSED-INSIGHTS)
- [DATA SOURCES](DATA-SOURCES)
- [DATA](DATA)
- [TOOLS USED](TOOLS-USED)
- [DATA CLEANING AND PREPARATION](DATA-CLEANING-AND-PREPARATION)
- [ANALYSIS AND INSIGHTS](ANALYSIS-AND-INSIGHTS)
- [CONCLUSION](CONCLUSION)
- [RECOMMENDATION](RECOMMENDATION)
- [VISUALIZATION](VISUALIZATION)
- [PRESENTATION SLIDE](PRESENTATION-SLIDE)
## PROJECT TITLE 

## LIFE EXPECTANCY ANALYSIS USING SOCIOECONOMIC AND HEALTH INDICATORS

## AIMS

To explore and analyze global life expectancy data, uncovering the socioeconomic, health, and environmental factors that contribute to disparities in longevity. The project seeks to provide actionable recommendations that support policy decisions and strategic interventions to improve global health outcomes.

## OBJECTIVES

- Data Cleaning: Handle missing values, standardize data, and address outliers for accurate analysis.
- Exploratory Data Analysis (EDA): Explore trends, distributions, and correlations in life expectancy and associated variables.
- Statistical Analysis: Quantify relationships and identify key predictors influencing life expectancy.
- Visualization: Use clear and impactful visuals to communicate findings effectively.
- Actionable Insights: Provide evidence-based recommendations to stakeholders for improving health and longevity.
- Presentation: Summarize findings in a professional report and presentation format for both technical and non-technical audiences.

## PROPOSED INSIGHTS

This project aims to uncover:
- **Key Predictors of Life Expectancy:** How factors like GDP, schooling, immunization, and mortality rates impact global life expectancy trends.
- **Regional Disparities:** Identify regions or countries lagging behind in life expectancy and their associated causes.
- **Health System Gaps:** Highlight areas of opportunity, such as immunization coverage and healthcare access, to improve outcomes.
- **Economic Impact:** Understand how economic indicators like GDP per capita influence healthcare quality and life expectancy.
- **Predictive Trends:** Forecast future trends in life expectancy based on historical data and key predictors.
- **Policy Recommendations:** Develop strategies to address disparities and promote equitable health outcomes globally

## DATA SOURCES

The data for this project was gotten from kaggle. [Click Here](https://www.kaggle.com/datasets/shreyasg23/life-expectancy-averaged-dataset?resource=download) to download dataset

## DATA

The dataset appears well-structured and contains 179 rows and 20 columns [Click Here to download](https://www.kaggle.com/datasets/shreyasg23/life-expectancy-averaged-dataset?resource=download). It includes data related to health metrics, economy, and demographic indicators. 

**COLUMNS**
- **Country:** Name of the country.
- **Region:** Geographic region.
- **Year:** Year of observation.
- **Infant_deaths:** Number of infant deaths per 1000 live births.
- **Under_five_deaths:** Number of deaths under five years of age per 1000 live births.
- **Adult_mortality:** Adult mortality rate (probability of dying between 15 and 60 years per 1000 population).
- **Alcohol_consumption:** Per capita alcohol consumption (liters of pure alcohol).
- **Hepatitis_B:** Percentage of immunization coverage for Hepatitis B.
- **Measles:** Number of reported cases of measles.
- **BMI:** Average Body Mass Index.
- **Polio:** Percentage of immunization coverage for Polio.
- **Diphtheria:** Percentage of immunization coverage for Diphtheria.
- **Incidents_HIV:** Incidents of HIV (per 1000).
- **GDP_per_capita:** Gross Domestic Product per capita.
- **Population_mln:** Population in millions.
- **Thinness_ten_nineteen_years:** Prevalence of thinness for age group 10-19 years.
- **Thinness_five_nine_years:** Prevalence of thinness for age group 5-9 years.
- **Schooling:** Average years of schooling.
- **Economy_status:** Economic classification (1 = developed, 0 = developing).
- **Life_expectancy:** Average life expectancy at birth

### Key Metrics

**Country, Region:** Geographic identifiers.

**Year:** All entries are for mid 2007 

**Life Expectancy:** Target variable, measured in years.

**Infant Deaths, Under Five Deaths, Adult Mortality:** Mortality metrics.

**Health Indicators:** Alcohol consumption, Hepatitis B vaccination rate, Measles, BMI, Polio, Diphtheria rates, and HIV incidents.

**Economic Metrics:** GDP per capita, Economy status (binary: 1 likely indicating developed status).

**Demographics:** Population in millions, schooling (years).

**Thinness:** Metrics for children and teens.


## TOOLS USED

This project leverages a range of powerful tools to efficiently collect, clean, analyze, and visualize sales data:

- **Microsoft Excel**: Used for initial data exploration, cleaning, and transformation, ensuring data consistency and accuracy.
- **SQL**: Employed for querying and managing data from relational databases, facilitating data extraction and transformation.
- **Power BI**: Utilized to build interactive dashboards and visualizations, providing insights through dynamic reports.
- **LINEAR REGRESSION CALCULATOR and PYTHON**: Used for linear regression and predictive analysis
- **DATATAB and EVIEWS**: Employed for Statistical Analysis

These tools collectively enabled seamless data management and visualization, ensuring accurate reporting and informed decision-making.

## DATA CLEANING AND PREPARATION

The data cleaning process involved several key steps to ensure the dataset was accurate, consistent, and ready for analysis:

- Data Collection: The initial dataset was downloaded from [kaggle.com](https://kaggle.com)
- Data Inspection: A thorough review of the dataset was conducted to identify any discrepancies, missing values, or outliers that could affect the analysis.
- Standardization: Data formats were standardized, including date formats and categorical values, to ensure uniformity across the dataset.
- Duplicate Removal: Duplicate entries were identified and removed to avoid skewed analysis results.
- Data Validation: Final checks were performed to confirm the accuracy of data entries and to ensure that all values fell within expected ranges.
- Data Loading: Data was loaded into analytics tools for analysis

By following these steps, the dataset was cleaned and optimized for accurate analysis, leading to reliable insights and actionable recommendations.

## ANALYSIS AND INSIGHTS

## DESCRIPTIVE STATISTICS

![image](https://github.com/user-attachments/assets/38405925-ce24-421a-849b-b5c44492d810)

![image](https://github.com/user-attachments/assets/da8cb9ff-be8a-45d2-ac50-5cc6b8e3ac2e)

![image](https://github.com/user-attachments/assets/8a6cd958-df00-42ce-ac77-a4fc722f1431)

### Key Findings
1. Education and immunization significantly improve life expectancy in developing nations.
2. High adult mortality and HIV prevalence strongly correlate with lower life expectancy.
3. Economic growth (GDP per capita) is a pivotal driver of healthcare access and outcomes.
4. Improved nutritional status is critical for reducing under-five mortality.
5. Life Expectancy Disparities: Clear divide between developed (>75 years) and developing countries (~60 years). Major drivers include education, immunization, and GDP per capita.
6. Health Challenges in Developing Regions: Higher infant mortality, under-five deaths, and malnutrition hinder sustainable health outcomes.
7. Immunization Gaps: Hepatitis B and Polio remain critical focus areas, particularly in low-income regions.
8. HIV Epidemic: Adult mortality is heavily impacted by HIV, highlighting a need for sustained healthcare interventions.

### Predictive Trends
1. **Rising Life Expectancy:** Continued investment in schooling and immunization can add up to 5-7 years to life expectancy in low-GDP regions by 2030.
2. **Target regions:** Sub-Saharan Africa and South Asia.
3. **Impact of Economic Growth:** Projected GDP increases in developing countries may enable higher healthcare spending, boosting immunization rates and reducing mortality.
4. **Immunization Focus:** Improving Hepatitis B coverage from ~65% to 90% in low-performing regions can reduce infant mortality by up to 15%.
5. **Nutrition Intervention:** Addressing thinness in children through school feeding programs and nutritional education may enhance youth survival and cognitive outcomes.

## RECOMMENDATION
1. **Strengthen Educational Programs:**
   - Expand access to schooling to build long-term health equity and increase life expectancy.
   - Partner with NGOs to enhance adult literacy and healthcare awareness.
2. **Expand Immunization Coverage:**
   - Improve immunization programs in low-GDP countries.
   - Implement targeted campaigns for Hepatitis B and Diphtheria.
   - Integrate vaccination programs with school attendance incentives.
3. **Invest in Healthcare Infrastructure:**
   - Address healthcare disparities through targeted funding.
   - Allocate resources for rural health centers in regions with high mortality rates.
   - Deploy mobile clinics to address healthcare deserts.
4. **Focus on Nutrition:**
   - Launch region-specific programs addressing child malnutrition.
   - Partner with local governments to enhance food security.
5. **Monitor and Reduce HIV Impact:**
   - Increase funding for antiretroviral therapy.
   - Focus on education to reduce transmission and stigma.

## REGRESSION

IMPACT OF HEALTH INDICATORS ON LIFE EXPECTANCY

![image](https://github.com/user-attachments/assets/785c4d1b-0d75-4606-9cbf-68e4426388a9)

![image](https://github.com/user-attachments/assets/5cba33e6-dbfa-47db-a2aa-e768d780fe48)

![image](https://github.com/user-attachments/assets/36f12927-5b6d-44e9-8fbb-42dccc747730)

![image](https://github.com/user-attachments/assets/d157d178-e133-4d27-8fe3-78c74b613d9b)

LIFE EXPECTANCY = 36.733909 - 0.125226 HEPATITIS + 0.0564321 MEASLES + 0.436975 POLIO - 1.783662 HIV + 0.433237 ALCOHOL

Reporting results 

Results of the multiple linear regression indicated that there was a very strong collective significant effect between the HEPATITIS, MEASLES, POLIO, DIPTHERIA, HIV, ALCOHOL, and LIFE EXPECTANCY, (F(5, 173) = 95.16, p < .001, R2 = 0.73, R2adj = 0.73).

The individual predictors were examined further and indicated that HEPATITIS (t = -2.764, p = .006) and MEASLES (t = 2.145, p = .033) and POLIO (t = 8.592, p < .001) and DIPTHERIA (t = -11.184, p < .001) and HIV (t = 4.294, p < .001) were significant predictors in the model.

![image](https://github.com/user-attachments/assets/80866812-2ca0-4e42-801b-d87e2e28693b)

![image](https://github.com/user-attachments/assets/e5639a38-13d6-452a-9ce1-c7767b93a40a)

![image](https://github.com/user-attachments/assets/16fbec74-9aec-4b15-84e9-d41783cf1ef6)

Multiple linear regression

The backward stepwise method is used to produce an initial screening of the predictors.


1. Y and X relationship

R square (R2) equals 0.733353. It means that the predictors (Xi) explain 73.3% of the variance of Y.

Adjusted R square equals 0.725647.

The coefficient of multiple correlation (R) equals 0.85636. It means that there is a very strong correlation between the predicted data (ŷ) and the observed data (y).

2. Goodness of fit

Overall regression: right-tailed, F(5,173) = 95.159622, p-value = 0. Since p-value < α (0.05), we reject the H0.
The linear regression model, Y = b0+ b1X1 +...+bpXp + ε, provides a better fit than the model without the independent variables resulting in, Y = b0 + ε.

The following independent variable is not significant as predictor for Y: DIPTHERIA.
Therefore it was excluded from the model.

The Y-intercept (b): two-tailed, T = 14.680723, p-value = -2.22045e-16. Hence b is significantly different from zero.

Validation

Residual normality

linear regression assumes normality for residual errors. Shapiro Wilk p-value equals 0.1006. It is assumed that the data is normally distributed.

Homoscedasticity - homogeneity of variance

The White test p-value equals 0.000101859 (F=9.689145). It is assumed that the variance is not homogeneous.

Multicollinearity - intercorrelations among the predictors (Xi)

There is a low multicollinearity concern as some of the VIF values are bigger than 2.5.

Priori power - of the entire model (6 predictors)

The priori power should be calculated before running the regression.
The power to test the entire model is strong: 0.9891

![image](https://github.com/user-attachments/assets/ae735a28-ba7e-4d98-af6d-681e8406a8eb)

![image](https://github.com/user-attachments/assets/54cf36f9-548c-4a1b-9461-43e0b016c1d5)

![image](https://github.com/user-attachments/assets/009c89c1-bf15-4fbd-882c-608f126b6fa5)


IMPACT OF MORTALITY RATE ON LIFE EXPECTANCY

![image](https://github.com/user-attachments/assets/9debfdf2-6544-4896-b80f-01f17889e0cb)

![image](https://github.com/user-attachments/assets/f0b6984f-4e3a-43c8-b940-e570af6d2840)

![image](https://github.com/user-attachments/assets/a53ff774-cdca-4655-be87-ba70ad76e6bc)

LIFE EXPECTANCY = 82.81321 - 0.159696 INFANT MORTALITY - 0.0474026 ADULT MORTALITY

Reporting results 

Results of the multiple linear regression indicated that there was a very strong collective significant effect between the INFANT MORTALITY, UNDER 5 MORTALITY, ADULT MORTALITY, and LIFE EXPECTANCY, (F(2, 176) = 3391.31, p < .001, R2 = 0.97, R2adj = 0.97).

The individual predictors were examined further and indicated that INFANT MORTALITY (t = -23.126, p < .001) and UNDER 5 MORTALITY (t = -28.69, p < .001) were significant predictors in the model, and ADULT MORTALITY was non significant predictor in the model.

![image](https://github.com/user-attachments/assets/1663ffec-b21f-47b8-a702-54794abf817b)

![image](https://github.com/user-attachments/assets/ae9cc3c8-3a29-4fd3-b638-beae19fd16a8)

Multiple linear regression

The backward stepwise method is used to produce an initial screening of the predictors. 

1. Y and X relationship

R square (R2) equals 0.974708. It means that the predictors (Xi) explain 97.5% of the variance of Y.

Adjusted R square equals 0.97442.

The coefficient of multiple correlation (R) equals 0.987273. It means that there is a very strong correlation between the predicted data (ŷ) and the observed data (y)

2. Goodness of fit

Overall regression: right-tailed, F(2,176) = 3391.310675, p-value = 0. Since p-value < α (0.05), we reject the H0.

The linear regression model, Y = b0+ b1X1 +...+bpXp + ε, provides a better fit than the model without the independent variables resulting in, Y = b0 + ε.

The following independent variable is not significant as predictor for Y: UNDER 5 MORTALITY.
Therefore it was excluded from the model.

The Y-intercept (b): two-tailed, T = 369.836524, p-value = 0. Hence b is significantly different from zero.

Validation

Residual normality

linear regression assumes normality for residual errors. Shapiro Wilk p-value equals 0.5306. It is assumed that the data is normally distributed.

Homoscedasticity - homogeneity of variance

The White test p-value equals 0.0160214 (F=4.232463). It is assumed that the variance is not homogeneous.

Multicollinearity - intercorrelations among the predictors (Xi)

There is a low multicollinearity concern as some of the VIF values are bigger than 2.5.

Priori power - of the entire model (3 predictors)

The power to test the entire model is strong: 0.9979

![image](https://github.com/user-attachments/assets/be83cf13-311a-4b7e-b4d6-a5972fa6bd3c)

![image](https://github.com/user-attachments/assets/c4e42365-f59d-4cc3-9970-f29175fb6891)

![image](https://github.com/user-attachments/assets/3be60b83-5543-4489-bccf-5acc3c00472f)

IMPACT OF HEALTH INDICATORS ON INFANT MORTALITY

INFANT MORTALITY = 234.008261 + 0.752244 HEPATITIS - 0.484221 MEASLES - 2.52578 DIPTHERIA

Reporting results 

Results of the multiple linear regression indicated that there was a strong collective significant effect between the HEPATITIS, MEASLES, POLIO, DIPTHERIA, and INFANT MORTALITY, (F(3, 175) = 89.3, p < .001, R2 = 0.6, R2adj = 0.6).

The individual predictors were examined further and indicated that HEPATITIS (t = 2.842, p = .005) and MEASLES (t = -3.53, p < .001) and POLIO (t = -9.079, p < .001) were significant predictors in the model

![image](https://github.com/user-attachments/assets/abebebe6-3c3b-4212-a2db-cbc367b0ebe7)

![image](https://github.com/user-attachments/assets/36eb2327-23b5-4519-8f36-866dd219877f)

![image](https://github.com/user-attachments/assets/64515bc3-5507-44cd-8176-3b3be4ea3b6c)

Multiple linear regression

The backward stepwise method is used to produce an initial screening of the predictors.

1. Y and X relationship

R square (R2) equals 0.604883. It means that the predictors (Xi) explain 60.5% of the variance of Y.

Adjusted R square equals 0.59811.

The coefficient of multiple correlation (R) equals 0.777743. It means that there is a strong correlation between the predicted data (ŷ) and the observed data (y).

2. Goodness of fit

Overall regression: right-tailed, F(3,175) = 89.302414, p-value = -2.22045e-16. Since p-value < α (0.05), we reject the H0.

The linear regression model, Y = b0+ b1X1 +...+bpXp + ε, provides a better fit than the model without the independent variables resulting in, Y = b0 + ε.

The following independent variable is not significant as predictor for Y: POLIO.
Therefore it was excluded from the model.

The Y-intercept (b): two-tailed, T = 17.893084, p-value = 3.33067e-16. Hence b is significantly different from zero.

Validation

Residual normality

linear regression assumes normality for residual errors. Shapiro Wilk p-value equals 0.00004998. It is assumed that the data is not normally distributed.

Homoscedasticity - homogeneity of variance

The White test p-value equals 1.79484e-10 (F=25.561831). It is assumed that the variance is not homogeneous.

Multicollinearity - intercorrelations among the predictors (Xi)

Priori power - of the entire model (4 predictors)

The power to test the entire model is strong: 0.9957

![image](https://github.com/user-attachments/assets/cef90397-d01c-4a00-bb3c-189cd1e95e01)

![image](https://github.com/user-attachments/assets/40e99fc4-ec37-419b-abfd-34b108c406fa)

![image](https://github.com/user-attachments/assets/4dc64a56-e1a1-4366-8208-5b9d474aa622)


IMPACT OF HEALTH INDICATORS ON UNDER 5 MORTALITY

![image](https://github.com/user-attachments/assets/e3fb7ca9-81f0-4230-a566-7f89997b0035)

![image](https://github.com/user-attachments/assets/03002f4d-e897-4c35-a80d-8e1d6ac01f24)

![image](https://github.com/user-attachments/assets/58475115-d3ac-4c76-8832-fc2db34da617)

Ln(UNDER 5 MORTALITY) = 20.447249 + 1.807709 Ln(HEPATITIS) - 1.108484 Ln(MEASLES) - 2.227308 Ln(POLIO) - 2.375264 Ln(DIPTHERIA)

UNDER 5 MORTALITY = 758799846.6⋅HEPATITIS1.807709⋅MEASLES-1.108484⋅POLIO-2.227308⋅DIPTHERIA-2.375264

Reporting results

Results of the multiple linear regression indicated that there was a strong collective significant effect between the HEPATITIS, MEASLES, POLIO, DIPTHERIA, and UNDER 5 MORTALITY, (F(4, 174) = 46.71, p < .001, R2 = 0.52, R2adj = 0.51).

The individual predictors were examined further and indicated that HEPATITIS (t = 3.369, p < .001) and MEASLES (t = -4.69, p < .001) and POLIO (t = -1.993, p = .048) and DIPTHERIA (t = -2.057, p = .041) were significant predictors in the model.

![image](https://github.com/user-attachments/assets/ef62281f-3901-4f30-884d-7e05d22afacc)

![image](https://github.com/user-attachments/assets/b1aa2339-aba2-48ec-a03e-93a3d3390bf7)

Multiple linear regression

The backward stepwise method is used to produce an initial screening of the predictors. 

1. Y and X relationship

R square (R2) equals 0.517791. It means that the predictors (Xi) explain 51.8% of the variance of Y.

Adjusted R square equals 0.506706.

The coefficient of multiple correlation (R) equals 0.719577. It means that there is a strong correlation between the predicted data (ŷ) and the observed data (y).

2. Goodness of fit

Overall regression: right-tailed, F(4,174) = 46.709926, p-value = 0. Since p-value < α (0.05), we reject the H0.

The linear regression model, Y = b0+ b1X1 +...+bpXp + ε, provides a better fit than the model without the independent variables resulting in, Y = b0 + ε.

All the independent variables (Xi) are significant.

The Y-intercept (b): two-tailed, T = 13.68948, p-value = 0. Hence b is significantly different from zero.

Validation

Residual normality

linear regression assumes normality for residual errors. Shapiro Wilk p-value equals 0.08468. It is assumed that the data is normally distributed.


Homoscedasticity - homogeneity of variance

The White test p-value equals 2.20049e-10 (F=25.299179). It is assumed that the variance is not homogeneous.

Multicollinearity - intercorrelations among the predictors (Xi)

There is a high multicollinearity concern as some of the VIF values are bigger than 10

Priori power - of the entire model (4 predictors)

The power to test the entire model is strong: 0.9927

![image](https://github.com/user-attachments/assets/94cdf720-cdef-47fa-94a8-b1bcff6c5757)

![image](https://github.com/user-attachments/assets/a2dd8e75-ce96-4797-bfc5-1bc33dbf9099)

![image](https://github.com/user-attachments/assets/de10ce84-43c9-44b3-b6e0-2f08be97a924)

![image](https://github.com/user-attachments/assets/982df6e7-9ce6-45b5-8038-dbbbb365a5e5)

IMPACT OF HEALTH INDICATORS ON ADULT MORTALITY

Ln(ADULT MORTALITY ) = 5.066562 - 0.0357906 Ln(HIV)

ADULT MORTALITY = 158.628066⋅HIV-0.0357906

Reporting results

Results of the multiple linear regression indicated that there was a very weak collective non significant effect between the ALCOHOL, HIV, and ADULT MORTALITY , (F(1, 177) = 1.22, p = .271, R2 = 0.01, R2adj = 0).

![image](https://github.com/user-attachments/assets/359cac56-8b78-4de2-9ddb-390ff6233d38)

![image](https://github.com/user-attachments/assets/13ef8dd5-f2d0-4c00-a451-72458a52793a)

![image](https://github.com/user-attachments/assets/7469d099-c613-42a2-8f03-5c33cccdcbdb)

Multiple linear regression

The backward stepwise method is used to produce an initial screening of the predictors. 

1. Y and X relationship

R square (R2) equals 0.00683623. It means that the predictors (Xi) explain 0.7% of the variance of Y.

Adjusted R square equals 0.00122513.

The coefficient of multiple correlation (R) equals 0.0826815. It means that there is a very weak correlation between the predicted data (ŷ) and the observed data (y).

2. Goodness of fit

Overall regression: right-tailed, F(1,177) = 1.218342, p-value = 0.271185. Since p-value ≥ α (0.05), we accept the H0.

The linear regression model, Y = b0+ b1X1 +...+bpXp + ε, doesn't provide a better fit than the model without the independent variables resulting in, Y = b0 + ε.

The following independent variable is not significant as predictor for Y: Ln(ALCOHOL).
Therefore it was excluded from the model.

The remaining variable: Ln(HIV) is not significant

The Y-intercept (b): two-tailed, T = 95.579246, p-value = 0. Hence b is significantly different from zero.

Validation

Residual normality

linear regression assumes normality for residual errors. Shapiro Wilk p-value equals 0.05037. It is assumed that the data is normally distributed.


Homoscedasticity - homogeneity of variance

The White test p-value equals 0 (F=3980.296512). It is assumed that the variance is not homogeneous.

Multicollinearity - intercorrelations among the predictors (Xi)

There is no multicollinearity concern as all the VIF values are smaller than 2.5 .


Priori power - of the entire model (2 predictors)

The power to test the entire model is strong: 0.9994.

![image](https://github.com/user-attachments/assets/247d1b2a-a763-46e9-a7f5-acf6192e6d67)

![image](https://github.com/user-attachments/assets/71c6bea8-3345-42ea-8e44-f894510bf156)

![image](https://github.com/user-attachments/assets/935317d3-c8c4-4472-805f-1546722da9f2)

IMPACT OF SOCIAL INDICATORS ON LIFE EXPECTANCY

![image](https://github.com/user-attachments/assets/d6c8fc99-14bd-47d8-ac90-2720feec9679)

LIFE EXPECTANCY = 54.172091 + 0.000140947 GDP PER CAPITAL + 1.709834 SCHOOLING

Reporting results 

Results of the multiple linear regression indicated that there was a strong collective significant effect between the GDP PER CAPITAL, POPULATION, SCHOOLING, and LIFE EXPECTANCY, (F(2, 176) = 122.04, p < .001, R2 = 0.58, R2adj = 0.58).

The individual predictors were examined further and indicated that GDP PER CAPITAL (t = 4.336, p < .001) and POPULATION (t = 9.767, p < .001) were significant predictors in the model.

![image](https://github.com/user-attachments/assets/63fbf098-8c31-4818-a083-b011fb766bc0)

![image](https://github.com/user-attachments/assets/f8cb9e73-fea8-4fd2-98e9-1abe2a3e929d)

Multiple linear regression
The backward stepwise method is used to produce an initial screening of the predictors. 

1. Y and X relationship

R square (R2) equals 0.581039. It means that the predictors (Xi) explain 58.1% of the variance of Y.

Adjusted R square equals 0.576278.

The coefficient of multiple correlation (R) equals 0.762259. It means that there is a strong correlation between the predicted data (ŷ) and the observed data (y).

2. Goodness of fit

Overall regression: right-tailed, F(2,176) = 122.043537, p-value = 0. Since p-value < α (0.05), we reject the H0.

The linear regression model, Y = b0+ b1X1 +...+bpXp + ε, provides a better fit than the model without the independent variables resulting in, Y = b0 + ε.

The following independent variable is not significant as predictor for Y: POPULATION.
Therefore it was excluded from the model.

The Y-intercept (b): two-tailed, T = 43.509514, p-value = -2.22045e-16. Hence b is significantly different from zero.

Validation

Residual normality

linear regression assumes normality for residual errors. Shapiro Wilk p-value equals 0.001187. It is assumed that the data is not normally distributed.

Homoscedasticity - homogeneity of variance

The White test p-value equals 0 (F=63.476097). It is assumed that the variance is not homogeneous.

Multicollinearity - intercorrelations among the predictors (Xi)
There is no multicollinearity concern as all the VIF values are smaller than 2.5 .

Priori power - of the entire model (3 predictors)

The power to test the entire model is strong: 0.9979

![image](https://github.com/user-attachments/assets/741d7884-ebe2-4b2d-b31e-eb75df1fdc6a)

![image](https://github.com/user-attachments/assets/86fb4b89-c85e-4a4b-95b8-a95889bc9877)


## Comprehensive Summary of Regression Models

LIFE EXPECTANCY Regression Models:

Key Predictors:

Negative Impact: HIV significantly decreases life expectancy (t = -1.783662, p < 0.001).

Positive Impact: Polio vaccinations and alcohol consumption contribute positively to life expectancy.

GDP per capita and schooling were strong predictors of life expectancy (R² = 0.58), with schooling showing a notable influence.
Insights:

Economic and educational factors significantly enhance life expectancy. Public health measures, particularly targeting HIV and improving vaccination rates, would have the most immediate life-extending effects.

Alcohol consumption's positive association could indicate its proxy for healthcare access or a social determinant rather than a direct health benefit.

INFANT MORTALITY:

Key Predictors:

Hepatitis increases infant mortality, while measles and diphtheria show a protective relationship when controlled for other factors (R² = 0.52).

Insights:

Vaccination campaigns targeting diseases like measles, polio, and diphtheria are critical for reducing infant mortality. Hepatitis prevalence requires more aggressive mitigation strategies to minimize its impact on vulnerable populations.

UNDER-5 MORTALITY:

Key Predictors:

Diseases like hepatitis (positive association) and measles, polio, and diphtheria (negative associations) collectively explain 51.8% of the variance in under-5 mortality.

Insights:
Like infant mortality, under-5 mortality is closely tied to vaccination rates and disease management. Effective hepatitis vaccination and broader coverage for childhood immunization could significantly improve outcomes.

ADULT MORTALITY:

Key Predictors:

HIV was the only predictor tested and showed a weak correlation with adult mortality (R² = 0.01), indicating that other factors might be more important predictors.

Insights:

HIV alone does not explain adult mortality variations significantly in this dataset. This suggests the need for more comprehensive datasets encompassing socio-economic, environmental, and healthcare factors.

Key Insights

Vaccination and Public Health:

Polio, measles, and diphtheria vaccines have the most significant positive effect on life expectancy and reductions in child mortality. Expanding immunization coverage could lead to substantial health improvements.

Hepatitis emerges as a consistent risk factor across multiple models, underscoring the need for better prevention and treatment strategies.

Economic and Educational Drivers:

Higher GDP per capita and years of schooling are strongly correlated with increased life expectancy. Economic growth policies and universal education initiatives are vital long-term investments for global health improvement.

Disease-Specific Recommendations:

While some diseases like HIV strongly correlate with life expectancy, the analysis suggests a broader focus on multi-disease interventions, particularly for early childhood illnesses.

Predictive Analysis

Short-term Predictions:

Countries increasing their GDP per capita and schooling years could experience measurable life expectancy improvements over the next decade, provided that healthcare and immunization efforts are sustained.

Reducing hepatitis prevalence alone could significantly decrease infant and under-5 mortality rates.

Long-term Trends:

Vaccination coverage expansion will lead to a gradual decline in both infant and under-5 mortality. The cumulative effect of education and healthcare infrastructure investment will reflect in rising life expectancy across regions.

Recommendations

Enhance Immunization Campaigns:

Target under-immunized areas for polio, measles, and diphtheria vaccines.

Introduce more comprehensive hepatitis control programs, including vaccination and treatment subsidies.

Invest in Education and Economic Growth:

Policies that improve schooling access will yield long-term health dividends.

Increase investments in healthcare infrastructure to translate economic growth into public health benefits.

Expand Data Scope:

Incorporate socio-economic and environmental variables into future models to better understand adult mortality.

## CONCLUSION

By aligning global resources with these actionable insights, Health management partners can improve global health equity, reduce preventable deaths, and promote sustainable development goals. This dataset has revealed areas where strategic interventions will have the most impact.

## VISUALIZATION

![image](https://github.com/user-attachments/assets/874805cf-3824-4354-97f1-8d843f5e752f)


![image](https://github.com/user-attachments/assets/edb87790-9aca-40c5-bf0a-e7b919be1154)

## PRESENTATION SLIDE






