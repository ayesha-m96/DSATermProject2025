DSATermProject
# Identifying State-Level Corelates of Car Fatalaties in U.S. States
Ayesha Musharaf - 33617

# Contents
1. [Project Overview](#Proj-Overview)
2. [Research Questions and Objectives](#rqao)
3. [Motivation](#moti)
4. [Datasets](#datase)
5. [Hypothesis](#hypo)
6. [Dataset Analysis Plan](#dap)
    - Data Collection
    - Data Preproccessing
    - Exploratory Data Analysis
8. [Limitations and Future Work](#lafw)
9. [Conclusion](#conc)

# Project Overview <a name="Proj-Overview"></a>
<p align="justify"> This project aims to analyze the factors contributing to fatal car accidents in United States by looking at the relationships between fatal car accidents in the United States and various other factors. The primary dataset "Fatal Car Accidents by State" will serve as the dependent variable, while the other datasets will act as independant variables. The goal is to find out the correlation of factors in order of assosiation. </p>
<p align="justify"> Using Statistical analysis and data vizualization techniques, the project will explore trends across states, helping find an inference vetween the factors. Additionally, conclusion of this project should help with transportation authorities to use the data to reduce fatal car accidents and improve road safety. </p>

# Research Questions and Objectives <a name="rqao"></a>
### Research Questions
- Which Factors have the strongest correlation with fatal car accidents in the United States?
- Are there regional patterns in fatal car accidents?
- Does the absence of vehicle inspection programs contrivute significantly to fatal accidents?
- Is there a relationship between the number of vehicles per capita and fatal car accidents?
- Do states with higher speed limits experience more fatal car accidents?

### Objectives 
- Determine which factors are most strongly related with fatal car accidents.
- Use maps, bar charts, and scatter plots to visualize relationships between variables.
- Utilize data cleaning, merging, statistical analysis, and visualization techniques to find meaningful conclusions

# Motivation <a name="moti"></a>
<p align="justify"> For me, this project is motivated by a desire to understand the very high rate of fatal accidents in the United States. Many lives are lost each year due to accidents that can be prevented. It is key to identify and analyse these factors that can help with the preventation of such accidents. </p>

# Datasets <a name="datase"></a>
<p align="justify"> This section provides a conside overview of the datasets used in the analysis, including their descriptions, to highlight its relavance to study of fatal car accidents. </p>

| Dataset  | Description |
| ------------- | ------------- |
| Fatal Car Accidents by State | State-level data on fatal car accidents in the U.S. |
| Speed Limits by State  | State-level data on maximum speed limits for highways and roads across the U.S. |
| Alcohol Consumption by State | State-level data on per capita alcohol consumption |
| Seat Belt Use by State | State and territory-level data on seat belt usage rates in the U.S. |
| Road Quality by State | State-level data on road quality metrics across the U.S. |
| States Without Vehicle Inspection | State-level data on vehicle safety inspection requirements across the U.S. |
| Population by State | State-level data on population rankings across the U.S. |

# Hypothesis <a name="hypo"></a>
- Null Hypothesis (H₀): There is no significatn relationship between fatal car accidents and other varaible factors such as speed limits, alcohol consumption, road quality, vehicle iunspection requirements, seat belt usage, and vehicle capita across U.S states.
- Alternate Hypothesis (H₁): Atleast 1 factor has a significant relationship with fatal car accident rates across U.S states such as speed limits, alocohol consumption, road quality, vehicle inspections, seat belt usage, or vehicles per capita acros U.S. states.

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
- Merge the datasets by state to create a unified dataset for analysing
- Ensure consistent state naming conventions and handle missing data

## Data Preproccessing
**Data Cleaning**
- Handle Missing Values by removing them or imputation
- Standardize units and formats acorss datasets

**Feature Engineering**
- Create derived variables
- Categorize Variables

## Exploratory Data Analysis
- **Univariate Analysis:**
  - Summarize and visualize individual variables
  - Use histograms, box plots, and summary statistics
- **Bivariate Analysis:**
  - Explore relationships between fatal car accidents and each independant variables
  - Use scatter plots, correlation matriices, and grouped bar charts
- **Multivariate Analysis:**
  - Examine interations between multiple variables
  - Use heatmaps and grouped vizualizations

# Limitations and Future Work <a name="lafw"></a>
## Limitations
### Data Quality and Availability
- **Missing Data:** Some states may have incomplete or missing data for certain variables.
- **Inconsistent Reporting:** Differnces in how states report fatal accidents could introduce bias.

### Causation
- **Reverse Causality:** For example, states with higher accident rates might implement stricter speed limits, creating a misleading relationship.

### Bias in Self-Reported Data
- **Alcohol Consumption:** Alcohol Consumption data may not account for illegal or unreported drinking.

## Future Work
- Incorporate additional variables, such as weather conditions, traffic density, and distracted driving statistics.
- Expand the scope to include local-level data for more granular analyses.

# Conclusion <a name="conc"></a>
<p align="justify"> This project aims to identify key factors influencing fatal car accidents across U.S. states by analyzing datasets on speed limits, alcohol consumption, road quality, vehicle inspections, seat belt usage, and vehicles per ccapita. Using exploratory data analysis, hypothesis testing, and statistical modeling, it will explore correlations between these variables and fatal accident rates, providing insights to improve road safety. </p>
