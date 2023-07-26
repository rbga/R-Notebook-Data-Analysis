# Hate Crimes as Recorded and Analyzed by the FBI, USA

## Introduction

This project proposal aims to analyze and annotate the research done by the FBI on their analysis of Hate Crime statistics across the United States of America for the year 2020. The data was published on the FBI public database on August 30th, 2021. The motive of this research is to capture information about the types of bias that motivate crimes, the nature of the offenses, and some information about the victims and offenders.

The Hate Crime Statistics Act, passed on April 23, 1990, requires the collection of data about crimes that manifest evidence of prejudice based on race, religion, sexual orientation, or ethnicity. The FBI's Uniform Crime Reporting (UCR) Program is responsible for collecting and managing hate crime data.

This R Studio Markdown aims to analyze data from 2020 of FBI's Hate Crime Statistics with various key parameters as control variables and defend hypotheses about hate crimes and bias motivation.

## Research Hypotheses

1. Most hate crimes with bias 'Race/Ethnicity/Ancestry' happened mostly at the target victim's place of residence, followed by supermarkets. This suggests that minority people are not safe in their own houses and public essential places like supermarkets in the USA.

2. Most hate crimes are targeted towards Black victims the highest in the USA, followed by a broader classification called Sexual Orientation, where the victims have various sexual orientations. This infers that criminals in America harbor more hate towards the Black race than they do towards an entire broader group of people with diverse sexual orientations.

3. Among juveniles, minors, and kids, hate crimes are seriously directed towards Black juveniles more than any other race. The second-highest category is not another race but the victims of various sexual orientations. White race in the USA commits the most range of hate crimes against any other race. The highest crimes are against other people and specifically Intimidation.

4. Single Bias Incidents, Race Bias, and African Bias are the leading bars showing which type of hate crimes are the highest.

5. More juvenile hate crime victims lead to more adult hate crime victims.

6. White race commits the most number of direct targeted hate crimes like Murder, Rape, Intimidation, followed by the Black race being the second.

7. The mean value of Known offenders is 600+, and intimidation is one of the biggest repeat offenses.

8. Known Offenders cause the most number of hate crimes.

## Functions Used

### Step 1: Install Necessary Packages and Libraries

The necessary packages and libraries are installed using the `install.packages()` function.

### Step 2: Load Libraries

After installation, the required libraries are loaded using the `library()` function. These libraries include `tidyverse`, `readxl`, `haven`, `corrr`, `janitor`, `rstatix`, `lmtest`, `ppcor`, `tableone`, `ggthemes`, `stargazer`, `ggrepel`, and `psych`.

### Step 3: Read Data

The data is read into R objects using the `read.xlsx()` function. Multiple data sheets from the Excel files are read into separate data frames, such as `victims`, `bias`, `location`, `race`, `vicincidents`, and more.

### Step 4: Data Manipulation and Visualization

Data frames are manipulated and visualized using various functions and libraries. For example, `barplot()` is used to create bar plots, `geom_histogram()` and `geom_density()` for histograms, `geom_smooth()` for scatter plots with regression lines, and `ggplot()` for customized visualizations.

### Step 5: Statistical Analysis

Statistical analysis is performed using functions like `lm()` for linear regression, `aov()` for ANOVA test, `t_test()` for t-tests, and `chisq.test()` for the Chi-Square test.

### Step 6: Final Conclusions

The results and conclusions from various analyses are summarized in the "Final Conclusions" section.

## Conclusion

This project demonstrates the use of R Studio for data analysis and visualization of hate crime statistics from the FBI for the year 2020. The research successfully defends several hypotheses related to hate crimes and bias motivation. The findings highlight the importance of addressing hate crimes and working towards creating a more inclusive and tolerant society.

The R Studio Markdown serves as a comprehensive and organized platform to conduct exploratory data analysis, statistical tests, and data visualization, offering valuable insights into the patterns and trends of hate crimes in the USA. It also emphasizes the significance of utilizing data-driven approaches to address and combat hate crimes effectively.
