# Native Taxa Biodiversity Analysis

This repository contains a data analysis project focused on the biodiversity of native taxa across various counties in California. The analysis includes a comparison of native amphibians, reptiles, birds, and mammals in Humboldt County, San Bernardino County, and Los Angeles County, with a focus on understanding how human population density might affect biodiversity.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Libraries](#libraries)
- [Analysis Workflow](#analysis-workflow)
- [Power BI Dashboard](#power-bi-dashboard)
- [Sustainability Perspective](#sustainability-perspective)

## Introduction

The primary goal of this project is to analyze the biodiversity of native taxa, including amphibians, reptiles, birds, and mammals, across selected counties in California. Specifically, the project compares the biodiversity in Humboldt County, San Bernardino County, and Los Angeles County to explore whether human population density affects biodiversity. This analysis is crucial from a sustainability perspective, as it may reveal the impact of urbanization on native species.

## Dataset

The dataset used in this analysis is the [Statewide Terrestrial Biodiversity Summary - ACE (ds1331)](https://data.cnra.ca.gov/dataset/statewide-terrestrial-biodiversity-summary-ace-ds1331), which provides comprehensive data on terrestrial species biodiversity in California, including amphibians, birds, mammals, plants, and reptiles.

### Key Components:
- **Terrestrial Native Species Richness:** Represents the overall diversity of native species.
- **Terrestrial Rare Species Richness:** Focuses on the diversity of rare species.

## Libraries

To run the Jupyter Notebook and perform the analysis, I used Python and had the following libraries installed:

- pandas
- matplotlib

## Analysis Workflow

The Jupyter Notebook can be found [here](https://github.com/k-vh123/CA_nativetaxa_3counties/blob/main/nativetaxa3_final.ipynb).
The analysis follows these steps:

1. **Data Loading:** The dataset is loaded from a CSV file using pandas.
   
   <img width="578" alt="workflow1" src="https://github.com/user-attachments/assets/77872a85-5382-4826-a486-776483a9ebd7">
   
2. **Filtering Columns:** Only the relevant columns (related to native and rare taxa) are selected for analysis.

   <img width="631" alt="workflow2" src="https://github.com/user-attachments/assets/562e30b4-ff2c-4b5a-b9d3-9781bd8f1f98">

3. **Summing Taxa:** The total counts for amphibians, reptiles, birds, and mammals are calculated by summing native and rare species counts. To further narrow the data, the native counts are then exclusivey summed to determine if the resulting "Top 10" county rankings differ from those of the total counts'. The native taxa alone become the focal point for the remainder of the analysis and visualization process.

    <img width="405" alt="workflow3" src="https://github.com/user-attachments/assets/3b6a7cbe-5aac-4a11-8cab-a4a71fb64c8d">
    <br /> <br />
    <img width="544" alt="workflow4" src="https://github.com/user-attachments/assets/0d16aaa4-1cc4-43c3-bafa-1671867b18d0">
    <br /> <br />
    <img width="519" alt="workflow5" src="https://github.com/user-attachments/assets/6a174897-72da-4250-b116-b95d5c7af1fb">

4. **Initial Visualization and Comparison Across Counties:** The analysis reveals that Humboldt County has the largest number of native amphibian taxa, while San Bernardino County has the largest number of reptile, bird, and mammal native taxa. Los Angeles County's "Top 10" ranking (or lack thereof) in each visualization is also noted, as it has the highest human population in California, with over 9 million residents ([source](https://www.census.gov/quickfacts/fact/table/losangelescountycalifornia,US/PST045221)).
<br /> <br />
    ![w1](https://github.com/user-attachments/assets/cd503fef-d75f-4562-b082-fe7483ecca25)
<br /> <br />  
    ![w2](https://github.com/user-attachments/assets/0b86e4d0-f456-46e1-9272-fcc337d61719)
<br /> <br />
    ![w3](https://github.com/user-attachments/assets/3c649eb9-fe0e-4287-9306-dba7a8f7fb98)
<br /> <br />
    ![w4](https://github.com/user-attachments/assets/7c39e994-4fed-477e-aaf5-c9ae3fce86be)

## Power BI Dashboard

To visualize and further explore the findings, a dashboard was created in Power BI, which can be found [here](https://github.com/k-vh123/CA_nativetaxa_3counties/blob/main/nativetaxa3_powerbi.PNG). The dashboard compares the native taxa counts of four categories in Humboldt, San Bernardino, and Los Angeles counties:

- **Birds**
- **Mammals**
- **Reptiles**
- **Amphibians**
<br /> <br />
   <img width="615" alt="dashboard1" src="https://github.com/user-attachments/assets/d790a7ac-9340-4f9c-ac34-69fcb9a7ce41">
<br /> <br />
### Key Insights and Total Native Taxa Categories Broken Down by Percentage:

Birds were the greatest percentage of total native taxa in each county, followed by mammals, reptiles, and amphibians, respectively.

- **Humboldt County:** Highest native amphibian taxa counts, making up 5.56% of total native taxa in the county.
<br /> <br />
  <img width="360" alt="dashboard4" src="https://github.com/user-attachments/assets/ecde820f-40c4-4576-a17b-f1161648915e">
<br /> <br />
- **San Bernardino County:** Highest bird, mammal, and reptile native taxa counts, making up 47.43%, 28.85%, and 22.46% of total native taxa in the county, respectively.
<br /> <br />
   <img width="373" alt="dashboard2" src="https://github.com/user-attachments/assets/7963da21-ead5-492c-ac4a-73a0a137574e">
<br /> <br />
- **Los Angeles County:** Moderate number of native taxa counts across all categories with the same highest-to-lowest category percentage sequence as Humboldt County and San Bernardino County, which is significant given Los Angeles County's high human population density.
<br /> <br />
  <img width="387" alt="dashboard3" src="https://github.com/user-attachments/assets/d04e7d68-64a7-4152-b5bc-4c9ca4c60324">
<br /> <br />

## Sustainability Perspective

This analysis provides important insights into how human population density in urban areas might impact biodiversity. With Los Angeles County having the largest human population in California, this project explores whether an unusually high number of people living in a county affects native taxa numbers. Understanding these dynamics is crucial for sustainability and conservation planning.
