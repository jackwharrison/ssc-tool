# Administrative Regions:

The SSC tool calculates scores for each administrative region, dependent on the availability of data. At present, the tool supports four levels of administrative regions, from ADM0 to ADM3. 

ADM0 is always the country, but the names of the lower administrative regions will vary depending on the country. Using the example of the Philippines, the data would be structured as such:

-ADM0 (Country)

--ADM1 (Region)
  
---ADM2 (Province)
    
----ADM3 (Municipality)

## Administrative regions within the tool

Each level of administrative region is represented by a different entity within the tool. ADM1, ADM2 and ADM3 follow a very similar structure, whilst ADM0 (Country level) is structured slightly differently, which will be explained later.

## ADM1 to ADM3

These are all very similar, bar a few minor differences, for this page, we will look through the ADM3 entity.

### Overview:

![image](https://github.com/user-attachments/assets/3241b3ee-9b25-4677-87fc-24f7502b5428)

- **ADM3:** the name of the administrative region. For lower admin levels it is recommended to combine the name of the region with the PCODE, as there may be multiple regions with the same name.
- **ADM2:** the name of the ADM2 region this region falls into
- **ADM1:** the name of the ADM1 region this region falls into
- **Country:** country of this region
- **PCODE:** Unique identifier associated with each administrative region to ensure correct matching of regions
- **Population:** Population within this administrative region
- **Adjusted Severity Score:** Overall shelter vulnerability score calculation via the decision tree method adjusted for baseline vulnerability
- **Shelter Vulnerability Score:** Overall shelter vulnerability score calculation via the decision tree method
- **Refresh:** Click this button to refresh the calculations. (Press small blue pencil to the right to unlock it). It will reset to unclicked when the calculations are complete. Make sure to refresh the page to see any changes.
