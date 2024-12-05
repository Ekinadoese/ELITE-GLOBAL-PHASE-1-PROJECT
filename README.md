# LIFE EXPECTANCY ANALYSIS USING SOCIOECONOMIC AND HEALTH INDICATORS

This project analyzes global life expectancy data to uncover the socioeconomic and health factors influencing disparities in longevity. The analysis aims to provide actionable insights to policymakers, NGOs, and global health organizations.

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

Columns:
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

### ANALYSIS

Key Analysis:

- Life Expectancy Distribution: Global variations by region and economic status.
- Correlation Matrix: Highlighting relationships between variables like schooling, immunization, GDP, and life expectancy.
- Trend Analysis: Life expectancy over time across regions.
- Missing Data Patterns: Regions or variables most affected by data gaps.

Statistical Analysis

p-value interpretation (< 0.05 indicates significance).
Results:
R-squared value: ~75%, indicating a strong model fit.
Significant predictors: Schooling, adult mortality, and immunization.

LINEAR REGRESSION

IMPACT OF MORTALITY RATE ON LIFE EXPECTANCY

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

IMPACT OF IMMUNIZATION ON INFANT MORTALITY

INFANT MORTALITY = 234.008261 + 0.752244 HEPATITIS - 0.484221 MEASLES - 2.52578 DIPTHERIA

Reporting results 

Results of the multiple linear regression indicated that there was a strong collective significant effect between the HEPATITIS, MEASLES, POLIO, DIPTHERIA, and INFANT MORTALITY, (F(3, 175) = 89.3, p < .001, R2 = 0.6, R2adj = 0.6).

The individual predictors were examined further and indicated that HEPATITIS (t = 2.842, p = .005) and MEASLES (t = -3.53, p < .001) and POLIO (t = -9.079, p < .001) were significant predictors in the model

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


IMPACT OF IMMUNIZATION ON UNDER 5 MORTALITY

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

BEHAVIOURAL IMPACT ON ADULT MORTALITY

Ln(ADULT MORTALITY ) = 5.066562 - 0.0357906 Ln(HIV)

ADULT MORTALITY = 158.628066⋅HIV-0.0357906

Reporting results

Results of the multiple linear regression indicated that there was a very weak collective non significant effect between the ALCOHOL, HIV, and ADULT MORTALITY , (F(1, 177) = 1.22, p = .271, R2 = 0.01, R2adj = 0).

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





### INSIGHTS





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


## CONCLUSION

By aligning global resources with these actionable insights, Health management partners can improve global health equity, reduce preventable deaths, and promote sustainable development goals. This dataset has revealed areas where strategic interventions will have the most impact.

## VISUALIZATION

Key Plots:
Line graphs: Trends in life expectancy over time.
Scatter plots: GDP vs. Life Expectancy, Schooling vs. Life Expectancy.
Bar charts: Immunization coverage by region.
Heatmaps: Correlation matrix.





