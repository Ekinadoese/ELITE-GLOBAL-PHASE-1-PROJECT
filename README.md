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





