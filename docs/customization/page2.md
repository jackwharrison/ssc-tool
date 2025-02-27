# **Adding Indicators**

Before adding any data to the system, an indicator must be created to define how the system will process the data.

There are three types of indicators:

- **General** (Stored in the Indicator Bank)

  Contains indicators for **pillar data** and **baseline vulnerability data**. Each indicator can only contain one theme and sub-theme, so if you have data which contains multiple themes, such as an MSNA, please create seperate indicators for each theme.

- **Impact Indicators**

  Used for assessing **immediate post-disaster impact**.

- **Hazard Indicators**
  
  Used to evaluate **underlying risks** associated with specific hazards, such as typhoons or volcanoes.

## General Indicators

### 1. Overview Page

The create page for the indicator bank will look like this:

![image](https://github.com/user-attachments/assets/9a4571e5-2762-4f27-a64b-a092bfc5695f)

- **Indicator Name**

Provide a concise but clear name for your indicator

- **Country**

Select the country for which this indicator is relevant

- **Data Type**

Gradient data: A type of data that can be represented by a number. (e.g., poverty rate or population density)

Categorical data: A type of data that can be stored into groups or categories with the aid of names or labels, and is not represented by a numerical value. (e.g., building type)

- **Indicator Weight**

This value determines the weight of this indicator in the overall score for the sub-theme.

Typically there will only be 1 indicator per sub-theme, which is why the default value is 1, but if there are more, please indicate how they should be weighted.

- **Admin Level:**

To what administrative level do we have data for this indicator.

- **Area or HH data?**

Please specify whether the data is based on area level or household level.

- **Source**

If possible, please provide information regarding the source of the data for future reference.

### 2a. Indicator Information (Gradient & Pillar Data)

The second page, titled 'Indicator Information', will appear different based on the type of indicator, if it is gradient or categorical data, or if it is pillar or vulnerability data.

![image](https://github.com/user-attachments/assets/d9b7f9b1-d2a3-479a-8e40-1dc999594311)

- **Timeframe**

Is this data from before or after a disaster

- **Indicator Category**

This refers to the category of the indicator, broadly each category is defined as such:

Pillar 1: Can people live in safe and dignified dwellings (structures that protects them against external threats, health problems, weather and natural hazards)

Pillar 2: Can people live properly and with dignity in their dwelling, and are they able to properly practice domestic functions

Pillar 3: Can people access common services and infrastructure

Baseline vulnerability: This refers to an indicator which does not fit into any of the above three pillars, but affects the severity of the shelter risk, such as poverty

- **Theme**

Select the theme that best fits your indicator

- **Sub-Theme**

Select the sub-theme that best fits your indicator. Note that not all themes contain sub-themes.

- **Criteria 1, 2, 3 & 4**

These are set for each theme & sub-theme, and have been aligned with the SSC framework specified by the GSC

- **Ascending / Descending**

Indicates whether a higher value increases (Ascending) or decreases (Descending) vulnerability.

Ascending examples: poverty rate, unemployment.

Descending examples: literacy rate, access to clean water.

- **Category Boundaries**

For ascending data, values below this threshold belong to the lowest vulnerability category (Category 1).
Note: If there are only two categories in this theme / sub-theme, all values above this fall into category 2.

For descending data, values above this threshold belong to the lowest vulnerability category (Category 1).
Note: If there are only two categories in this theme / sub-theme, all values below this fall into category 2.

- **Use default values for this sub theme**

Press this button to use the default values, these are shown in brackets in the criteria definitions

- **Scores**

These fields can be edited if you do not wish to use the default score values.

### 2b. Indicator Information (Categorical & Pillar Data)

For categorical data, the view looks like this:

![image](https://github.com/user-attachments/assets/eb82329e-482d-43bb-ae48-080f3d8232f5)

This is similar to the above view, however the key difference is how we define each category.

Here there is a text box for you to provide definitions of the values that fall into each category. For example, if you are looking at latrine type, 'No toilet' may be criteria 3, and 'Sealed toilet', may be criteria 1.

