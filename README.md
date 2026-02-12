# FitBit Case Study: The Sleep-Activity Trade-Off (Pre-COVID Baseline)

## About This Project 

This case study analyzes FitBit fitness tracker data from April-May 2016 to uncover the relationship between sleep duration and physical activity in active women. Completed as part of my Google Data Analytics Certificate, this work demonstrates the type of user behavior analysis I'm passionate about pursuing professionally in the fitness technology space.

**What makes this analysis unique:** The data predates COVID-19 by nearly four years, providing a valuable pre-pandemic baseline for understanding how global disruptions reshape health behaviors—exactly the type of longitudinal research that companies like Garmin, Fitbit, Apple, Whoop, Amazfit, and Nike need to inform product strategy.

## Why This Matters

As a half marathon runner and cyclist, I understand firsthand the challenge of balancing training with adequate sleep. This analysis reveals that I'm not alone—active women consistently sacrifice sleep for movement, creating an unsustainable wellness pattern. 

The implications for fitness technology are clear: devices that celebrate maximum activity without promoting sleep balance may inadvertently encourage burnout. This presents a strategic opportunity for companies positioning themselves as holistic wellness partners rather than pure achievement trackers.

## Key Insights

1. **The Sleep-Activity Trade-Off:** Negative correlation between sleep duration and daily steps (r = -0.19, p < 0.001)
2. **Magnitude Matters:** Users sleeping <6 hours take ~50% more steps than those sleeping 8+ hours
3. **Validated Findings:** FitBit sample is representative of US women (confirmed via NHANES comparison)
4. **Pre-COVID Baseline:** Data from 2016 provides foundation for comparative analysis with post-pandemic behavior
5. **Strategic Opportunity:** Market positioning around "balance and sustainability" vs. "maximum achievement"

## Methodology

**Data Sources:**
- FitBit Daily Activity (n=33, 940 observations)
- FitBit Sleep Data (n=24, 413 observations)  
- NHANES 2009-2011 (n=5,020 US women, validation)

**Analytical Approach:**
1. Data cleaning and quality checks (duplicate detection/removal)
2. Exploratory data analysis and visualization
3. Dataset integration (merging sleep + activity data)
4. Correlation analysis with statistical testing
5. External validation against national health data
6. Translation of findings into strategic recommendations

**Tools Used:**
- R (tidyverse, ggplot2, dplyr)
- R Markdown for reproducible analysis
- NHANES national health data for validation

## Repository Contents

### Main Documents
- **[FitBit_Case_Study.md](FitBit_Case_Study.md)** - Complete analysis and findings
- **[FitBit Case Study Steps.Rmd](FitBit Case Study Steps.Rmd)** - R Markdown source with executable code
- **[FitBit_Case_Study.pdf](FitBit_Case_Study.pdf)** - PDF version for easy viewing

### Data & Outputs
- `raw_data/` - Original FitBit and NHANES datasets
- `*.png` - Visualization outputs from analysis

## Future Research Directions

**Priority Question:** How did COVID-19 alter the sleep-activity trade-off identified in this 2016 baseline?

The pandemic fundamentally changed how we work, exercise, and sleep. Comparing this pre-COVID data against 2020-2024 datasets would reveal:
- Which user segments thrived vs. struggled during disruption
- Whether remote work improved or worsened sleep-activity balance  
- What lasting behavioral changes should inform product development
- How to design crisis-resilient wellness technology

This is exactly the type of longitudinal behavior-change analysis I'm eager to pursue professionally.

## Project Status

✅ Core analysis complete  
🔄 Currently enhancing visualizations and formatting  
📅 Final version: February 2026

Check back for updates as I continue refining the presentation!

## Strategic Recommendations for Bellabeat

Based on this analysis, I recommend Bellabeat:

1. **Position as the "anti-burnout" wellness partner** - differentiate from competitors celebrating maximum activity
2. **Develop sleep-activity balance alerts** - notify users when high activity coincides with poor sleep
3. **Create "sustainable wellness" messaging** - emphasize that adequate sleep enables better performance
4. **Target the "ambitious but exhausted" segment** - active women who need help finding balance

## Let's Connect

**Interested in discussing:**
- Fitness technology data analytics
- Pre/post-COVID behavior change analysis  
- Longitudinal user behavior research
- Career opportunities in wellness tech

**Reach out:**
- 💼 LinkedIn: [Lea Harvin](https://www.linkedin.com/in/lea-harvin-1a3817a7/)
- 📧 Email: LNHarvin@gmail.com

I'm particularly interested in opportunities with companies analyzing multi-year user behavior data to inform product development and marketing strategy. Whether you're at Garmin, Nike, Apple, Whoop, Runkeeper, or a startup in the wellness space—if you're working on similar analyses, I'd love to connect.

---

**Author:** Lea N. Harvin | February 2026  
**Capstone Project:** Google Data Analytics Certificate  
**Data Source:** FitBit Fitness Tracker Data (Kaggle) | NHANES 2009-2011
