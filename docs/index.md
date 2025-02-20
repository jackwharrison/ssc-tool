### Shelter Severity Classification Tool


<!-- markdownlint-disable-next-line no-trailing-punctuation -->

Welcome to the Shelter Severity Classification Tool training!
It covers access to the system, explains how the system works, how to add indicators and data to the system, how to interpret the results, and how to export the data. This training covers how to use the system as both a user and an admin. We will go through each entity one by one, so you can better understand how the tool works.

If you are using this training module for self-study, you are advised to follow the navigation list starting with the General chapter. The Customisation part is optional and is intended for experienced EspoCRM administrators willing to develop their entities and flowcharts further. 

**On the left you can find a navigation overview**  

---

<!-- markdownlint-disable -->
<div class="grid cards" markdown>

- **[:material-clock-fast: General](./general/index.md)**  
  This section provides an overview of the current Shelter Severity Classification system developed by the Global Shelter Cluster and its connection to this tool.

- **[:fontawesome-solid-users-gear: Administrative Divisions](./administrative_regions/page1.md)**  
  The tool allows users to navigate between different administrative layers within a country, from Admin Level 0 (ADM0) down to Admin Level 3 (ADM3). These layers can be customized to reflect regional naming conventions.  
  For example, in the Philippines, the administrative levels are called Country (ADM0), Region (ADM1), Province (ADM2), and Municipality (ADM3).

- **[:fontawesome-solid-people-roof: Indicators and Decision Trees](./indicators_and_decision_trees/page1.md)**  
  **The calculation framework is primarily defined by selecting which indicators to use. These indicators fall into two main categories:**  

  - **Non-hazard indicators:** Classified as either pre- or post-disaster and further divided into Pillar 1, Pillar 2, Pillar 3, Vulnerabilities, or Impacts (these terms will be explained in detail later). These are specified in the **Indicator Bank** entity.
  - **Hazard indicators:** Represent the risk of specific hazards before any disaster occurs. Currently, these include risks from volcanoes, floods, earthquakes, typhoons, conflicts, and other hazards. These are specified in the **Hazard Indicators** entity.

  Each administrative region has its own Pillar 1, Pillar 2, and Pillar 3 scores. The overall **shelter severity score** is determined by a combination of these three scores, following a structured **decision tree**. Users can customize how different pillar score combinations influence the final shelter severity score. However, the system includes a default decision tree established by the **Global Shelter Cluster**, though a new decision tree can be created and used based on specific needs. These decision trees are stored in the **Decision Tree** entity.

- **[:fontawesome-solid-money-bill-transfer: Data (Pillars, Vulnerabilities, Hazards, and Impacts)](./data/page1.md)**  
  This section serves as the primary data input area and the foundation for all calculations. It is divided into six categories: Pillar 1 – The Shelter, Pillar 2 – Inside the Shelter, Pillar 3 – Outside the Shelter, Baseline Vulnerabilities, Hazards, and Impacts. Each row within these entities corresponds to a specific administrative region, ranging from ADM1 to ADM3.

- **[:material-book-edit: Visualizations](./visualizations/page1.md)**  
  The primary output of the tool is the visualizations displayed on the homepage, which can always be accessed by clicking 'Global Shelter Cluster' in the top left corner of the page. This section will explain how to interpret these visualizations and export the data for further analysis and calculations.

- **[:material-account-multiple-plus: Customization and Administration](./customization/page1.md)**  
  This section is primarily intended for administrators. However, if you want a deeper understanding of the system, you are welcome to explore it. Here, we explain how the system processes data using formulas, flowcharts, and reports. We will also cover customization options and further developments, though these should only be attempted if you are confident in managing an EspoCRM system.  

  This section also covers user management, including adding and removing users, as well as general administrative tasks like resetting passwords.

</div>
<!-- markdownlint-enable -->


---

Need further assistance? Contact your dedicated EspoCRM Specialist
or reach out to support@510.global

---
