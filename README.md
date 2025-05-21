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
9. [Expected Outcomes](#conc)
10. [Analysis of Research](#aor)
11. [Machine Learning](#ml)
12. [Final Remarks](#fr)

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

| Dataset  | Description | Link |
| ------------- | ------------- | --------------- | 
| Fatal Car Accidents by State | State-level data on fatal car accidents in the U.S. | [Dataset 1](https://worldpopulationreview.com/state-rankings/fatal-car-accidents-by-state) [Dataset 2](https://wisevoter.com/state-rankings/fatal-car-accidents-by-state/) |
| Speed Limits by State  | State-level data on maximum speed limits for highways and roads across the U.S. | [Dataset 1](https://worldpopulationreview.com/state-rankings/speed-limits-by-state) |
| Alcohol Consumption by State | State-level data on per capita alcohol consumption | [Dataset 1](https://worldpopulationreview.com/state-rankings/alcohol-consumption-by-state) |
| Seat Belt Use by State | State and Territory-Level Data on Seat Belt Usage Rates in the U.S. | [Dataset 1](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813615) |
| Road Quality by State | State-level data on road quality metrics across the U.S. | [Dataset 1](https://worldpopulationreview.com/state-rankings/road-quality-by-state) |
| States Without Vehicle Inspection | State-level data on vehicle safety inspection requirements across the U.S. | [Dataset 1](https://worldpopulationreview.com/state-rankings/states-without-vehicle-inspection) |
| Vehicle Ownership per Capita by State | State-Level Data on Vehicles per Capita Across the U.S. | [Dataset 1](https://www.fhwa.dot.gov/policyinformation/statistics/2022/mv1.cfm) [Dataset 2](https://www.fhwa.dot.gov/policyinformation/statistics/2023/pdf/mv1.pdf) |

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
- Handle Missing Values by removing them or by imputation
- Standardise units and formats across datasets

**Feature Engineering**
- Create derived variables
- Categorise Variables

## Exploratory Data Analysis
- **Univariate Analysis:**
  - Summarise and visualise individual variables
  - Use histograms, box plots, and summary statistics
- **Bivariate Analysis:**
  - Explore relationships between fatal car accidents and each independent variables
  - Use scatter plots, correlation matrices, and grouped bar charts
- **Multivariate Analysis:**
  - Examine interactions between multiple variables
  - Use heatmaps and grouped visualisations

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

## Expected Outcomes <a name="conc"></a>
<p align="justify"> This project aims to identify key factors influencing fatal car accidents across U.S. states by analysing datasets on speed limits, alcohol consumption, road quality, vehicle inspections, seat belt usage, and vehicles per capita. Using exploratory data analysis, hypothesis testing, and statistical modelling, it will explore correlations between these variables and fatal accident rates, providing insights that will hopefully aid in improving road safety. </p>

# Analysis of Research <a name="aor"></a>
Following the compilation of the dataset, we explore the relationships between various factors through visualisation and conduct hypothesis testing across multiple dimensions.

##  Total Fatal Car Accidents by State (2022–2023)
![newplot](https://github.com/user-attachments/assets/34324d85-55ba-49e3-9fdd-b15c7f626fc9)
This map shows the total fatal car accidents in the U.S. States (2022-2023), highlighting key regional patterns.
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

## Correlation Analysis of Car Accident Factors

To begin the analysis, we first test our main hypothesis by examining the relationships between fatal car accidents and various potential influencing factors. Additionally, we explore the correlations between other key variables related to car accidents. This initial step helps identify which factors are most closely associated with fatalities and may warrant further investigation.

**Hypothesis**

> Null Hypothesis (H₀): There is no significant relationship between fatal car accident rates and factors such as speed limits, alcohol consumption, road quality, vehicle inspection requirements, seatbelt usage, or the number of vehicles per capita across U.S. states.

> Alternative Hypothesis (H₁): At least one of these factors — speed limits, alcohol consumption, road quality, vehicle inspection requirements, seatbelt usage, or vehicles per capita — has a significant relationship with fatal car accident rates across U.S. states.

![Correlation Matrix](https://github.com/user-attachments/assets/b80cba0c-a3e3-4499-a88d-b8cafe99741f)

**Analysis Based on the Correlation Matrix**
- TotalDeaths_2022_2023 is highly positively correlated with both Automobiles_2022 and Automobiles_2023 (r ≈ 0.94). This strong association suggests that the number of vehicles in a state is closely tied to the total number of traffic-related deaths. However, this is partially expected, as vehicle count is used in calculating related fatality metrics.
- DeathPercentage_2022 and DeathPercentage_2023 show moderate negative correlations with Seatbelt Usage (r ≈ -0.16 to -0.19), implying that states with higher seatbelt usage tend to have lower fatality rates relative to population. Lets check this with the pear

### Seatbelt Usage vs Car Accident Deaths (2022 & 2023)
| Year | Variable Pair                           | Correlation Type | Correlation Coefficient (r) | p-value   | Significant?                |
|------|------------------------------------------|------------------|-----------------------------|-----------|-----------------------------|
| 2022 | Seatbelt Usage vs Death Percentage       | Pearson          | -0.1828                     | 0.20391   | No (fail to reject H₀)      |
| 2023 | Seatbelt Usage vs Death Percentage       | Pearson          | -0.1561                     | 0.27913   | No (fail to reject H₀)      |


According to the pearson test however, for both year cases (2022 and 2023) the null hypothesis fails to be rejected here.

### Additional Correlation Insights according to the correlation matrix above
- Alcohol Fatalities % (2022 and 2023) exhibit strong positive correlations with Ethanol per Capita (r ≈ 0.43–0.48), suggesting that higher alcohol consumption is associated with more alcohol-related car fatalities. While relevant, these metrics are not directly part of the overall fatality rate hypothesis tested above.
- InterstateSpeedAvg and Road Quality metrics show weak to no meaningful correlation with fatality rates, indicating a limited direct linear relationship. These factors may influence crash severity or likelihood through more complex mechanisms.
- InspectionRank demonstrates minimal correlation with fatality metrics, implying that state-level inspection policy stringency does not independently predict fatality rates in this dataset.

### Conclusion
While correlations suggest potential relationships between variables like seatbelt usage and vehicle count with fatality outcomes, statistical testing shows no significant relationship at the population level across states for the tested hypothesis. The null hypothesis cannot be rejected based on current results. However, some behavioral factors (like alcohol consumption) may still warrant further focused analysis.

This correlation matrix serves as a foundation for identifying relationships worth modeling or visualizing further correlations

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

### Visual Comparison: Map
Geographical Patterns:

- Several Southeastern and Central states experienced notable increases in alcohol-related fatality rates.
- Western and Midwestern regions generally showed stable or minimal changes.
- Some Southern and Southwestern states saw moderate decreases, indicating potential improvements.
- The Northeast displayed mixed trends, with no clear regional pattern.

## Vehicle-Normalised Death Percentage vs. Interstate Speed Limit (2022 & 2023)
Further comparing the normalised death percentage with other variables, we examine how it relates to the average interstate speed limit across U.S. states. These side-by-side scatter plots represent the relationship for 2022 (left) and 2023 (right).
![Vehicle Normalized Death Per vs Interstate Speed Limit](https://github.com/user-attachments/assets/6aa7d683-99cd-4d36-9622-75ee835b7b27)
- In both years, the data points are widely scattered across all speed ranges, with no strong upward or downward trend.
- States with the same speed limits (e.g., 70 mph) show a wide range of fatality percentages, indicating that speed alone is not a strong predictor of vehicle-normalised death rates.
- The similarity between the two plots suggests a consistent trend year-over-year, reinforcing the observation that interstate speed limit, when viewed in isolation, does not appear to drive significant changes in fatality percentages.
- The analysis implies that other factors, such as seatbelt usage, alcohol involvement, inspection policies, and road quality, may have a stronger influence on fatality risk than posted speed limits alone.

## Death Percentage (2023) vs. Vehicle Inspection Strictness
This box plot compares the vehicle-normalised fatality percentage in 2023 across states grouped by their level of vehicle inspection strictness, represented by InspectionRank:
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

## Seatbelt Usage vs. Vehicle-Normalised Death Percentage (2022)

This scatter plot examines the relationship between seatbelt usage percentage and the death percentage per registered vehicle for each state in 2022. Each point represents a U.S. state, and the black regression line shows the overall trend.

![Seatbelt Usage vs Death Percentage (2022)](https://github.com/user-attachments/assets/0f3334fc-929a-4bb1-bcdb-4accfcbf34f9)

**Observations:**

- There is a slight negative correlation: as seatbelt usage increases, the death percentage tends to decrease
- The trendline slopes downward, suggesting that states with higher seatbelt compliance generally have lower fatality rates relative to the number of vehicles
- While the correlation is modest and there is variability among states, the general pattern reinforces the role of seatbelt usage as a contributing factor in reducing traffic deaths

This visualisation supports the idea that seatbelts may be an influencing factor when it comes to Fatal car accident death rates, even if it is not the only one.

After this visualisation, let's move on to testing a hypothesis on similar data in the dataset, specifically the "Car accident deaths per 100k (2022)"

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
- The normal curve does not fit well, especially in the upper range
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

This scatter plot explores the relationship between the percentage of adults reporting excessive drinking and the percentage of fatal car accidents involving alcohol across U.S. states in 2022. Even though this is a more straightforward comparison, its still important to confirm that the correlation between these two factors exists.

![Alcohol Fatalities vs Excessive Drinking (2022)](https://github.com/user-attachments/assets/954e7ef2-5d8a-4acd-8a24-e3811fdc5c3a)

Observations:

- The regression line shows a clear positive correlation: as excessive drinking rates increase, so do alcohol-related traffic fatalities.
- States with higher levels of reported excessive drinking tend to experience a greater proportion of alcohol-involved fatal crashes.
- The trendline's slope and clustering of points along the upward direction suggest a relatively strong relationship.
  
Let's also test these observations through hypothesis testing.

## Hypothesis Test: Alcohol Consumption Behaviours vs. Alcohol-Related Fatalities (2022)

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
**Ethanol per Capita vs. Alcohol Fatalities% %**

There is a moderate, statistically significant positive correlation between ethanol consumption per capita and the percentage of alcohol-related car fatalities. This suggests that states with higher ethanol use tend to experience more fatal traffic incidents involving alcohol.

**Excessive Drinking % vs. Alcohol Fatalities %**

There is a strong, statistically significant positive correlation between the percentage of people who engage in excessive drinking and alcohol-related traffic fatalities. This also confirms our observations earlier that we deduced from the graph.

**Conclusion:**

Both ethanol consumption and excessive drinking rates are positively associated with alcohol-related fatal crashes. These findings support the hypothesis that alcohol-related behaviours are associated with increased alcohol-related car fatalities.

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
Speed limit regulations may be considered as a factor that reduces fatal accidents across states.

# Machine Learning for Predictions <a name="ml"></a>

## Further Data Enrichments for the implementation of ML methods
```
import pandas as pd

#loading thedataset
df = pd.read_csv('all_state_data_merged.csv')

#here we define column pairs for % change calculation
percent_change_pairs = {
    'Deaths': ('Deaths due to car accidents (2022)', 'Deaths due to car accidents (2023)'),
    'Alcohol_Fatalities': ('Alcohol Fatalities % (2022)', 'Alcohol Fatalities % (2023)'),
    'Ethanol_per_Capita': ('Ethanol per Capita (2022)', 'Ethanol per Capita (2023)'),
    'Excessive_Drinking': ('Excessive Drinking % (2022)', 'Excessive Drinking % (2023)'),
    'Seatbelt_Usage': ('Seatbelt 2022', 'Seatbelt 2023'),
    'Automobiles': ('Automobiles_2022', 'Automobiles_2023'),
}

#Compute % change and add to dataframe
for new_col, (col_2022, col_2023) in percent_change_pairs.items():
    df[f'{new_col}_Pct_Change'] = ((df[col_2023] - df[col_2022]) / df[col_2022]) * 100

df['Automobile_Growth_Rate'] = (df['Automobiles_2023'] - df['Automobiles_2022']) / df['Automobiles_2022'] * 100

df['Road_Quality_Index'] = (
    df['RoadQuality2022Ranking'].fillna(0) +
    df['RoadQualityUrbanPavementRoughness'].fillna(0) +
    df['RoadQualityRuralPavementRoughness'].fillna(0)
) / 3

df.to_csv('enriched_all_state_data.csv', index=False)
```

### Data Enrichment Explanation
Below are the key enrichment steps we performed and their significance:

---

#### Percentage Change Calculations
We computed the year-over-year percentage change for key indicators such as:
- Deaths due to car accidents
- Alcohol-related fatality rates
- Ethanol consumption per capita
- Excessive drinking percentage
- Seatbelt usage
- Number of registered automobiles

**Why?**  
Percentage change captures trends and shifts more effectively than raw values. It normalizes state-level differences, reveals behavioral or policy impacts over time, and enhances the predictive power of the model by showing dynamics rather than static figures.

---

#### Automobile Growth Rate
We specifically computed the growth rate in the number of automobiles from 2022 to 2023.

**Why?**  
This metric serves as a proxy for economic activity, urbanization, and road usage intensity—all of which can influence accident patterns and fatality risks.

---

#### Road Quality Index
We aggregated three road quality metrics:
- Road quality ranking (2022)
- Urban pavement roughness
- Rural pavement roughness

**Why?**  
By averaging these, we create a unified Road Quality Index that represents overall infrastructure quality. Poor roads often correlate with higher accident rates, so this consolidated index improves interpretability and model usability.

---

Now we head on to find the most useful columns to use for making predictions.


## Using Chi Squared Test and Mutual Information to select the most useful Columns for prediction

### Chi-Squared Test

Top features by Chi-Squared score:
| Feature                                  | Chi-Squared Score |
|------------------------------------------|------------------:|
| DeathPercentage_2023                     |          3.996954 |
| Car accident deaths per 100k (2022)      |          3.980151 |
| DeathPercentage_2022                     |          2.680914 |
| RoadQualityRuralPavementRoughness        |          2.055921 |
| InspectionRank                           |          1.951613 |
| Road_Quality_Index                       |          1.773729 |
| RoadQuality2022Ranking                   |          1.529513 |
| Alcohol_Fatalities_Pct_Change            |          1.301770 |
| RoadQualityUrbanPavementRoughness        |          1.259854 |
| InterstateSpeedAvg                       |          0.939417 |


### Interpretation of Chi-Squared Test Results

1. **Strongest Signals Come from Past Fatality Rates**  
   - Both **“Deaths per 100k in 2022”** and **“DeathPercentage_2022”** rank at the top. That tells us a state’s fatality rate last year is by far the best indicator of whether it’ll fall into the “high-fatality” group this year.

2. **Leakage Feature Must Be Dropped**  
   - **“DeathPercentage_2023”** appears highest only because it’s literally the binarized target itself. Including it in any model would be data leakage—so remove it before training.

3. **Road Quality & Inspection Matter Moderately**  
   - **Rural pavement roughness** and **InspectionRank** both show a clear—but smaller—association. States with rougher country roads or more lenient inspection policies tend to cluster on one side of the high/low split.  
   - **Road_Quality_Index** also carries meaningful signal.

4. **Trend Features Add Some Value, but Less**  
   - **Year-over-year change in alcohol-fatality percentage** and **urban-road roughness** make the top 10, but with lower scores. They help a bit, but much less than last year’s death rates.

5. **Speed Limits Barely Move the Needle**  
   - **Average interstate speed** ranks near the bottom, indicating it does little to separate “high” vs. “low” fatality states in a simple χ² test.

---

### Mutual Info Selection

Below are the top features ranked by mutual information with the continuous target **“Car accident deaths per 100k (2023)”**. Mutual information (MI) measures how much knowing a feature reduces uncertainty about the target:

| Feature                                | MI Score | Interpretation                                                         |
|----------------------------------------|---------:|------------------------------------------------------------------------|
| **Car accident deaths per 100k (2022)**|   1.3704  |  **Strongest predictor**: last year’s fatality rate per 100k carries the most information about this year’s rate—models will lean heavily on it. |
| **DeathPercentage_2023**               |   0.8384  | **Leakage alert**: this is effectively the normalized 2023 target itself; drop it to avoid “cheating.” |
| **DeathPercentage_2022**               |   0.5890  |  **Very informative**: vehicle-normalized death percentage in 2022 also provides substantial predictive power. |
| **Excessive Drinking % (2023)**        |   0.2814  | **Moderate signal**: states with higher binge-drinking rates tend to have higher crash death rates. |
| **RoadQualityRuralPavementRoughness**  |   0.2682  | **Moderate signal**: rougher rural roads are associated with higher fatality rates. |
| **InterstateSpeedAvg**                 |   0.1781  | **Some information**: posted speed limits contribute, but less so than behavioral or historical factors. |
| **Alcohol_Fatalities_Pct_Change**      |   0.1668  | **Some information**: year-over-year change in alcohol-related deaths helps a bit. |
| **Road_Quality_Index**                 |   0.1541  | **Some information**: the composite road-quality metric adds modest predictive value. |
| **RoadQualityUrbanPavementRoughness**  |   0.1407  | **Lesser signal**: urban pavement roughness helps, but to a smaller degree than rural. |
| **Deaths_Pct_Change**                  |   0.1097  | **Least in top 10**: change in vehicle-normalized death percentage has the smallest—but still nonzero—information. |

---

### Key Takeaways

1. **Historical Fatality Rates Dominate**  
   - Both raw and normalized **2022** death rates are the strongest continuous predictors.  
2. **Drop Data-Leakage Features**  
   - **`DeathPercentage_2023`** must be removed before training—it trivially encodes the target.  
3. **Behavior & Infrastructure Matter Less**  
   - **Excessive drinking rates** and **road-quality measures** carry useful signal, but far below last year’s death figures.  
4. **Speed Limits & Trend Features Are Secondary**  
   - **Interstate speed** and **percent-change metrics** (alcohol fatalities, deaths per vehicle) add incremental information; should only be included if  model benefits in cross-validation.

---

## Comparison: Chi-Squared vs. Mutual Information Selections

Below is a quick look at where the two feature-selection methods agree and disagree:

| Feature                              | χ² Top-10? | MI Top-10? | Notes                                                                      |
|--------------------------------------|:----------:|:----------:|----------------------------------------------------------------------------|
| **Car accident deaths per 100k (2022)**  | ✓          | ✓          | Strongest predictor in both                                               |
| **DeathPercentage_2022**             | ✓          | ✓          | Normalized 2022 fatality rate                                              |
| **RoadQualityRuralPavementRoughness**| ✓          | ✓          | Moderate signal from both                                                  |
| **Road_Quality_Index**               | ✓          | ✓          | Composite road-quality measure                                             |
| **RoadQualityUrbanPavementRoughness**| ✓          | ✓          | Lower but nonzero in both                                                  |
| **InterstateSpeedAvg**               | ✓          | ✓          | Weak signal in both                                                        |
| **Alcohol_Fatalities_Pct_Change**    | ✓          | ✓          | Year-over-year change in alcohol fatalities                                 |
|                                      |            |            |                                                                            |
| **Disagreements**                    |            |            |                                                                            |
| InspectionRank                       | ✓          | ×          | χ² sees classification signal; MI ranks it much lower                      |
| RoadQuality2022Ranking               | ✓          | ×          | χ² picks raw ranking, MI favors the composite index                        |
| Excessive Drinking % (2023)          | ×          | ✓          | MI flags it as informative for the continuous target; χ² does not          |
| Deaths_Pct_Change                    | ×          | ✓          | MI sees a small continuous signal; χ² ranks it lower in the binary split   |

---

### Implementing Machine Learning Models

With our dataset now enriched, we are ready to begin implementing machine learning models.

We will start by predicting known values using various ML algorithms and compare the predicted results to the actual values. This approach allows us to evaluate the accuracy and performance of each model before moving on to unseen data.

## Using Random Forest Regressor to predict: Car accident deaths per 100k (2023)
### This is a hyper-tuned model using Random-Search


### What This Tells Us

1. **Chosen Hyperparameters**  
   - **100 trees** (`n_estimators`): enough to stabilize predictions without excessive computation.  
   - **`min_samples_split = 2`**: allows trees to split until each leaf has ≥ 2 samples, capturing fine-grained patterns.  
   - **`max_features = None`**: each split considers all features, which can boost accuracy but may increase correlation between trees.  
   - **`max_depth = 10`**: limits tree depth to prevent overfitting; deeper than this gave no additional benefit.

2. **Model Accuracy (RMSE = 1.28)**  
   - On average, the model’s predictions are off by **±1.28 deaths per 100,000** people.  
   - For a state with ~12 deaths/100k, most predictions fall between **10.7 and 13.3**.

3. **Explained Variance (R² = 0.94)**  
   - The model **explains 94%** of the variation in state-level fatality rates for 2023.  
   - This high R² indicates that our chosen features (historical death rates, drinking metrics, road quality, inspection rank) capture nearly all of the state‐to‐state differences.

---

### Key Takeaways

- **Excellent Fit**: R² of 0.94 shows outstanding predictive power given the available features.  
- **Low Error**: RMSE of 1.28 is small relative to the range of death rates (~5–25 per 100k), so predictions are precise.  
- **Balanced Complexity**: Depth = 10 and 100 trees strike a good balance—deep enough to learn complex relationships without overfitting.  

---

![image](https://github.com/user-attachments/assets/672afc33-fc5c-45ae-8939-df8747d17370)


## Tuned Random Forest Feature Importances

Below is the bar chart showing how much each feature contributed to the final, hyper-tuned Random Forest model:

| Feature                                | Importance (%) |
|----------------------------------------|---------------:|
| **Car accident deaths per 100k (2022)**| **82.0**       |
| DeathPercentage_2023                   | 10.0           |
| DeathPercentage_2022                   |  2.0           |
| Road_Quality_Index                     |  1.7           |
| RoadQualityUrbanPavementRoughness      |  1.1           |
| Excessive Drinking % (2023)            |  1.0           |
| Alcohol_Fatalities_Pct_Change          |  0.8           |
| RoadQualityRuralPavementRoughness      |  0.7           |
| InterstateSpeedAvg                     |  0.4           |
| InspectionRank                         |  0.1           |


## Key Takeaways

1. **Dominant Predictor**  
   - **“Car accident deaths per 100k (2022)”** drives **82%** of the model’s decisions—last year’s raw death rate is by far the best single indicator of 2023 rates.

2. **Secondary Signals**  
   - **“DeathPercentage_2023”** (10%) and **“DeathPercentage_2022”** (2%) add modest extra information once the raw rate is known.

3. **Engineered & Behavioral Features**  
   - The composite **Road_Quality_Index** (1.7%) and other road-quality measures contribute some signal, but together account for only ~3–4% of importance.  
   - **Excessive Drinking % (2023)** and **Alcohol_Fatalities_Pct_Change** each add less than 1%.

4. **Minimal Contributors**  
   - **InterstateSpeedAvg** and **InspectionRank** have near-zero importance—it is better to consider dropping thesevariables to simplify the model without losing accuracy.


**Conclusion:**  
Historical fatality rates overwhelmingly determine the prediction. Engineered features and policy metrics add only marginal gains.

---

## Data Standardization & Preparation for SVR/k-NN

1. **Load Enriched Data**  
   - Reads the pre-enriched state‐level dataset from `enriched_all_state_data.csv`.

2. **Select Features & Target**  
   - Defines a list of **10 numeric predictors** (`svr_features`) that include:  
     - Historical fatality metrics (`2022` rates and percentages, `2023` percentages)  
     - Behavioral trends (`Excessive Drinking % (2023)`, `Alcohol_Fatalities_Pct_Change`)  
     - Road quality measures (`RoadQualityRuralPavementRoughness`, `RoadQualityUrbanPavementRoughness`, `Road_Quality_Index`)  
     - Policy variable (`InspectionRank`)  
     - Driving exposure (`InterstateSpeedAvg`)  
   - Sets the **target variable**: `Car accident deaths per 100k (2023)`.

3. **Clean Missing Data**  
   - Drops any rows missing *any* of the selected features or the target.

4. **Extract Features (`X_svr`) & Labels (`y_svr`)**  
   - Splits the cleaned DataFrame into:
     - `X_svr`: the 10-column feature matrix  
     - `y_svr`: the vector of 2023 death rates per 100k

5. **Standard Scaling**  
   - Uses `StandardScaler()` to transform each feature to have **zero mean** and **unit variance**.  
   - Produces `X_svr_scaled`, which is ready for use in regression models that are sensitive to feature scale, such as **Support Vector Regression (SVR)** and **k-Nearest Neighbors Regression**.

**Result:**  
`X_svr_scaled` (standardized feature matrix) and `y_svr` (target array) are now prepared for training and evaluation using **SVR**, **k-NN regression**, or any other regression algorithm that benefits from normalized inputs.

---

## Outlier Detection & Removal via Z-Score

```
from scipy.stats import zscore
import numpy as np

#compute z‐scores on the array that is there:
z_scores = np.abs(zscore(X_svm_scaled))

#set threshold (e.g., 3 standard deviations from mean)
threshold = 3

#then we create mask: True if all features for a sample are within threshold
mask = (z_scores < threshold).all(axis=1)

#apply mask to remove outliers
X_filtered = X_svm_scaled[mask]
y_filtered = y[mask]
```
The cell above filters out extreme outliers from the standardized feature matrix so that downstream models (SVM, k-NN) aren’t unduly influenced by anomalies:


1. Compute absolute Z-scores for each feature in every sample
2. Define outlier cutoff at ±3 standard deviations
3. Build a mask: keep only rows where all feature Z-scores < threshold
4. Apply mask to filter both features and target

---

## SVR Model with GridSearch on Enriched Data


### What This Means

1. **Search Scope**  
   - **48 total fits**:  
     - `C` ∈ {0.1, 1, 10, 100}  
     - `epsilon` ∈ {0.1, 0.3, 0.5, 1.0}  
     - `kernel` ∈ {'linear', 'rbf', 'poly'}

2. **Optimal Hyperparameters**  
   - **`kernel='linear'`**: A linear decision boundary best captures the relationship in the data.  
   - **`C=10`**: A moderate penalty on slack—balances margin width vs. misclassification.  
   - **`epsilon=0.1`**: Very small tube around the regression line, allowing for fine‐grained fit.

3. **Model Performance Metrics**  
   - **RMSE = 0.34**  
     - On average, the SVR’s prediction error is **±0.34 deaths per 100k**.  
     - Compared to a typical range of ~5–25 deaths/100k, this error is **very low**.  
   - **R² = 0.99**  
     - The model **explains 99%** of the variance in 2023 fatality rates per 100k across states.  
     - Indicates an **excellent fit**—almost all state‐to‐state differences are captured.

### Key Takeaways
- A **linear SVR** with these settings generalizes extremely well on the hold-out set.  
- **Low RMSE** and **high R²** suggest the selected features (historical death rates, drinking behavior, road quality, inspection rank) form a nearly perfect linear combination for predicting the target.  
- **Next Steps:**  
  1. **Residual analysis**: now we check for any systematic deviations.  
  2. we then **Compare** against other models (Random Forest, k-NN, GBM) on the same test split.  
  3. lastly, we **Validate** absence of data leakage (especially around normalized “DeathPercentage_2023”).

 ![image](https://github.com/user-attachments/assets/27069666-c3f7-4c07-af04-40df4c8af011)

 ## SVR Predicted vs. Actual Values: Interpretation

The scatter plot below compares the SVR model’s predictions (`y_pred_best`) against the true test‐set values (`y_test`). The red dashed 45° line represents perfect prediction (`predicted = actual`).


### Key Observations

1. **Tight Clustering Along the 45° Line**  
   - Most points lie very close to the red line, indicating the SVR is making highly accurate predictions across the full range (≈ 6–23 deaths per 100k).

2. **Low Scatter & Minimal Bias**  
   - There is no obvious systematic over- or under-prediction: errors are small and symmetrically distributed around the line.

3. **Performance Metrics Align**  
   - An **RMSE of 0.34** and **R² of 0.99** (from the tuning step) are reflected here visually—predicted values deviate by only a few tenths of a death per 100k.

4. **Edge‐Case Accuracy**  
   - Even at the extremes (lowest ~6.7 and highest ~22.6 deaths/100k), the model tracks actual values very closely, demonstrating robustness.

**Conclusion:**  
This plot validates that our SVR (with `C=10, ε=0.1, kernel='linear'`) generalizes exceptionally well on the hold‐out set, providing nearly perfect fit with minimal error.  


![image](https://github.com/user-attachments/assets/5b1c1ff9-c537-4f83-9581-432cc4d89b13)


## SVR Residual Plot Interpretation

Above is the residual plot for the tuned SVR (kernel = linear). Each point shows the **prediction** on the x-axis versus its **residual** (actual – predicted) on the y-axis; the red dashed line is zero error.


### Key Observations

- **Random Scatter Around Zero**  
  Residuals are distributed both above and below the zero line with no obvious curve or trend, indicating the **SVR is unbiased** across the span of predicted values.

- **Consistent Variance**  
  The vertical spread of points remains roughly constant from low (≈ 7) to high (≈ 23) predictions. This suggests **homoscedasticity**—the model’s error variance does not inflate at the extremes.

- **Minor Outliers**  
  A few points (e.g., at **predicted ≈ 9.7**, residual ≈ −0.83) lie further from zero, showing where the model under- or over-predicts by up to ~0.8 deaths per 100k.

- **Alignment with Metrics**  
  The tight clustering confirms that the **low RMSE (0.34)** and **high R² (0.99)** errors are small and symmetric.

---

## k-Nearest Neighbors (k-NN) regression modeling




### What This Means

1. **Optimal Neighborhood Size**  
   - **k = 3** is the sweet spot: each state’s 2023 death-rate prediction is the average of its **3 nearest neighbors** in our 10-dimensional feature space.

2. **Prediction Error (RMSE = 1.52)**  
   - On average, the k-NN predictions deviate by **±1.52 deaths per 100 k**.  
   - In context: if a state’s true rate is 12/100 k, k-NN typically predicts between ~10.5 and ~13.5.

3. **Explained Variance (R² = 0.90)**  
   - The model **captures 90%** of the variation in 2023 death rates across states.  
   - This is solid performance, though slightly below Random Forest (R² ≈ 0.94) and SVR (R² ≈ 0.99).


### Key Takeaways

- **Local vs. Global**: k-NN’s strength is in capturing local patterns—here, using the 3 most similar states.  
- **Baseline Value**: Even though tree- and kernel-based methods outperform it, k-NN provides a valuable non-parametric benchmark.  
- **Model Diversity**: Including k-NN demonstrates that instance-based and model-based approaches are being explored.


### Next Steps

1. **Residual Analysis**: Plot k-NN residuals vs. predictions to check for bias or heteroscedasticity.  
2. **Compare Models**: Lay out RMSE/R² for k-NN, SVR, Random Forest, and Gradient Boosting side-by-side.  
3. **Feature Insights**: we check if k-NN struggles more on certain feature regions—as this can guide further feature engineering.

![image](https://github.com/user-attachments/assets/938c084c-dba4-4c67-9a18-b93fde2573ff)

## k-NN (k=3) Predicted vs. Actual Values: Interpretation

The scatter plot above compares the k-NN model’s predictions (`y_pred_best_knn`) against the true test‐set values (`y_test`) for 2023 death rates per 100k. The red dashed line is the ideal `predicted = actual` diagonal.


### Key Observations

1. **Points Near the 45° Line**  
   - Most states fall close to the red reference line, indicating k=3 produces fairly accurate predictions across the full range (~ 6–23 deaths per 100k).

2. **Slight Under-Prediction at Lower End**  
   - A few of the lowest actual values (~ 6–9) are predicted a bit higher (points lie above the line), showing a slight upward bias on the low side.

3. **Slight Over-Prediction at Upper End**  
   - Conversely, the highest actual state (~ 22.7) is predicted around ~ 20, suggesting a mild downward bias at the top.

4. **Moderate Scatter**  
   - Compared to SVR’s tight clustering, k-NN shows a bit more spread—consistent with its higher RMSE (~ 1.52) and lower R² (~ 0.90).


### Why Include This Plot?

- **Diagnostic Check**: Visually confirms where k-NN performs well and where it systematically errs (low vs. high extremes).  
- **Model Comparison**: When displayed alongside SVR and Random Forest plots, its noticeable which approach tracks the diagonal most tightly.  
- **Communication**: Offers a clear, intuitive summary of k-NN’s accuracy for stakeholders.

Overall, this plot demonstrates that a **3-neighbor** k-NN model provides reasonable predictions but exhibits slightly larger deviations at the extremes compared to more complex models.  

---

## Predicted vs. Actual Comparison: SVR vs k-NN vs Random Forest

![image](https://github.com/user-attachments/assets/b8de9a2f-f9be-4190-ae14-1d709db9d81a)


The three‐panel plot below shows each model’s test‐set predictions against the true 2023 death‐rate per 100k. The red dashed line is the ideal `predicted = actual` diagonal.

### 1. SVR (Left Panel)  
- **Tightest clustering** around the red line: almost no vertical scatter.  
- **Minimal bias** at both low and high ends.  
- **Reflects** RMSE ≈ 0.34 and R² ≈ 0.99: near‐perfect fit.

### 2. k-NN (Middle Panel, k=3)  
- **Moderate scatter**: points close but visibly more spread than SVR.  
- **Slight under-prediction** at low values and slight over-prediction at high values.  
- **Matches** RMSE ≈ 1.52 and R² ≈ 0.90: good but less precise.

### 3. Random Forest (Right Panel)  
- **Greater scatter** than SVR and k-NN, especially in the mid-range.  
- **No strong systematic bias**, but more variance in errors.  
- **Consistent** with RMSE ≈ 1.28 and R² ≈ 0.94: strong but not as tight as SVR.


### Overall Takeaways

- **SVR** delivers the **best** predictive accuracy (lowest RMSE, highest R², tightest points).  
- **Random Forest** sits in the **middle**—very good but slightly more error spread.  
- **k-NN** provides a **solid baseline**, yet shows the most deviation at the extremes.

Including all three side-by-side highlights how different algorithmic approaches trade off bias vs. variance, and confirms SVR as the top performer on this task.  

## Residual Comparison: SVR vs k-NN vs Random Forest

![image](https://github.com/user-attachments/assets/705c0342-6bf4-47df-a656-5befbbcff22b)

Above is the three‐panel residual plot for the tuned models. Each panel shows the model’s predicted value on the x-axis and the residual (Actual − Predicted) on the y-axis, with the red dashed line at zero error.

### 1. SVR Residuals (Left Panel)
- **Tight clustering** within ±1 death per 100k, with most residuals near zero.  
- **No obvious pattern** or funnel shape—errors are homoscedastic (constant variance).  
- **Interpretation:** SVR produces very small, unbiased errors across the whole range, confirming its **best** performance (RMSE ≈ 0.34, R² ≈ 0.99).

### 2. k-NN Residuals (Middle Panel)
- **Moderate spread** of residuals roughly between −3 and +2.5 deaths per 100k.  
- **Symmetric** around zero, though a slight under-prediction at the low end and slight over-prediction at higher predictions.  
- **Interpretation:** k-NN (k = 3) yields larger errors than SVR but still performs well overall (RMSE ≈ 1.52, R² ≈ 0.90).

### 3. Random Forest Residuals (Right Panel)
- **Widest spread**: residuals range from about −7.5 to +7 deaths per 100k.  
- **No clear bias** (points scatter above and below zero) but **high variance**, especially at mid‐range predictions.  
- **Interpretation:** While Random Forest captures most trends (RMSE ≈ 1.28, R² ≈ 0.94), it produces the largest outliers, indicating it’s more prone to occasional large misses.


### Overall Takeaway
- **SVR** is the most **consistent** and **precise**, with minimal residual spread.  
- **k-NN** is a solid middle ground with moderate error dispersion.  
- **Random Forest** shows higher variance in its errors, leading to occasional large prediction misses.  

Including this comparison helps validate not just average accuracy (RMSE/R²) but also the **error behavior** of each algorithm—critical for understanding reliability in real‐world applications.  

## Model Performance Comparison: SVR vs k-NN vs Random Forest

![image](https://github.com/user-attachments/assets/ca7fd228-54bb-41f7-90db-0300ecd2805a)


Above are two side-by-side bar charts comparing each model’s error (RMSE) and explained variance (R²) on the same hold-out test set.


### 1. RMSE (Lower Is Better)

| Model          | RMSE  |
|---------------:|------:|
| **SVR**        | 0.34  |
| k-NN (k = 3)   | 1.52  |
| Random Forest  | 1.28  |

- **SVR** has by far the smallest average error (±0.34 deaths/100k).  
- **Random Forest** comes in second (±1.28), nearly five times larger error than SVR.  
- **k-NN** performs worst on this metric (±1.52), though still within a couple of deaths/100k.


### 2. R² Score (Higher Is Better)

| Model          | R²   |
|---------------:|-----:|
| **SVR**        | 0.99 |
| Random Forest  | 0.94 |
| k-NN (k = 3)   | 0.90 |

- **SVR** explains **99%** of the variance—an almost perfect fit.  
- **Random Forest** explains 94%, indicating a very strong but slightly less precise model.  
- **k-NN** explains 90%, still solid but trailing the other two.


### Key Takeaways

1. **SVR** is the **clear winner**: lowest RMSE and highest R².  
2. **Random Forest** is a strong runner-up, balancing bias and variance well.  
3. **k-NN** provides a useful baseline but shows higher error and lower explained variance.  

These comparisons confirm that **SVR** (with tuned hyperparameters) is the best predictive model for state-level car-accident death rates per 100k.

## Death Percentage Predicted for 2024 (Gradient Boosting Regressor)
### Predicting Future Accident Trends

Now that we have evaluated our models by predicting known values from previous years and comparing them to actual outcomes, we can move forward with forecasting future data points.

In this step, we use historical data from 2022 to train a regression model that predicts the death percentage for 2023. Once validated, we apply the same model using 2023 data as input to estimate the projected death percentage for 2024, a year for which we currently do not have actual records.

This forward-looking prediction helps simulate likely outcomes and identify potential risk patterns.

![image](https://github.com/user-attachments/assets/adc17de4-2c40-4cc5-b604-ccc53e75e6ed)


### 1. Tabular Ranking of All 50 States

| Rank | State         | Predicted 2024 Death % |
|-----:|---------------|-----------------------:|
| 1    | **Mississippi** | 9.40%                |
| 2    | Arkansas      | 7.81%                |
| 3    | New Mexico    | 7.73%                |
| 4    | Oklahoma      | 7.37%                |
| 5    | Louisiana     | 7.00%                |
| …    | …             | …                    |
| 46   | Hawaii        | 2.21%                |
| 47   | Connecticut   | 2.53%                |
| 48   | New Hampshire | 2.49%                |
| 49   | Rhode Island  | 2.06%                |

- **Top 5** states are all above **7%**, with Mississippi nearly **9.4%**.
- **Bottom 5** states remain below **3%**, led by Rhode Island at just over **2%**.


### 2. Split‐Bar Chart Insights

**Top 25 States (Upper Panel)**
- **Green bars** (2024 predictions) mostly sit between the **blue** (2022) and **orange** (2023) bars, showing the model captures steady trends.
- Some high‐risk states (e.g., Mississippi, Arkansas) show a **slight drop** from 2023 → 2024, hinting at potential improvements.
- Others (e.g., New Mexico, Oklahoma) maintain or slightly increase, suggesting persistent risk factors.

**Bottom 25 States (Lower Panel)**
- Many low‐risk states display **small decreases** from 2023 → 2024, reinforcing continued safer outcomes.
- States like Rhode Island and Massachusetts stay **below 3%**, with marginal year‐over‐year gains in safety.


### 3. Overall Takeaways

1. **High‐Risk Persistence:** The same states that topped the fatality charts in 2022–2023 (Mississippi, Arkansas, etc.) are forecast to remain highest in 2024.  
2. **Low‐Risk Stability:** States at the low end continue to cluster below 3%, with slight additional improvements predicted.  
3. **Model Validity:** The alignment of 2024 predictions between the two visual and tabular formats confirms the model is effectively learning from historical data and projecting modest, realistic year‐over‐year changes.


### Predicting Future Accident Trends

Now that we have evaluated our models by predicting known values from previous years and comparing them to actual outcomes, we can move forward with forecasting future data points.

In this step, we use historical data from 2022 to train a regression model that predicts the death percentage for 2023. Once validated, we apply the same model using 2023 data as input to estimate the **projected death percentage for 2024**, a year for which we currently do not have actual records.

This forward-looking prediction helps simulate likely outcomes and identify potential risk patterns, allowing for better policy planning and safety intervention strategies.


## What happens if seat-belt usage rises by 5 pp statewide?

![image](https://github.com/user-attachments/assets/f768f8c8-df4a-4a77-83c1-e0e065a2e617)

### States that benefit most from +5 pp seatbelt use

| State       | Baseline_2024_% | With_+5pp_Seatbelt_% |  Delta_% |
|-------------|----------------:|---------------------:|---------:|
| New Mexico  |          0.0773 |               0.0718 |  -0.0055 |
| South Dakota|          0.0551 |               0.0500 |  -0.0051 |
| Colorado    |          0.0469 |               0.0425 |  -0.0043 |
| Tennessee   |          0.0630 |               0.0590 |  -0.0040 |
| Texas       |          0.0600 |               0.0561 |  -0.0039 |

### States with smallest predicted benefit

| State         | Baseline_2024_% | With_+5pp_Seatbelt_% | Delta_% |
|---------------|----------------:|---------------------:|--------:|
| Missouri      |          0.0572 |               0.0581 |   0.0009 |
| Ohio          |          0.0416 |               0.0426 |   0.0010 |
| New Hampshire |          0.0249 |               0.0261 |   0.0012 |
| North Dakota  |          0.0442 |               0.0462 |   0.0021 |
| Nebraska      |          0.0412 |               0.0451 |   0.0039 |

### Impact of +5pp Increase in Seatbelt Usage: Interpretation

The bar chart aboce shows, for each state, how the **predicted 2024 death percentage** (per registered vehicle) changes when we simulate a **5-percentage-point increase** in seatbelt use:

**Key Takeaways**

- **Largest Predicted Reductions**  
  - **New Mexico** (~–0.0055 pp)  
  - **South Dakota** (~–0.0047 pp)  
  - **Colorado** (~–0.0042 pp)  
  - **Tennessee** (~–0.0040 pp)  
  - **Texas**, **Michigan**, **Mississippi**, **Kentucky**, **Vermont**, **Florida**, **North Carolina** all see decreases between –0.0035 and –0.0040 pp.

- **Moderate or Negligible Change**  
  - States like **Iowa**, **Delaware**, **Massachusetts**, **Minnesota**, **Nevada**, **Hawaii**, **Maine**, **Alaska**, **Montana**, **Oregon**, **California**, **Alabama**, **Arkansas**, **Connecticut**, **New York**, **South Carolina**, **Idaho**, **Indiana**, **Washington**, **West Virginia** cluster around zero change (±0.001 pp).

- **Unexpected Predicted Increases**  
  - **Nebraska** (+0.0035 pp), **North Dakota** (+0.0025 pp), **New Hampshire**, **Ohio**, **Missouri**, **Georgia**, **Virginia**, **Pennsylvania** show small increases in predicted deaths.


**What This Means**

- In most states, a 5 pp rise in seatbelt compliance is forecast to **reduce** fatality rates by up to about **0.55 percentage points**, with the biggest gains in states that currently have lower compliance or higher baseline risk.
- A handful of states show **slight increases**, which reflect the model’s complex, non-monotonic decision boundaries and interactions with other features (e.g. alcohol metrics, historical death rates). In some regions of feature space—especially near the extremes—boosted‐tree ensembles can produce counterintuitive predictions unless monotonic constraints are imposed.
- Overall, the exercise underscores the potential public-safety benefit of improving seat-belt usage, while also illustrating the importance of understanding model behavior before drawing policy conclusions.


## What if excessive drinking drops by 10%?

![image](https://github.com/user-attachments/assets/d6cb4cfb-b1da-4d7f-9a36-57ad555b34d5)

### Interpretation: Impact of a –10pp Decrease in Excessive Drinking Rate

When we simulate a 10 percentage‐point drop in each state’s excessive‐drinking rate (2023) and re-predict the 2024 death percentage, we observe:

- **Largest Benefits (≈ –0.0055 to –0.0045 pp):**  
  - **Montana, Nebraska, Virginia, Iowa, Kansas, Arizona, North Carolina** and several others at the top of the chart see the biggest reductions in predicted fatality rate (up to roughly 0.55 percentage points less mortality per vehicle).
  - These states likely had higher baseline excessive‐drinking rates, so a 10 pp cut shifts them into regions where the model predicts substantially fewer deaths.

- **Moderate Benefits (≈ –0.0040 to –0.0030 pp):**  
  - Mid-rank states such as **Indiana, Georgia, Kentucky, Ohio, Texas**, etc., each experience decreases around 0.3–0.4 pp in the predicted death percentage.

- **Minimal or No Impact (≈ 0 to –0.001 pp):**  
  - The bottom of the list—**Alaska, West Virginia, Utah, New Mexico, Mississippi, Oklahoma, Alabama, Tennessee**, etc.—shows almost zero change.
  - This suggests excessive drinking was already low in those states, or that the model attributes their fatality risk more strongly to other factors (e.g. historical death rates, vehicle counts).


**Conclusion:**  
A statewide 10 pp reduction in excessive‐drinking rates would yield non-uniform benefits. States with high baseline drinking show the greatest drop in predicted fatalities, whereas states with low drinking rates see negligible change. This highlights the potential for targeted alcohol‐reduction policies to meaningfully lower traffic deaths, especially in high-drinking states.  


## Clustering States by Risk Profile & Scenario Analysis

In this section, we use **K-Means clustering** to group U.S. states based on their 2023 accident-related profiles. By clustering on key features such as fatality rates, seatbelt usage, alcohol involvement, road quality, and vehicle prevalence, we aim to uncover distinct patterns and groupings among states.

Once the clusters are established, we simulate a **hypothetical policy intervention**—a 5 percentage point increase in seatbelt usage—and examine how this change might shift state-level cluster membership.

This approach enables us to:
- Identify states with similar safety profiles
- Understand the defining characteristics of each cluster
- Assess how certain behavioral changes (e.g., improved seatbelt compliance) could impact a state’s safety classification

Finally, we visualize the clustering in two dimensions and list which states belong to each group before and after the scenario adjustment.

![image](https://github.com/user-attachments/assets/977bc14c-bfed-4cbf-a6d5-912283e138a2)

- 0: Louisiana, Colorado, Wisconsin, Nebraska, Montana, Maine, South Dakota, North Dakota, Alaska
- 1: California, Ohio, Illinois, Pennsylvania, New York, Michigan, Virginia, Washington, New Jersey, Oregon, Maryland, Minnesota, Massachusetts, Connecticut, Iowa, New Hampshire, Vermont
- 2: Texas, Florida, Georgia, North Carolina, Tennessee, Arizona, South Carolina, Missouri, Alabama, Indiana, Kentucky, Oklahoma, Mississippi, Arkansas, New Mexico, Nevada, Kansas, Utah, West Virginia, Idaho, Delaware, Wyoming
- 3: Hawaii, Rhode Island

### Cluster Profiles Overview

| Cluster | Color  | Death % (2023) | Alcohol Fatalities % (2023) | Profile |
|-------|------|--------------|---------------------------|--------|
| 0       | Blue   | ~0.035–0.070   | ~35–47 %                    | Moderate-high overall fatality states that also have very high alcohol-related share. |
| 1       | Orange | ~0.025–0.040   | ~28–35 %                    | Lower-risk states: below-average death rates and only moderate alcohol involvement. |
| 2       | Green  | ~0.050–0.098   | ~23–38 %                    | High-fatality states where alcohol plays a somewhat smaller role compared to cluster 0. |
| 3       | Red    | ~0.020–0.025   | ~38–40 %                    | A tiny “outlier” group with very low total death rates but an unusually large alcohol share. |


## Risk Classification


### Best Hyperparameters:
 - rf__n_estimators: 200
 - rf__min_samples_split: 2
 - rf__max_depth: None

**Cross-Validation Accuracy:** 0.70


### Hold-Out Test Performance
Overall accuracy: 0.70


### Class-wise metrics:
   
**High**
- Precision = 1.00
- Recall    = 0.75
- F1-score  = 0.86
- Support   = 4

**Low**
- Precision = 0.60
- Recall    = 1.00
- F1-score  = 0.75
- Support   = 3

**Medium**
- Precision = 0.50
- Recall    = 0.33
- F1-score  = 0.40
- Support   = 3

### Confusion Matrix (rows = true class, columns = predicted class):
 - [3, 0, 1]    True High → Predicted High = 3, Low = 0, Medium = 1
 - [0, 3, 0]     True Low  → Predicted Low = 3
 - [0, 2, 1]     True Medium → Predicted Low = 2, Medium = 1

### True vs. Predicted for Hold-Out States:
| State          | TrueRisk | PredictedRisk |
|----------------|----------|---------------|
| Wisconsin      | Low      | Low           |
| Mississippi    | High     | High          |
| Alaska         | Medium   | Low           |
| West Virginia  | High     | High          |
| New Mexico     | High     | High          |
| Maine          | Medium   | Medium        |
| Idaho          | Medium   | Low           |
| Ohio           | Low      | Low           |
| Louisiana      | High     | Medium        |
| Connecticut    | Low      | Low           |

### Takeaway
 - The model is very good at spotting High-risk and finds every Low-risk state, but it struggles to distinguish the “middle” group.
 - The model perfectly identifies all Low-risk states (recall=1.0) and never mislabels another class as High (precision=1.0 for High).  
 - It misses 1 of 4 High states (recall=0.75) and sometimes confuses Medium states as Low.  
 - The Medium class is the hardest to predict (recall=0.33).  


### Definitions:
 - F1-score: the harmonic mean of precision and recall, balancing false positives and false negatives.
 - Support: the number of actual occurrences of each class in the test set.

# Final Remarks <a name="fr"></a>

Through this analysis, we applied a range of machine learning techniques to explore, predict, and simulate patterns in U.S. state-level traffic fatality data. We began by enriching our dataset with meaningful derived features and then evaluated multiple regression models (SVR, Gradient Boosting) to predict known and future accident-related outcomes.

In addition to regression, we used clustering to identify latent groupings among states and conducted scenario-based simulations to observe how changes in specific features—such as seatbelt usage—can affect cluster membership.

This end-to-end workflow demonstrates the application of machine learning for exploratory and predictive analysis, using real-world, multi-dimensional data in a structured, reproducible process.
