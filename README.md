# Stat-184-Project

Home Advantage in the Premier League
An exploratory data analysis of home advantage in the English Premier League across five seasons (2019/20 -- 2023/24), with a particular focus on whether home advantage was disrupted during the COVID-19 pandemic when matches were played without fans.
Authors

Arnav Patel
Nivaan Garg
Jesunifemi Ijaware

This is a final project for STAT 184 at Penn State University.
Research Question
Does home advantage exist in the Premier League, and did it change during the COVID-19 no-fans season of 2020/21?
Key Findings

Home teams won 43--48% of matches in four of the five seasons studied -- a consistent advantage over away teams.
In the 2020/21 COVID season (played without fans), home wins dropped to 37.9% and away wins climbed to 40.3%, the largest single-season shift in the dataset.
Across all seasons, away teams received more yellow cards and committed more fouls than home teams, but this gap narrowed in 2020/21 -- consistent with the hypothesis that crowd presence influences referee decisions.

Data Source
Match-level statistics were sourced from football-data.co.uk, a publicly available repository of football match results compiled from official league sources. The data were not obtained from Kaggle and have not been used in any prior STAT 184 assignment.
The dataset contains 1,900 matches (380 matches per season across five seasons). Each row represents a single Premier League match and includes the season, home and away teams, full-time result, goals, shots, yellow cards, and fouls for both sides.
How to Reproduce
To reproduce this analysis on your own machine:

Clone the repository to your local computer.
Open the project in RStudio.
Make sure you have the following R packages installed: tidyverse, janitor, and knitr. You can install any missing packages by running:

r   install.packages(c("tidyverse", "janitor", "knitr"))

Open the .qmd file and click Render in the RStudio toolbar. The rendered PDF will appear in the same folder.

Software
This analysis was conducted in R using a Tidyverse-based workflow. All visualizations were created with ggplot2, and the report was written and rendered using Quarto.
License and Use
The source data are publicly available for educational and non-commercial use. This report and the code in this repository may be used freely for educational purposes.
