
🔍Youth Crime Patterns in Victoria — Interactive Dashboard

Overview:
An interactive 10-slide storyboard dashboard analysing a decade of youth crime data in Victoria, Australia (2015–2024). Built using R and flexdashboard, this project explores how youth offending patterns have shifted over time across age groups, gender, and crime types — including the impact of COVID-19.

Key Questions Explored:
1. How have youth offending patterns shifted over 2015–2024?
2. Which age groups are most at risk and when?
3. What types of crimes are young people committing?
4. How do gender and age intersect to create different risk profiles?
5. What was the impact of COVID-19 on youth crime?

Key Findings:
1. Youth crime peaked in 2024 at 65,000+ incidents — the highest in the decade
2. Ages 15–17 consistently show the highest incident rates across all years
3. 2021 saw the decade's lowest point as pandemic restrictions took full effect
4. Property crimes dominate youth offending among 15–17 year olds
5. Males account for approximately 75% of all youth incidents

Tools & Technologies:
1. Language: R
2. Dashboard: flexdashboard (storyboard layout)
3. Visualisation: ggplot2, plotly (interactive charts)
4. Data Processing: tidyverse, dplyr, scales
5. Data Source: Crime Statistics Agency Victoria (2024)

Project Structure
youth-crime-dashboard/
│
├── dashboard.Rmd        # Main dashboard file
├── data/
│   └── youth_crime_2015_2024.xlsx
├── README.md

How to Run
1. Clone the repository
2. Open dashboard.Rmd in RStudio
3. Install required packages:
install.packages(c("flexdashboard", "tidyverse", "ggplot2", "plotly", "scales", "readxl"))
4. Click Knit to render the dashboard

Data Source
Crime Statistics Agency Victoria. (2024). Alleged offender incidents by age and sex, Victoria, 2015–2024 [Data set]. Victorian Government. https://www.crimestatistics.vic.gov.au
