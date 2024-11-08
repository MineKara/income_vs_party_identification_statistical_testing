
# Does Annual Household Income Play a Role in Minority’s Political Party Identification?

This repository analyzes the relationship between annual household income and political party identification among ethnic minority groups in the UK. Using data from the British Election Study (BES) 2010, we examine how income levels influence political preferences within five ethnic groups: Indian, Pakistani, Bangladeshi, Black Caribbean, and Black African.

## Overview

This study explores whether income impacts political affiliation among ethnic minorities in the UK. This information can be valuable for political campaigners, sociologists, and policymakers interested in understanding the socioeconomic factors influencing political behavior within minority communities.

## Data

The analysis is based on the BES 2010 survey data, focusing on:

- **Dependent Variable**: Annual Household Income (`zqinc`, ordinal)
- **Independent Variable**: Party Identification (`bq9_1`, nominal)

The survey includes responses from 2,787 adults from England, Scotland, and Wales, filtered down to 1,543 records relevant to the research question.

## Research Question

**Does annual household income play a role in minority political party identification?**

## Methodology

The study used statistical filtering and non-parametric tests to analyze the relationship between income and party preference. Key transformations included filtering responses for targeted ethnicities and removing records lacking transparency in income or party identification.

1. **Data Filtering**: Filtered for relevant ethnic minorities and excluded records without clear political or income responses.
2. **Assumptions and Analysis**: Conducted a Kruskal-Wallis Test, testing for income distribution consistency across party identification categories.
3. **Hypotheses**:
   - **Null Hypothesis**: Income distribution is consistent across party identification.
   - **Alternative Hypothesis**: Income distribution differs across party preferences.

## Findings

The analysis revealed a significant relationship between income and political identification, with notable distinctions among party preferences:

- Higher-income individuals tended to support the Conservative Party.
- Lower-income individuals leaned towards Labour or had no specific party preference.
  
These findings suggest income as a key factor in political identification for UK ethnic minorities.

## Conclusion

Income levels within minority communities appear to influence political affiliations, similar to trends observed in the general population. Political parties can leverage these insights to better tailor campaign messages to different income groups within minority populations.

## Repository Structure

- `/data`: Contains the BES 2010 dataset in `.dta` format.
- `/analysis`: Scripts for data preprocessing, filtering, and statistical tests.
- `/results`: Visualizations and statistical outputs of the analysis.
- `/docs`: Report detailing methodology, analysis, and findings.

## Requirements

- **Language**: Python or R for statistical analysis.
- **Libraries**: `pandas`, `numpy`, `scipy`, and `matplotlib`.

## Usage

1. Clone the repository.
2. Run the scripts in the `/analysis` directory to replicate the study.
3. Check `/results` for visualizations and summary statistics.

## License

This project is licensed under the MIT License.
