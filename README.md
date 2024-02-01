# ESRI_Going-Places-with-Spatial-Analysis
A course to learn how the special capabilities of spatial data analysis provide deeper understanding using ArcGIS Online.

## Goals ##
- **Understand** why location really matters in a wide range of business and policy decisions.
- **Understand** some of the distinguishing characteristics that make spatial data special.
- **Learn** how to identify and describe uses of several spatial analysis techniques.
- **Gain** hands-on experience with authentic spatial analysis workflows in a cloud-based mapping environment.

## Section 2 ##
Understanding and Comparing Places
Different locations host different physical and cultural features and populations. Locations can be described and summarized with attributes and can be compared to one another. 

**Exercise 1: Understanding and Comparing Places: Mixed-Use Development**

1. Introduction to the Analyst's Role and Company's Goals:
- Position: Market analyst for a local development company.
- Objective: Monitor the market for optimal sites for small mixed-use developments.
- Target demographic: People in their 20s and 30s.

2. Context of City Selection:
- Preference for a city with a large amount of land already zoned for mixed-use development.
- Belief that a larger rental market offers more potential for interested clients.

3. Spatial Analysis Question:
- How much area is zoned for mixed-use development?
- Where are high rental areas?
- Where do high numbers of people between the ages of 22-39 live in high rental areas?

4. Information Needed for Analysis:
- Area zoned for mixed-use development. (Dataset provided by ESRI)
- Location of high rental areas. (Dataset provided by ESRI)
- Geographic distribution of people aged 22-39 in high rental areas. (Dataset provided by ESRI)
  
5. Exercise Steps:
   
**Data Exploration and Preparation:**
- Examined attribute tables and statistics.
  - Datasets easy to filter
  ![image](https://github.com/marianahiroki/ESRI_Going-Places-with-Spatial-Analysis/assets/110165879/8e6b9f8f-fe49-470b-be36-0f0d14167d72)
  ![image](https://github.com/marianahiroki/ESRI_Going-Places-with-Spatial-Analysis/assets/110165879/3667a72a-dddd-4bce-9399-83920b9818d6)
- Enriched layer data by adding additional information.
- Added attribute data to create a new field for analysis.
  - Although some calculations are made with SQL, similar to Power BI and Tableau, it is not necessary to write the syntax.
  ![image](https://github.com/marianahiroki/ESRI_Going-Places-with-Spatial-Analysis/assets/110165879/eb5eaee7-f45a-46aa-ab87-55e08a8bcd05)
  - In other cases, some expressions are written with code:
  ![image](https://github.com/marianahiroki/ESRI_Going-Places-with-Spatial-Analysis/assets/110165879/d810b537-aa2b-4407-a867-5828c0bbd710)
  
**Data Analysis and Modeling:**
- Analysed and modelled the data.
- Utilized filters to limit feature display.
- Changed map styles for effective visualization.

**Interpretation of Results:**
- Addressed the spatial question: "Is this city a good place to build a small mixed-use development?"
- Examined a map displaying block groups with high rental units and residents aged 22-39 near mixed-use zones.
  
**Key Findings:**
- Approximately 517 acres are zoned for mixed-use development.
- Block groups with higher-than-average renters are closer to the city centre in Gresham.
- Most individuals aged 22-39 reside in block groups surrounding the city centre.

**Conclusion:**
- The analysis suggests that the city is a suitable location for a small mixed-use development, supported by the correlation between high rental units, the age demographic of residents, and their proximity to mixed-use zones.
<img width="1242" alt="image" src="https://github.com/marianahiroki/ESRI_Going-Places-with-Spatial-Analysis/assets/110165879/b926dce4-0d54-4820-bd5d-0f6d1417e720">




