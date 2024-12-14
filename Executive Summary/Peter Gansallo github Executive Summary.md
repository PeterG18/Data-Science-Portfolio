## **Prevalence of asthma and Chronic Obstructive Pulmonary Disease (COPD)**

**Exploring the Relationship between COPD, Asthma, Race, and Location**

#### 

#### **Introduction**

Asthma and Chronic Obstructive Pulmonary Disease (COPD) are significant public health concerns in the United States. Both conditions impact millions of individuals, leading to reduced quality of life and increased healthcare costs. This study explores the prevalence of asthma and COPD by state and investigates how racial and ethnic disparities influence prevalence rates. By identifying trends and disparities, the study aims to inform targeted public health interventions and policy changes. According to the CDC, chronic lower respiratory diseases, primarily COPD, are the third leading cause of death in the United States.

#### **Purpose**

The purpose of this research is to investigate these questions:

* Does the prevalence of asthma and COPD vary by state in the United States?  
* How do racial and ethnic demographics influence the prevalence of these conditions?

The analysis examines geographic and demographic trends in the prevalence of asthma and COPD, offering actionable insights for healthcare stakeholders to reduce disparities and improve health outcomes.

#### 

#### **Methodology**

This study uses the publicly available Chronic Disease Indicators dataset from the CDC. This was my methodology

* **Examined the dataset**:  
  * Just looked through the dataset  
  * Used multiple unique() lines to see the different values in different columns  
  * After Inspection, decided on which columns I’d like to keep  
* **Exploratory Data Analysis and Cleaning**:  
  * Filtered to only keep data if the condition were COPD or asthma  
  * Removed unnecessary columns and rows with missing values.  
  * Split into two dataframes one containing only asthma condition and one only COPD  
  * A lot of data was missing in asthma and COPD, 50% of the  datavalue column was missing for Asthma and 30% for COPD, so I filled those values with mean of the dataset  
  * Examined the prevalence of asthma and COPD by state.  
  * Analyzed prevalence by race/ethnicity, focusing on three groups: Hispanic, Black (non-Hispanic), and White (non-Hispanic).  
* **Statistical Analysis**:  
  * Conducted an ANOVA test to evaluate significant differences in COPD prevalence by race/ethnicity.

* **Visualization**:  
  * Generated bar plots to compare the mean prevalence of asthma and COPD by race/ethnicity.  
  * Created state-wise visualizations to highlight geographic variations.

#### **Analysis**

Key findings from the study include:

* **Geographic Trends**:  
  * COPD and asthma prevalence appeared to correlate more strongly with states that have larger populations rather than distinct geographic patterns. Which lead to a later focus on race, the morbidity and mortality report also suggested Information on state specific prevalence of COPD is sparse  
* **Racial Disparities**:  
  * Black (non-Hispanic) populations exhibited higher prevalence rates for both asthma and COPD compared to White and Hispanic populations. This aligns with findings from previous studies indicating that certain occupational and socioeconomic factors may contribute to these disparities.  
  * Industries and occupations with high exposure to vapors, gases, dust, or fumes—such as agriculture, food preparation, and manufacturing—are associated with increased asthma-COPD overlap, especially among marginalized groups. For example, men in beverage manufacturing showed a PMR of 3.15, while women in food preparation occupations exhibited high exposure rates to secondhand smoke.  
  * A Morbidity and Mortality Weekly Report (2012) highlights that individuals with less than a high school education are more likely to report COPD (11.1%) compared to those with some college education (4.2%).

#### **Recommendations**

Based on the findings, the following actions are recommended:

1. **Targeted Public Health Campaigns**:  
   * Focus on policies that address occupational risks in industries with high exposure to environmental hazards, such as beverage manufacturing and food preparation.  
   * Develop programs to improve smoking cessation rates, as smoking remains the leading cause of COPD, accounting for 75% of related deaths in the U.S.  
2. **Address Racial Disparities**:  
   * Implement community-specific interventions for Black (non-Hispanic) populations, including education on risk factors and improved access to affordable healthcare.  
3. **Improve Data Collection**:  
   * Enhance data collection to capture more granular insights into occupational and environmental risk factors, enabling more precise targeting of public health interventions.

#### **Implementation**

To implement these recommendations effectively, a time of 6-12 months is proposed to design and deploy public health campaigns. Collaboration with state health departments and local healthcare providers is essential to ensure the success of these initiatives. Budget allocations should prioritize education programs, screening initiatives, and treatment subsidies. Along with policies that could make working conditions better for such workers at risk due to their occupation

#### **Conclusion**

This study highlights significant racial and occupational disparities in the prevalence of asthma and COPD. By addressing these disparities through targeted public health interventions and improved data collection, healthcare stakeholders can reduce the burden of these chronic conditions and improve outcomes for affected populations. A 2012 CDC report, says individuals with COPD face barriers to healthcare access, with 34% reporting cost as a significant obstacle. Addressing these challenges is crucial to achieving health equity. Continued research and data monitoring are essential to ensure the effectiveness of these interventions.

**References**

Chronic Obstructive Pulmonary Disease and Associated Health-Care Resource Use — North Carolina, 2007 and 2009\. (2012). *Morbidity and Mortality Weekly Report*, *61*(8), 143–146. http://www.jstor.org/stable/23320655

Dodd, K. E., Wood, J., & Mazurek, J. M. (2020). Mortality Among Persons with Both Asthma and Chronic Obstructive Pulmonary Disease Aged ≥25 Years, by Industry and Occupation — United States, 1999–2016. *Morbidity and Mortality Weekly Report*, *69*(22), 670–679. https://www.jstor.org/stable/26967494

