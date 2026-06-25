Youth Crime Patterns in Victoria — Interactive Dashboard

Overview
An interactive 10-slide storyboard dashboard analysing a decade of youth crime data in Victoria, Australia (2015–2024). Built using R and flexdashboard, this project explores how youth offending patterns have shifted over time across age groups, gender, and crime types — including the impact of COVID-19.

Key Questions Explored
How have youth offending patterns shifted over 2015–2024?
Which age groups are most at risk and when?
What types of crimes are young people committing?
How do gender and age intersect to create different risk profiles?
What was the impact of COVID-19 on youth crime?

Key Findings
Youth crime peaked in 2024 at 65,000+ incidents — the highest in the decade
Ages 15–17 consistently show the highest incident rates across all years
2021 saw the decade's lowest point as pandemic restrictions took full effect
Property crimes dominate youth offending among 15–17 year olds
Males account for approximately 75% of all youth incidents

Tools & Technologies

Language: R
Dashboard: flexdashboard (storyboard layout)
Visualisation: ggplot2, plotly (interactive charts)
Data Processing: tidyverse, dplyr, scales
Data Source: Crime Statistics Agency Victoria (2024)

How to Run
1. Clone the repository
2. Open dashboard.Rmd in RStudio
3. Install required packages:
install.packages(c("flexdashboard", "tidyverse", "ggplot2", "plotly", "scales", "readxl"))
4. Click Knit to render the dashboard

Data Source
Crime Statistics Agency Victoria. (2024). Alleged offender incidents by age and sex, Victoria, 2015–2024 [Data set]. Victorian Government. https://www.crimestatistics.vic.gov.au
