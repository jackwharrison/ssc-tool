# **Indicator Bank**

All pillar scores and baseline vulnerability scores are calculated using predefined indicators, which are created and managed within the indicator bank.

# Indicator Overview

![image](https://github.com/user-attachments/assets/01d9fdd6-74b5-4c8b-8c0b-4f91b83a497b)



This section provides an overview of key metadata fields related to an indicator.  

- **Indicator Name** – The name of the indicator being displayed.  
- **Country** – The country for which the data applies.  
- **Data Type** – Specifies whether the data is **Categorical** (grouped into categories) or **Gradient** (numerical values).  
- **Indicator Weight** – A value indicating the relative importance of the indicator.  
- **Admin Level** – The administrative level at which the data is available (e.g., **ADM1** for regional data).  
- **Area or HH data?** – Indicates whether the data represents an **Area** or **Household** level dataset.  
- **Source** – A reference link to the original data source.

# Indicator Information Overview (Categorical Data)

![image](https://github.com/user-attachments/assets/cbb1b770-9d7d-4270-a729-30aa696ab134)

This section provides details on an indicator, including its classification and scoring criteria. The displayed information is specific to **categorical data**, meaning the indicator is grouped into predefined categories rather than represented as a numerical value.

## Fields  

- **Timeframe** – Specifies whether the indicator applies to a pre-disaster, during-disaster, or post-disaster scenario.  
- **Indicator Category** – Defines the broader classification of the indicator, which determines its focus:  
  - **Pillar 1** – Assessing whether people can live in safe and dignified dwellings that protect them from external threats, health risks, weather, and natural hazards.  
  - **Pillar 2** – Evaluating whether people can live properly and with dignity in their dwellings and carry out domestic functions.  
  - **Pillar 3** – Determining whether people can access common services and infrastructure.  
  - **Baseline Vulnerability** – Covers factors that do not fit within the three pillars but influence shelter risk severity, such as poverty.  

## Pillars  

- **Pillar Definition** – Describes the aspect of shelter conditions that the indicator measures.  
- **Theme** – A broad category under the pillar (e.g., Energy).  
- **Sub-Theme** – A more specific category within the theme (e.g., Communications and Livelihoods - Energy).  

## Categories and Scoring  

- **Criteria** – The classification of conditions related to the indicator, each assigned a score:  
  - **Criteria 1** – Represents an optimal condition (e.g., "Available" = Score **0**).  
  - **Criteria 2** – Represents a partial fulfillment of the condition (e.g., "Partially Available" = Score **0.5**).  
  - **Criteria 3** – Represents a severe issue (e.g., "Not Available" = Score **1**).  
- **Values fitting each criteria** – Provides a description of the data that falls under each category.  
- **Threshold** – Defines the value used to assess severity.  
- **Default values for sub-theme** – Specifies whether the predefined scoring system is applied.  

### Notes:  
- The **criteria, scores, theme, and sub-theme** vary depending on which **pillar** is selected.  
- This structure ensures a standardized approach to classifying categorical data within shelter assessments.


# Indicator Information Overview (Gradient Data)

![image](https://github.com/user-attachments/assets/fe89c266-60bb-486f-bff3-d6acb9f2dd04)

This section provides details on an indicator using **gradient data**, meaning values are represented numerically rather than as predefined categories. The data is classified based on thresholds, determining the level of vulnerability.

## Fields  

- **Timeframe** – Specifies whether the indicator applies to a pre-disaster, during-disaster, or post-disaster scenario.  
- **Indicator Category** – Defines the broader classification of the indicator, which determines its focus:  
  - **Pillar 1** – Can people live in safe and dignified dwellings that protect them from external threats, health risks, weather, and natural hazards?  
  - **Pillar 2** – Can people live properly and with dignity in their dwellings, and are they able to properly practice domestic functions?  
  - **Pillar 3** – Can people access common services and infrastructure?  
  - **Baseline Vulnerability** – Covers factors that do not fit within the three pillars but influence shelter risk severity, such as poverty.  

## Pillars  

- **Pillar Definition** – Describes the aspect of shelter conditions that the indicator measures.  
- **Theme** – A broad category under the pillar (e.g., Energy).  
- **Sub-Theme** – A more specific category within the theme (e.g., Communications and Livelihoods - Energy).  

## Data Classification  

- **Ascending / Descending** – Determines how vulnerability is measured:  
  - **Ascending** – Higher values indicate increased vulnerability (e.g., poverty rate, unemployment).  
  - **Descending** – Higher values indicate reduced vulnerability (e.g., literacy rate, access to clean water).  
- **Category Boundaries** – Defines the threshold for classification:  
  - For **ascending data**, values **below** the threshold belong to the **lowest vulnerability category (Category 1)**. If only two categories exist, all values above fall into **Category 2**.  
  - For **descending data**, values **above** the threshold belong to the **lowest vulnerability category (Category 1)**. If only two categories exist, all values below fall into **Category 2**.  
- **Threshold** – The numerical value that determines category boundaries.  

### Notes:  
- The **theme, sub-theme, and thresholds** vary depending on the **selected pillar**.  
- This structure ensures a standardized approach to classifying gradient data within shelter assessments.  
