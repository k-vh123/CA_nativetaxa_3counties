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
- **Terrestrial Irreplaceability:** A weighted measure of endemism, highlighting areas with unique biodiversity.

## Libraries

To run the Jupyter Notebook and perform the analysis, I used Python and had the following libraries installed:

- pandas
- matplotlib

## Analysis Workflow

The analysis follows these steps:

1. **Data Loading:** The dataset is loaded from a CSV file using pandas.
2. **Filtering Columns:** Only the relevant columns (related to native and rare taxa) are selected for analysis.
3. **Summing Taxa:** The total counts for amphibians, reptiles, birds, and mammals are calculated by summing native and rare species counts.
4. **Comparison Across Counties:** The analysis reveals that Humboldt County has the largest number of native amphibian taxa, while San Bernardino County has the highest number of bird, mammal, and amphibian native taxa. These results are compared with data from Los Angeles County, which has the highest human population in California, with over 9 million residents ([source](https://www.census.gov/quickfacts/fact/table/losangelescountycalifornia,US/PST045221)).

## Power BI Dashboard

To visualize and further explore the findings, a dashboard was created in Power BI. The dashboard compares the native taxa counts in Humboldt, San Bernardino, and Los Angeles counties, with specific focus on the following taxa:

- **Birds**
- **Mammals**
- **Reptiles**
- **Amphibians**

### Key Insights:
- **Humboldt County:** High native amphibian taxa counts.
- **San Bernardino County:** High bird, mammal, and amphibian native taxa counts.
- **Los Angeles County:** A moderate number of native taxa counts across all categories, which is significant given its high human population density.

## Sustainability Perspective

This analysis provides important insights into how human population density in urban areas might impact biodiversity. With Los Angeles County having the largest human population in California, this project explores whether an unusually high number of people living in a county affects native taxa numbers. Understanding these dynamics is crucial for sustainability and conservation planning.
