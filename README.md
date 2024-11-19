## Potential State-level Predictors of Parkinson's Disease Mortality Rates
### Final Project for QBS181 Data Wrangling
### Savannah Gonzales, Yifei Gao, Amy Wang, Kath Paul 

**Aim 1: Assess the impact of neurologist workforce measures on Parkinson’s Disease mortality rates.** \
1.1 Calculate state-level neurologist supply and examine the association with PD mortality rates. \
1.2 Quantify Medicare-accepting neurologist availability and determine the extent to which it affects PD mortality rates.

**Aim 2: Explore agricultural variables and their influence on Parkinson’s Disease mortality rates.** \
2.1 Investigate the relationship between PD mortality rates and total agricultural chemical expenditure per state. \
2.2 Evaluate the association between the amount of acreage treated with three types of pesticides and PD mortality rates.

### Repository Files

**QBS181\_ProjectAim1.pdf**  
Format: PDF (knitted from R Markdown, .rmd file also provided)  
Purpose:

* Merges the following data:  
  * National Plan and Provider Enumeration System (NPPES)  
  * Center for Medicare & Medicaid Services (CMS) Physician Compare National  
  * Parkinson’s disease mortality rates  
  * US adult population data  
  * Medicare monthly enrollment file (for Medicare beneficiary population data)  
  * Social Deprivation Index (SDI)  
  * Rural-Urban Continuum Codes (RUCA) codes  
* Conduct data analysis for Aim 1 of the project.

Output:

* Statistical testing results (correlation plot)  
* Maps displaying metrics pertaining to Aim 1
   
**QBS181\_ProjectAim2.pdf**  
Format: PDF (knitted from R Markdown, .rmd file also provided)  
Purpose:

* To merge the pre-processed 2022 USDA data with the CDC mortality rate data frame.  
* Conduct data analysis for Aim 2 of the project.

Output:

* A series of visualizations (plots) and summary tables.  
* Statistical testing results.  
* Regression models.

**Ag\_Data\_Clean\_Final.xlsx**  
Format: Excel  
Purpose:

* To clean, preprocess, and perform calculations on the 2022 USDA raw data.  
* Organize the data into a final, cleaned sheet with all relevant variables for further analysis.  
* Prepare the data for merging with CDC mortality rate data.

Output:

* A series of exploratory data analysis plots and maps.  
* A cleaned data sheet, ready for merging with the CDC mortality rate data frame.

