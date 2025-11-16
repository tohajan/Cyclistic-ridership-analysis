# Cyclistic Bike-Share Usage Analysis
## Comparative Behavioral Analysis of Annual Members vs. Casual Riders

Author: Toheeb M. • Tools: R, Tidyverse, ggplot2, R Markdown

---

### Repository Structure
├── README.md       # Project overview + documentation  
├── Cyclistic company analytics.md # Main notebook  
├── Cyclistic company analytics.Rmd # R-markdown version of main notebook  
├── Cyclistic-company-analytics_files/figure-gfm   # Auto-generated visualizations - plots and graphs  
├── data/       # Raw Cyclistic data files  
└── average_ride_length.csv        # Exported output (for further analysis)

---

### Overview
This project examines how annual members and casual riders use Cyclistic’s bike-share service 
differently. The goal is to generate insights that support targeted marketing strategies to 
increase annual memberships—a major strategic priority for Cyclistic.

Using Q1 2019 and Q1 2020 Divvy/Cyclistic trip data, this analysis:
- Cleans and harmonizes datasets across years
- Engineers time-based and duration features
- Compares usage patterns across rider types
- Visualizes temporal and behavioral trends
- Provides data-driven recommendations for membership growth

The project is fully reproducible via the included R Markdown script.

---

### Skills Demonstrated
- Data Wrangling: tidyverse
- Feature Engineering: date-time extraction, ride duration
- Exploratory Data Analysis (EDA)
- Data Visualization: ggplot2
- Business Communication: insights → recommendations
- Reproducible Workflow: R Markdown

---

### Key Findings
**1. Members ride more frequently**  
Weekday usage dominates, consistent with commuting patterns.

**2. Casual riders take longer rides**  
Across all days—especially weekends—casual riders take significantly longer trips, which may 
indicate recreational usage.

**3. Distinct weekday vs. weekend behavior**
* Members → weekday-heavy
* Casual riders → weekend-heavy


**Insight**  
Longer trip durations among casual riders suggest opportunities to highlight cost savings and 
convenience associated with membership.

---

### Recommendations
1. Develop a recreation-focused membership tier
Target high-duration casual riders who bike primarily on weekends.
2. Segment marketing campaigns
  * Weekday messaging → encourage commuters
  * Weekend messaging → target tourists & leisure riders
3. Improve cost-savings transparency  
  Demonstrate when frequent or long rides make membership cheaper.
  
---

### Visualization Examples
* Number of rides by user type & weekday
* Average ride duration by user type & weekday
* Distribution of ride length

All plots generated using ggplot2.

---

### Exported Output
A summary CSV (for Tableau or downstream analysis):
  `average_ride_length.csv`
  
---

### Conclusion
This project provides a reproducible, business-oriented analysis demonstrating the full pipeline 
of:  
**data ingestion** → **cleaning** → **engineering** → **analysis** → **visualization** 
→ **strategy.**  
It highlights strong analytical reasoning, communication skills, and applied technical ability.