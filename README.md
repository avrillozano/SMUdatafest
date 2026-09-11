# ASA DataFest 2026: Hospital Patient Journey & Engagement Issues

This repository contains the exploratory data analysis, statistical modeling, and visual pipelines developed for the 2026 ASA DataFest Hackathon at SMU. 
The project evaluates a large-scale healthcare dataset to understand patient journeys from initial diagnosis to treatment, with a specific focus on MyChart app activation rates, demographic disparities, and follow-up appointment compliance.

## Project Overview

Healthcare outcome metrics and portal usage vary significantly across patient demographics. Using R and tidyverse tools, this analysis explores:
-Mental health identification: Flagging diagnostic patterns to identify patient groups with mental health diagnoses.
-Portal activation disparities: Finding MyChart portal inactivation rates across reported racial groups and diagnostic categories.
-Follow-up compliance: Performing chi-square independence testing to evaluate how digital portal activation impacts follow-up appointment completion.
-Healthcare utilization: Quantifying differences in total encounter counts between patient groups.

## Data & Repository Notes
The dataset used for this project is proprietary and subject to regulations, therefore, data files are excluded from this repository.
This repository contains preliminary statistical exploratory code and draft visualizations alongside the core scripts used for the final presentation.

## Packages used

This code uses the following packages:
```r
library(tidyverse)
library(webshot2)
library(kableExtra)
```
