DSATermProject
# Identifying State-Level Correlates of Car Fatalities in U.S. States.
Ayesha Musharaf - 33617

# Contents
1. [Project Overview](#Proj-Overview)
2. [Research Questions and Objectives](#rqao)
3. [Motivation](#moti)
4. [Datasets](#datase)
5. [Hypothesis](#hypo)
6. [Dataset Analysis Plan](#dap)
7. [Tools and Technologies](#tat)
8. [Limitations and Future Work](#lafw)
9. [Conclusion](#conc)

# Project Overview <a name="Proj-Overview"></a>
<p align="justify"> This project aims to analyze the factors contributing to fatal car accidents in the United States by looking at the relationships between fatal car accidents in the United States and various other factors. The primary dataset "Fatal Car Accidents by State" will serve as the dependent variable, while the other datasets will act as independent variables. The goal is to find out the correlation of factors in order of association. </p>
<p align="justify"> Using Statistical analysis and data visualization techniques, the project will explore trends across states, helping find an inference between the factors. Additionally, the conclusion of this project should help transportation authorities use the data to reduce fatal car accidents and improve road safety. </p>

# Research Questions and Objectives <a name="rqao"></a>
### Research Questions
- Which Factors have the strongest correlation with fatal car accidents in the United States?
- Are there regional patterns in fatal car accidents?
- Does the absence of vehicle inspection programs contribute significantly to fatal accidents?
- Is there a relationship between the number of vehicles per capita and fatal car accidents?
- Do states with higher speed limits experience more fatal car accidents?

### Objectives 
- Determine which factors are most strongly related to fatal car accidents.
- Use maps, bar charts, and scatter plots to visualize relationships between variables.
- Utilize data cleaning, merging, statistical analysis, and visualization techniques to find meaningful conclusions
- Use machine learning models and data science skills to assist me with the analysis accordingly.

# Motivation <a name="moti"></a>
<p align="justify"> For me, this project was generally driven by a strong desire to understand and address the rate of fatal accidents on roads, so I specifically chose to work on datasets based in the United States. Every year, thousands of lives are tragically lost in accidents that could be prevented with a better understanding of the contributing factors. These fatalities not only result in immeasurable loss for communities but also place a significant burden on public health systems, emergency services, and the economy.
Therefore, by analyzing data related to car accidents, I believe we can uncover patterns and identify key risk factors—This knowledge is crucial for developing targeted interventions, improving public safety policies, and implementing more effective preventive measures. It is vital that we explore these variables in order to make informed decisions that could save lives, and create safer road environments for all.

# Datasets <a name="datase"></a>
<p align="justify"> This section provides a concise overview of the datasets used in the analysis, including their descriptions, to highlight their relevance to the study of fatal car accidents. </p>

| Dataset  | Description |
| ------------- | ------------- |
| Fatal Car Accidents by State | State-level data on fatal car accidents in the U.S. |
| Speed Limits by State  | State-level data on maximum speed limits for highways and roads across the U.S. |
| Alcohol Consumption by State | State-level data on per capita alcohol consumption |
| Seat Belt Use by State | State and Territory-Level Data on Seat Belt Usage Rates in the U.S. |
| Road Quality by State | State-level data on road quality metrics across the U.S. |
| States Without Vehicle Inspection | State-level data on vehicle safety inspection requirements across the U.S. |
| Vehicle Ownership per Capita by State | State-Level Data on Vehicles per Capita Across the U.S. |

# Hypothesis <a name="hypo"></a>
- **Null Hypothesis (H₀):** There is no significant relationship between fatal car accidents and other factors such as speed limits, alcohol consumption, road quality, vehicle inspection requirements, seat belt usage, and vehicle capita across U.S states.
- **Alternate Hypothesis (H₁):** At least 1 factor has a significant relationship with fatal car accident rates across U.S. states such as speed limits, alcohol consumption, road quality, vehicle inspections, seat belt usage, or vehicles per capita across U.S. states.

# Dataset Analysis Plan <a name="dap"></a>
## Data Collection
**Data Sources**
- Fatal Car Accidents by State
- Speed Limits by State
- Alcohol Consumption by State
- Road Quality by State
- Vehicle Inspection Requirements by State
- Seat Belt Usage by State
- Vehicles per Capita per State

**Data Integration**
- Merge the datasets by state to create a unified dataset for analysis
- Ensure consistent state naming conventions and handle missing data

## Data Preprocessing
**Data Cleaning**
- Handle Missing Values by removing them or imputation
- Standardize units and formats across datasets

**Feature Engineering**
- Create derived variables
- Categorize Variables

## Exploratory Data Analysis
- **Univariate Analysis:**
  - Summarize and visualize individual variables
  - Use histograms, box plots, and summary statistics
- **Bivariate Analysis:**
  - Explore relationships between fatal car accidents and each independent variables
  - Use scatter plots, correlation matrices, and grouped bar charts
- **Multivariate Analysis:**
  - Examine interactions between multiple variables
  - Use heatmaps and grouped visualizations

 # Tools and Technologies <a name="tat"></a>
 - To be able to effectively analyse the data above, I will make use of the following tools:
    - Python: The primary programming language for managing datasets, conducting statistical analyses, and running models, utilizing platforms like Google Colab or Visual Studio Code.
    - Pandas:  A crucial tool for data preprocessing, filtering, and transforming data to derive meaningful insights.
    - Matplotlib & Seaborn: Used for creating visualizations such as graphs, heatmaps, and trend charts to explore and understand the relationships between variables.

# Limitations and Future Work <a name="lafw"></a>
## Limitations
### Data Quality and Availability
- **Missing Data:** Some states may have incomplete or missing data for certain variables.
- **Inconsistent Reporting:** Differences in how states report fatal accidents could introduce bias.

### Causation
- **Reverse Causality:** For example, states with higher accident rates might implement stricter speed limits, creating a misleading relationship.

### Bias in Self-Reported Data
- **Alcohol Consumption:** Alcohol Consumption data may not account for illegal or unreported drinking.

## Future Directions for the Current Objective
- Incorporate additional variables, such as weather conditions, traffic density, and distracted driving statistics.
- Expand the scope to include local-level data for more granular analyses.

# Expected Outcomes <a name="conc"></a>
<p align="justify"> This project aims to identify key factors influencing fatal car accidents across U.S. states by analyzing datasets on speed limits, alcohol consumption, road quality, vehicle inspections, seat belt usage, and vehicles per capita. Using exploratory data analysis, hypothesis testing, and statistical modelling, it will explore correlations between these variables and fatal accident rates, providing insights that will hopefully aid in improving road safety. </p>

# Analysis of Research
## Total Fatal Car Accidents by State (2022–2023)
![newplot](https://github.com/user-attachments/assets/34324d85-55ba-49e3-9fdd-b15c7f626fc9)
This map shows the total fatal car accidents in U.S. States (2022-2023) highlighting key regional patterns.
- High fatalities are concentrated in large, populous states like Texas, California, and Florida, likely due to more vehicles, longer road networks, and denser traffic.
- Lower totals appear in smaller states like Vermont, Rhode Island, and Wyoming, which have fewer residents and vehicles.
- The map shows absolute deaths, not adjusted for population so it doesn’t reflect risk per person or per mile driven.

The map highlights regional differences in traffic fatalities and points to areas that may benefit from targeted safety measures.

## Comparison of Death Rates per State (2022 vs 2023)
![Comparison of Death Rates per State (2022 vs 2023)](https://github.com/user-attachments/assets/0e497ff1-2ea9-4f61-a4f6-733259e0bf4c)
<p align="justify"> Building on the earlier choropleth that showed total state-wise fatalities, this bar chart shifts focus to vehicle-normalized death percentages, offering a fairer comparison across states. It presents fatality rates per registered vehicle for each U.S. state in 2022 and 2023, sorted in descending order based on 2023 values. This normalization removes the influence of population size and total vehicle count, allowing for a clearer assessment of relative fatality rates. </p>

- Mississippi, Alabama, and New Mexico consistently show the highest death percentages in both years, highlighting states with the most elevated normalized fatality rates
- Many states exhibit minimal variation between years, indicating overall consistency in fatality risk
- Some states such as Arkansas, Montana, and Alaska show a notable decline in death percentages from 2022 to 2023
- At the lower end of the scale, Massachusetts, Rhode Island, and New Jersey report the lowest fatality rates in both years

This comparison enables a more precise identification of patterns and changes in road fatalities over time, independent of state size or total crash volume.

## Breakdown of Fatal Car Accidents by Alcohol Involvement (2022)
![newplot (1)](https://github.com/user-attachments/assets/4a8b254e-56c6-4b23-b5d1-18c5f28e187b)
The grouped bar chart shows each state's fatality percentages for both years side by side, while the difference map highlights the year-over-year change, with redder states showing an increase and whiter states showing a decrease or no change.

### Visual Comparison: Bar Chart
Top States in Both Years:

- Montana, North Dakota, and Rhode Island remain at the top of the list with the highest alcohol-related fatality percentages in both 2022 and 2023.
- The ordering slightly shifts, but the core high-risk states are consistent across both years.

General Shape:

- The distribution appears quite similar: a gradual decline from the highest (46%) to the lowest (18–22%) in both years.
- No state shows a dramatic spike or drop, suggesting relative consistency in state-level patterns.

### Visual Comparision: Map
Geographical Patterns:

- Several Southeastern and Central states experienced notable increases in alcohol-related fatality rates.
- Western and Midwestern regions generally showed stable or minimal changes.
- Some Southern and Southwestern states saw moderate decreases, indicating potential improvements.
- The Northeast displayed mixed trends, with no clear regional pattern.

## Vehicle-Normalized Death Percentage vs. Interstate Speed Limit (2022 & 2023)
Further comparing the normalized death percentage with other variables, we examine how it relates to the average interstate speed limit across U.S. states. These side-by-side scatter plots represent the relationship for 2022 (left) and 2023 (right).
![Vehicle Normalized Death Per vs Interstate Speed Limit](https://github.com/user-attachments/assets/6aa7d683-99cd-4d36-9622-75ee835b7b27)
- In both years, the data points are widely scattered across all speed ranges, with no strong upward or downward trend.
- States with the same speed limits (e.g., 70 mph) show a wide range of fatality percentages, indicating that speed alone is not a strong predictor of vehicle-normalized death rates.
- The similarity between the two plots suggests a consistent trend year-over-year, reinforcing the observation that interstate speed limit, when viewed in isolation, does not appear to drive significant changes in fatality percentages.
- The analysis implies that other factors, such as seatbelt usage, alcohol involvement, inspection policies, and road quality, may have a stronger influence on fatality risk than posted speed limits alone.

## Death Percentage (2023) vs. Vehicle Inspection Strictness
This box plot compares the vehicle-normalized fatality percentage in 2023 across states grouped by their level of vehicle inspection strictness, represented by InspectionRank:
- 0 = No inspection requirement
- 0.5 = Single or one-time inspection
- 1 = Biennial inspections
- 2 = Annual inspections

![Death Per vs Vehicle Inspection Strictness](https://github.com/user-attachments/assets/85e6abf4-1660-4e32-bc22-8c0cf401c93d)

Observations:

- States with annual inspections (rank = 2) show the lowest median death percentages, with a narrower spread of values.
- States with no inspection requirements (rank = 0) and biennial inspections (rank = 1) display higher medians and greater variability.
- Some outliers exist, but the overall trend suggests that stricter inspection policies may be associated with lower fatality rates per vehicle.

While this plot alone doesn't prove causality, it suggests a potential link worth exploring further alongside other contributing factors such as road quality, seatbelt usage, or alcohol consumption.

## Road Surface Quality vs Total Car Accident Deaths (2022–2023)

This figure presents two side-by-side scatter plots analyzing how pavement roughness in urban and rural areas correlates with the total number of traffic fatalities per state over the years 2022 and 2023.

- The left plot compares urban pavement roughness to total deaths
- The right plot compares rural pavement roughness to total deaths

![Road Surface Quality vs Total Car Accidents Deaths](https://github.com/user-attachments/assets/5a83766f-20f2-4adf-84a7-6c3e73116d95)

Key Insights:

- In both graphs, fatality totals appear to be widely distributed across various levels of roughness, indicating no strong linear relationship
A few states with high fatality counts also show low or moderate roughness scores, suggesting that road surface quality may not be the primary driver of fatal crashes
- Most roughness values are concentrated in the lower range, especially for rural roads, while urban roads show a broader spread in surface conditions

These plots suggest that pavement roughness alone is not a reliable predictor of fatality totals. However, it may still interact with other factors.

## Seatbelt Usage vs. Vehicle-Normalized Death Percentage (2022)

This scatter plot examines the relationship between seatbelt usage percentage and the death percentage per registered vehicle for each state in 2022. Each point represents a U.S. state, and the black regression line shows the overall trend.

![Seatbelt Usage vs Death Percentage (2022)](https://github.com/user-attachments/assets/0f3334fc-929a-4bb1-bcdb-4accfcbf34f9)

**Observations:**

- There is a slight negative correlation: as seatbelt usage increases, the death percentage tends to decrease
- The trendline slopes downward, suggesting that states with higher seatbelt compliance generally have lower fatality rates relative to the number of vehicles
- While the correlation is modest and there is variability among states, the general pattern reinforces the role of seatbelt usage as a contributing factor in reducing traffic deaths

This visualization supports the idea that seatbelt may be a influencing factor when it comes to Fatal car accident death rates, even if it is not the only one.

After this viusalisation, lets move on to testing a hypothesis on similar data in the dataset, specifically the "Car accident deaths per 100k (2022)"

## Hypothesis Test: Seatbelt Usage vs. Car Accident Death Rate (2022)

**Hypothesis:**

> Null Hypothesis (H₀): There is no significant relationship between seatbelt usage rates and the number of deaths per 100,000 people in car accidents.

> Alternative Hypothesis (H₁): Higher seatbelt usage is significantly associated with fewer deaths per 100,000 people in car accidents.

We will first check if both the column variables are normalised through histograms. If not, we lean towards using the Spearman Correlation.

![Normality Check](https://github.com/user-attachments/assets/9653603b-f365-4cf2-b40d-7c2bac71acd0)

**Seatbelt Usage (2022)**
- Slight left skew with most values above 85%
- KDE line deviates from the normal curve, especially at lower values
- Likely not normally distributed
**Car Accident Deaths per 100k (2022)**
- Right-skewed with a heavy tail above 20 deaths per 100k
- Normal curve does not fit well, especially in the upper range
- Also likely not normally distributed

**Histogram Observation Conclusion:** Since both variables show deviations from normality, I am deciding to use Spearman correlation to test my hypothesis testing.

**Test Performed:** Spearman Correlation

**Results:**
- Correlation coefficient (ρ): -0.280
- P-value: 0.049
  
**Conclusion:**

There is a statistically significant negative correlation between seatbelt usage and car accident deaths per 100k in 2022. As seatbelt usage increases, fatality rates tend to decrease.

While the correlation is not strong, it is significant at the 5% level, supporting the hypothesis that increased seatbelt use is associated fewer deaths per 100,000 people in car accidents.

## Alcohol Fatalities vs. Excessive Drinking (2022)

This scatter plot explores the relationship between the percentage of adults reporting excessive drinking and the percentage of fatal car accidents involving alcohol across U.S. states in 2022. Even though this is a more straightforward comparison, its still important to confirm that the correlation between these two fcators exists.

![Alcohol Fatalities vs Excessive Drinking (2022)](https://github.com/user-attachments/assets/954e7ef2-5d8a-4acd-8a24-e3811fdc5c3a)

Observations:

- The regression line shows a clear positive correlation: as excessive drinking rates increase, so do alcohol-related traffic fatalities.
- States with higher levels of reported excessive drinking tend to experience a greater proportion of alcohol-involved fatal crashes.
- The trendline's slope and clustering of points along the upward direction suggest a relatively strong relationship.
  
Lets also test these observations through hypothesis testing.

## Hypothesis Test: Alcohol Consumption Behaviors vs. Alcohol-Related Fatalities (2022)

**Hypothesis:**

> Null Hypothesis (H₀): There is no significant relationship between excessive drinking rates or ethanol consumption per capita and alcohol-related car fatalities.

> Alternative Hypothesis (H₁): Higher excessive drinking rates and higher ethanol consumption per capita are significantly associated with increased alcohol-related car fatalities.

**Variables Used:**
- Ethanol per Capita (2022)
- Excessive Drinking % (2022)
  
**Test Performed:**
Spearman Correlation (since we are not sure of the normality of the variables being tested.)

**Results:**
| Variable Pair                                | Correlation Type | Correlation Coefficient (r) | p-value   | Significant? |
|---------------------------------------------|------------------|-----------------------------|-----------|--------------|
| Ethanol per Capita vs Alcohol Fatalities     | Spearman         | 0.447                       | 0.00115   | Yes          |
| Excessive Drinking % vs Alcohol Fatalities   | Spearman         | 0.611                       | 0.00000   | Yes          |

### Interpretation:
**Ethanol per Capita vs. Alcohol Fatalities %**

There is a moderate, statistically significant positive correlation between ethanol consumption per capita and the percentage of alcohol-related car fatalities. This suggests that states with higher ethanol use tend to experience more fatal traffic incidents involving alcohol.

**Excessive Drinking % vs. Alcohol Fatalities %**

There is a strong, statistically significant positive correlation between the percentage of people who engage in excessive drinking and alcohol-related traffic fatalities. This also confirms our observations earlier that we dediced from the graph.

**Conclusion:**

Both ethanol consumption and excessive drinking rates are positively associated with alcohol-related fatal crashes. These findings support the hypothesis that alcohol-related behaviors are associated with increased alcohol-related car fatalities.

## Hypothesis Test: Total Automobiles vs. Car Accident Deaths (2022 & 2023)

**Hypothesis:**

> H₀ (Null Hypothesis): There is no monotonic relationship between the number of registered vehicles and the total number of car accident fatalities.

>H₁ (Alternative Hypothesis): States with more registered vehicles tend to have more car accident fatalities.

**Variables Used:**
- Automobiles_2022, Automobiles_2023 (Total registered vehicles)
- Deaths due to car accidents (2022), (2023)

**Test Chosen:**
Pearson Correlation was chosen as both variables are quantitative and approximately linear in relationship.

| Year | Correlation Coefficient (r) | P-Value   | Significant? |
|------|-----------------------------|-----------|--------------|
| 2022 | 0.940                       | 0.00000   | Yes       |
| 2023 | 0.931                       | 0.00000   | Yes       |

**Interpretation:**
- Both years show a very strong and statistically significant positive correlation between the number of registered vehicles and total car accident deaths.
- The correlation coefficients (r = 0.940 for 2022 and r = 0.931 for 2023) are near-perfect, indicating a consistent and strong linear relationship.
- These findings strongly support the hypothesis: States with more vehicles tend to experience more fatal traffic accidents.

**Conclusion:**

This result reinforces the link between vehicle volume and traffic fatalities. As vehicle ownership increases, exposure to road risks rises. Hence, the results support the alternate hypothesis.

## ANOVA Analysis: Vehicle Inspection Rank vs. Car Accident Death Rate (2022)

Hypothesis:

>H₀ (Null Hypothesis): There is no significant difference in the average fatality rates among states with different vehicle inspection ranks.

>H₁ (Alternative Hypothesis): There is a significant difference in the average fatality rates among states with different vehicle inspection ranks.

**Test Type:**
- One-Way ANOVA

**Independent Variable:**
- InspectionRank (Ordinal scale: e.g., 0 = No Inspection, 2 = Annual Inspection)

**Dependent Variable:**
- Car accident deaths per 100k (2022)

**Results:**
| Metric        | Value        |
|---------------|--------------|
| F-statistic   | 1.79     |
| p-value       | 0.147    |
| Groups tested | [ 0.0, 0.5, 1.0, 1.5, 2.0 ] |

**Interpretation:**
- The p-value is greater than 0.05, so we fail to reject the null hypothesis.
- This suggests there is no statistically significant difference in mean death rates between states with different inspection ranks in 2022.
- Therefore, based on this data, inspection policy alone does not appear to influence fatality rates significantly.

**Conclusion:**

While safety inspections might play a role in overall vehicle safety, this analysis indicates that other variables (like alcohol use, seatbelt rates, or road conditions) may be more influential in determining per-capita traffic deaths. I would need to use further tests to determine its exact importance.

## Paired T-Test: Year-to-Year Change in Fatality Metrics (2022 - 2023)

**Hypothesis:**

H₀ (Null Hypothesis): > There is no significant difference in fatality-related variables between 2022 and 2023.

> H₁ (Alternative Hypothesis): There is a significant difference in fatality-related variables between 2022 and 2023.

**Variables**

- Car accident deaths per 100k (2022) vs. (2023)
- Alcohol Fatalities % (2022) vs. (2023)

**Test Type:**
- Paired T-Test (two-tailed)

**Results:**
| Metric                          | t-statistic | p-value       | Significant? |
|--------------------------------|-------------|---------------|--------------|
| Car accident deaths per 100k   | -0.384      | 0.70241  |  No        |
| Alcohol Fatalities %           | -6.614      | 0.00000  |  Yes       |

**Interpretation:**

- There is no statistically significant change in the car accident death rate per 100,000 people from 2022 to 2023.
- However, there is a significant decrease in the percentage of alcohol-related fatalities across states between the two years.
- This suggests that any efforts (that might have been made) to combat alcohol-involved crashes may have had a measurable effect.

**Conclusion:**

While overall accident death rates remained stable, alcohol-specific interventions or behavior changes between 2022 and 2023 may have led to less fatal deaths. Hence, the results partially support the alternate hypothesis.

## One-Way ANOVA: Interstate Speed Groups vs. Car Accident Death Rate (2022)

Hypothesis:

> H₀ (Null Hypothesis): There is no significant difference in average car accident fatality rates among states with different average interstate speed limits.

> H₁ (Alternative Hypothesis):
There is a significant difference in average car accident fatality rates among states with different average interstate speed limits.

**Test Type:**

One-Way ANOVA since we are comapring multiple means (we group the interstate speed limits into different groups based on their numbers)

**Independent Variable (Grouped):**
- InterstateSpeedAvg (binned into: Low < 65, Mid 65–70, High > 70)
- 
**Dependent Variable:**
- Car accident deaths per 100k (2022)

**Results:**
- F-statistic = 3.28 (rounded)
- p-value = 0.046
- Groups tested = ['High (>70)', 'Low (<65)', 'Mid (65–70)']
- 
**Interpretation:**
- The p-value is less than 0.05, so we reject the null hypothesis.
- There is a statistically significant difference in fatality rates across states with different average interstate speed limits.
- This suggests that interstate speed limits may influence car accident death rates.
- To better understand which specific speed categories differ, and how large the effect is, further analysis will most likely be needed

**Conclusion:**
Policymakers and transportation agencies may consider speed limit regulations as a factor that reduces fatal accidents across states.
