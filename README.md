# Exploratory Analyses of CT Drug-Related Deaths from 2012-2024

- Data from https://data.ct.gov/Health-and-Human-Services/Accidental-Drug-Related-Deaths-2012-2024/rybz-nyjw/about_data
- Contains data permitting to all deaths deemed accidental and related to drug use
- Over 12,000 individuals' worth of data.
- Please visit this [Jupyter Notebook](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/analyses_notebook.ipynb) for all analyses.
- Otherwise, a summary of findings are shown here. 
  
## Demographics
### Gender
- There are 9571 males
- There are 3380 females
- Mean age of death (males): 44.2833855799373
- Mean age of death (females): 44.55355029585799
  
### Age
- Mean age of death is around 45 years of age.
- There is a range of 13-87 years of age.

![Age Histogram](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/age_histogram_with_mean.png)

### Race
- Majority of deaths are of White individuals, followed by Black/African American.
![Race Pie Chart](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/top2_race_pie_chart.png)

## Death-Related Information
### Number of Deaths Over the Years
- The numnber of deaths per year climbed steadily, peaking in 2021. 
- Since 2021, the number of deaths per year has been decreasing.
  
![Deaths per Year](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/deaths_per_year.png)

### Death Locations
- Most deaths occur at individuals' own residences, followed by medical facilities/hospitals.

![Top 5 Death Locations](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/top5_locations_pie_chart.png)

- Hartford and New Haven Counties show the most deaths overall

![New Haven Counties](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/ct_deaths_map.png)

### Main Substances Associated with Deaths
![Main Substances](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/drug_counts_by_category.png)

- Most drug-related deaths can be attributed to Fentanyl.

### Drug-Related Deaths Across Years

![Drug-Related Deaths Across Years](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/drug_group_trends.png)

- Fentanyl-related deaths begin to overtake other categories in 2017.

### Polysubstance Use vs Single Drug Use

![Polysubstance Deaths](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/single_vs_multiple_drugs.png)

- Most drug related deaths are a resutl of polysubtance use.

### Single Drug-Associated Deaths

![Single Drug Deaths](https://github.com/ellenmartin11/CT-Drug-Deaths/blob/main/single_drug_pie_chart.png)

- Of deaths that are related to the use of just one substance, cocaine accounts for almost half of the amount of deaths.

## Analyses To Come:
- looking at specific drug-use across counties to see if there is a difference
