---
title: "What is the relationship between race and the likelihood of getting stopped under stop-and-search laws in London?" 
date: 2023-04-01
#lastmod: 2024-05-08
#tags: ["Portugese","irregular verbs","philology"]
author: ["Aniket Kapadia, Hannah Ismael, Lydia Sidhom, Sarah Zhang"]
#description: "This book discusses Portugese irregular verbs in great details."
summary: "Legalst 123 project"
cover:
    image: "london_race.jpeg"
    alt: "What is the relationship between race and the likelihood of getting stopped under stop-and-search laws in London?"
    relative: false
editPost:
    #URL: "https://github.com/pmichaillat/hugo-website"
    #Text: "Regensburg University Press"
showToc: false
disableAnchoredHeadings: false

---

---

#### Description

This project explores the relationship between race and the likelihood of being stopped under stop-and-search laws in London. While racial disparities in policing have been extensively studied in the U.S., similar patterns in the U.K. remain underexplored. Our objective was to analyze how the racial makeup and police density in different London boroughs influence stop-and-search practices. Using data from the London Metropolitan Police and census reports, we applied computational techniques to investigate whether specific racial groups are disproportionately targeted and how these patterns vary across boroughs with different demographic compositions.


---

#### Some Questions We Explored:

- What is the relationship between race and the likelihood of being stopped under stop-and-search laws in London?

- How does police density in different boroughs influence the frequency of stop-and-searches across racial groups?

- Do boroughs with varying racial compositions show significant differences in stop-and-search patterns?

---

#### Methodology:

We combined stop-and-search data with census demographics and police workforce statistics from 2022. Officer-defined racial categories—White, Black, Asian, and Other—were used to align our analysis with how police perceive race. Using Python, we cleaned and merged datasets, calculated police density by dividing the number of officers by borough population, and created proportional racial breakdowns for each borough. We used Ordinary Least Squares, Ridge Regression, and LASSO to model the relationship between racial demographics, police density, and stop-and-search frequencies. Each model was trained separately on racial groups, allowing us to evaluate whether the predictors systematically affected certain groups more than others.

---

#### Conclusion:

Our models revealed varying relationships between race, police density, and stop-and-search frequency. For Asian and Black populations, increased police density generally correlated with fewer stop-and-searches, while higher population proportions of these groups led to more frequent stops. The LASSO model indicated stronger relationships for Asian populations, suggesting potential biases. However, the limited dataset (32 boroughs) posed challenges, with high model errors suggesting other unmeasured variables like socioeconomic status or officer discretion may play a role. While our findings suggest possible racial profiling, more granular data is needed to draw definitive conclusions.
