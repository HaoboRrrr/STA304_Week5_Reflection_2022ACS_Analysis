# Analysis of 2022 USA Census: Focus on Doctoral Degree Holders

This project analyzes the 2022 USA Census data, focusing on the actual number of respondents with a doctoral degree in each state compared to estimated values.

## Table of Contents
- [Overview](#overview)
- [Data Source](#data-source)
- [Methodology](#methodology)
- [Findings](#findings)
- [Authors](#authors)
- [References](#references)

## Overview
This analysis examines:
- The number of respondents with a doctoral degree as their highest educational attainment, categorized by state.
- The estimated number of respondents compared to actual values, using ratios derived from California's data.

The study explores differences between estimated and actual values, highlighting potential biases in the estimation approach.

## Data Source
The data was sourced from [IPUMS USA](https://usa.ipums.org/usa/index.shtml). 
To replicate the data extraction:
1. Select the **2022 ACS** sample.
2. Include the variables:
   - **STATEICP** (State code)
   - **Sex**
   - **EDUC** (Educational attainment)
3. Submit and download the extract after configuration.

For more details, see the data preparation section in the analysis document.

## Methodology
- The ratio of doctoral degree holders in California to its population was applied to all states to estimate their values.
- Variations between estimated and actual values were analyzed, accounting for factors like population size, state-specific educational trends, and the presence of universities.

## Findings
- There is variability between estimated and actual numbers due to differences in state demographics, educational infrastructure, and professional composition.
- The use of California's ratio for other states introduces inaccuracies, especially for states with unique characteristics.

Key tables and figures are included in the project files.

## Authors
- Chendong Fei
- Robert Ford
- Rui Hu
- Haobo Ren
- Xinze Wu
- Xinrui Xie
