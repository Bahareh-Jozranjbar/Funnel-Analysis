# Funnel Analysis with Advanced UX Insights  

## Overview  
This repository provides a structured approach to **funnel analysis**, focusing on identifying user drop-off points in workflows like onboarding, checkout, and sign-ups. By combining **data visualization, Markov modeling, survival analysis, and segmentation**, this project delivers a deep understanding of user behavior to optimize retention.  

## Key Features  

### 1. Funnel Drop-Off Analysis  
- Visualizes how users progress through key steps and where they abandon the process.  
- Uses real-world-inspired data to simulate realistic drop-off rates.  

### 2. Markov Attribution Model  
- Identifies the most influential touchpoints in the user journey.  
- Creates a transition matrix to understand user movement between steps.  

### 3. Survival Analysis for User Retention  
- Estimates the probability of users remaining in a funnel over time.  
- Helps predict when users are most likely to drop out.  

### 4. Behavioral Segmentation Analysis  
- Compares funnel retention rates across different user groups.  
- Highlights variations in user behavior based on **Premium vs. Free** user segments.  

## Installation  
To run this project locally, ensure you have R and the following libraries installed:  

```r
install.packages(c("ggplot2", "dplyr", "survival", "markovchain", "tidyr", 
                   "survminer", "tibble", "ChannelAttribution", "reshape2", "igraph"))
```

### Usage
Clone the repository and open the R Markdown file to execute the analysis. Each section runs independently and produces visualizations that offer actionable insights into user behavior.

### Visualizations
- Funnel Drop-Off Chart: Displays where users abandon the process.
- Markov Model Graph: Highlights key touchpoints driving user engagement.
- Survival Curve: Shows how long users stay in the funnel before dropping off.
- Segmented Funnel Analysis: Compares behaviors across user segments.
