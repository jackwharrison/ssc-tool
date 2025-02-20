### Shelter Severity Classification Tool


<!-- markdownlint-disable-next-line no-trailing-punctuation -->

Welcome to the Shelter Severity Classification Tool training!
It covers access to the system, explains how the system works, how to add indicators and data to the system, how to interpret the results, and how to export the data. This training covers how to use the system as both a user and an admin. We will go through each entity one by one, so you can better understand how the tool works.

If you are using this training module for self-study, you are advised to follow the navigation list starting with the General chapter. The Customisation part is optional and is intended for experienced EspoCRM administrators willing to develop their entities and flowcharts further. 

**On the left you can find a navigation overview**  

---
<!-- markdownlint-disable -->
<div class="grid cards" style="grid-template-columns: 1fr 1fr;" markdown>

- **[:material-clock-fast: General](./general/index.md)**  
  This section provides an overview of the current Shelter Severity Classification system developed by the Global Shelter Cluster and its connection to this tool.

- **[:fontawesome-solid-users-gear: Administrative Divisions](./administrative_regions/page1.md)**  
  The tool allows users to navigate between different administrative layers within a country, from Admin Level 0 (ADM0) down to Admin Level 3 (ADM3). These layers can be customized to reflect regional naming conventions.  
  _For example, in the Philippines, the administrative levels are called:_  
  - **Country (ADM0)**  
  - **Region (ADM1)**  
  - **Province (ADM2)**  
  - **Municipality (ADM3)**  

- **[:fontawesome-solid-people-roof: Indicators and Decision Trees](./indicators_and_decision_trees/page1.md)**  
  **The calculation framework is primarily defined by selecting which indicators to use. These indicators fall into two main categories:**  

  - **Non-hazard indicators:** Pre- or post-disaster, categorized into Pillar 1, Pillar 2, Pillar 3, Vulnerabilities, or Impacts. These are stored in the **Indicator Bank** entity.
  - **Hazard indicators:** Represent risks before a disaster occurs (e.g., volcanoes, floods, earthquakes, typhoons, conflicts). These are stored in the **Hazard Indicators** entity.

  Each administrative region has its own **Pillar 1, Pillar 2, and Pillar 3 scores**. The overall **shelter severity score** is determined using a structured **decision tree**.  
  Users can customize how pillar scores influence the final shelter severity score. However, the system includes a **default decision tree** defined by the **Global Shelter Cluster**, which can be modified based on specific needs.

- **[:fontawesome-solid-money-bill-transfer: Data (Pillars, Vulnerabilities, Hazards, and Impacts)](./data/page1.md)**  
  This section serves as the primary data input area and foundation for all calculations. It is divided into six categories:  
  - **Pillar 1** – The Shelter  
  - **Pillar 2** – Inside the Shelter  
  - **Pillar 3** – Outside the Shelter  
  - **Baseline Vulnerabilities**  
  - **Hazards**  
  - **Impacts**  
  Each row corresponds to an administrative region, ranging from **ADM1 to ADM3**.

- **[:material-book-edit: Visualizations](./visualizations/page1.md)**  
  The primary output of the tool is the visualizations displayed on the homepage. These can always be accessed by clicking **'Global Shelter Cluster'** in the top left corner of the page.  
  This section explains how to:
  - Interpret visualizations  
  - Export data for further analysis and calculations  

- **[:material-account-multiple-plus: Customization and Administration](./customization/page1.md)**  
  This section is primarily intended for administrators, but anyone seeking a deeper understanding of the system is welcome to explore it.  
  It covers:  
  - How the system processes data using **formulas, flowcharts, and reports**  
  - How to customize and further develop the tool (only recommended for those familiar with **EspoCRM**)  
  - User management tasks, including **adding and removing users** and **resetting passwords**  

</div>
<!-- markdownlint-enable -->


---

Need further assistance? Contact your dedicated EspoCRM Specialist
or reach out to support@510.global

---
