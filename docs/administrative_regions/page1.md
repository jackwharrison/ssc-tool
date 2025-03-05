# Administrative Regions  

The SSC tool calculates scores for each administrative region, depending on data availability. It currently supports four levels of administrative regions, ranging from ADM0 to ADM3.  

- **ADM0** always represents the country.  
- **ADM1, ADM2, and ADM3** represent progressively smaller administrative divisions, though their specific names vary by country.  

## Administrative Regions in the Tool  

Each administrative level is represented by a separate entity within the tool. While ADM1, ADM2, and ADM3 share a similar structure, ADM0 (the country level) is structured differently. The differences at ADM0 will be explained in detail later.  

## ADM1 to ADM3  

ADM1 to ADM3 follow a similar structure, with only minor differences. This section will primarily focus on ADM2 as a reference point for understanding these administrative levels.  


### Overview:

![image](https://github.com/user-attachments/assets/57f58a64-2acf-4b29-81f8-eb3d3e86311a)

- **Name:** The name of this administrative region. 
- **ADM1:** The name of the ADM1 region that this region belongs to.  
- **Country:** The country where this region is located.  
- **PCODE:** A unique identifier assigned to each administrative region to ensure accurate matching.  
- **Population:** The total population within this administrative region.  
- **Adjusted Severity Score:** The overall shelter vulnerability score, calculated using the decision tree method and adjusted for baseline vulnerability.  
- **Shelter Vulnerability Score:** The shelter vulnerability score derived from the decision tree method before adjustments.  
- **Refresh:** Click this button to refresh the calculations. (Press the small blue pencil icon on the right to unlock it.) The button will reset to an unclicked state once calculations are complete. Be sure to refresh the page to view any updates.  

- **Decision Tree:** The decision tree used to calculate the overall severity score. By default, it is set to the decision tree configured by the Global Shelter Cluster but can be modified as needed.  
- **Threshold:** Defines the percentage of lower administrative regions required at a specific score for it to be displayed at this administrative level. For example, if set to 20% (0.2), the highest cumulative score meeting this threshold will be shown. If 15% of lower regions have a score of 5, 4% have a score of 4, and 2% have a score of 3, then the displayed score will be 3.  

All fields are read-only except for **'Refresh'**, **'Decision Tree'**, and **'Data Timeframe'**.  


### Overall Pillar Themes & Scores

![image](https://github.com/user-attachments/assets/a6567449-e033-494f-a7ef-4c8d366f1a7b)

This page reflects data across all administrative regions. It is divided into the individual pillars, and shows the score in each theme as well as the pillar score. For more information on the definitions of these pillars or themes, see **[here](../general/page1.md)**.

Scores are calculated across administrative layers in two ways:

1. **Local Pillar Score:** This score is derived solely from data specific to a given administrative layer. For example, if an indicator is only available at admin level 2 (ADM2), it will contribute to the local pillar score for ADM2 but not for ADM1 or ADM3. Each administrative layer has its own local pillar score.

2. **Overall Pillar Score:** This score incorporates data from multiple administrative layers. For higher administrative layers, the local pillar score is assumed to represent all lower-level regions within it and is included in the overall pillar score. For lower administrative layers, if data coverage exceeds a predefined threshold, those scores are also factored into the overall pillar score. Finally, the local pillar score itself is always included in the overall pillar score.


### Region Level Pillar Themes & Scores

![image](https://github.com/user-attachments/assets/3c074be6-cd7c-44e5-b1f8-bc474b8d036b)

This page is the same as the previous page, however it only shows local pillar scores data.

### Baseline Vulnerability Information

![image](https://github.com/user-attachments/assets/4f554998-2ba2-4ad8-a839-a781f2f9d710)

This page displays **vulnerability data**—factors that fall outside the three pillars but still impact household vulnerability. It includes two key fields:  

1. Vulnerability Threshold  
This represents the percentage of a region’s population that must fall into a specific category for the region to be classified as vulnerable. It is expressed as a decimal (e.g., `0.2 = 20%`).  

For example, if more than **20% of the population** lives in poverty, the region is considered **vulnerable**. When a region is deemed vulnerable, this increases the **Adjusted Severity Score**.  

2. Percentage of Population that is Vulnerable  
This represents the proportion of the population that is **likely to be vulnerable**.  

- This calculation is based on **lower administrative regions**.  
- If a lower admin region exceeds the vulnerability threshold, the **entire region** is classified as vulnerable.  
- In this example, if **all lower admin regions** surpass the threshold, the entire region is considered vulnerable.  

### Hazard Scores

![image](https://github.com/user-attachments/assets/f4cbcfb4-ddac-4455-a838-c453a8a7248a)

This page provides **risk scores** for five major hazards, along with the option to include **region-specific hazards**. The five primary hazards are:  

- **Volcano Risk**  
- **Typhoon Risk**  
- **Flood Risk**  
- **Earthquake Risk**  
- **Conflict Risk**  

If data for a particular hazard is unavailable, that field will not appear.  

**Important Note:**
These risk scores are based on indicators that may only capture **a specific aspect** of a hazard. For example, **typhoon risk** may only reflect **storm surge**, rather than the full impact of a typhoon.  

As a result, these scores should be used **as guidance only** and not as a definitive assessment of risk.  


### Bottom Panels 

![image](https://github.com/user-attachments/assets/f836ce6a-42b5-4004-a5ad-c0b0d66c30f2)

At the bottom of each page, **data panels** display all the individual data points that contribute to the scores for that administrative region.  

## ADM0 (Country level)


