# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  

# Civic Data Analysis

### Hypothetical Business Case
A mayor created a new data analysis team to provide policy advice. The mayor wants to start a new initiative to move the needle on two separate issues:
1. high school education outcomes,
2. drug abuse in the community.

### Datasets
1. SAT Scores by State
2. Drug Use by Age in the community.

### Objective
- Identify patterns
- Visualize data where relevant and informative
- Generate features
- Pull information from other sources if existing data is deemed inadequate


### Findings
1. SAT Dataset:
    - There is bimodal distribution of the data across states.
    - More information should be gathered for state-specific scores and a history of scores to be able to recommend more county-specific suggestions to the mayor. 
    - The higher the Math Scores, the higher the Verbal Scores, and the higher the Total Score.
    - There is not significant variance of contribution of each subject's score to the Total Score in each state. For example, there is not a single state whereby 70% of the Total Score was attributed to the Math Score.

2. Drug Dataset:
    - Age 12 sample shows strong correlations to hallucinogen, inhalant, and pain relief drug use. Hypothesis that this is due to the accessible nature of these drugs. 
    - Hypohtesis: Meth and Heroin Use averages are essentially the same. This hypothesis was rejected through use of teh t-statistic and p-values. 

3. Recommendations:
    - See if there exists data for the age of test takers so there can be a common ground by which to compare the drug dataset and the SAT score dataset. This might allow for more thorough analysis on how certain age groups that use certain drugs or do not use certain drugs during teen years impact academic success. 
    - Do further research to measure how many home products contain ingredients that double as hallucinogens, inhalants, and pain relievers in order to better understand the strong correlation of these drug types with the age group 12.
    - Obtain additional information on drug use and balance the sample sizes. The sample sizes for each age and age group are incredibly imbalanced, which should be a consdieration if any predictive models are built on this dataset. My recommendation is to pull additional data resources that we can leverage, or work to somehow obtain a larger sample AND more balanced sample.

### Assumptions
* SAT Dataset:
    - Assumed that Rate represents the number of total eligible seniors in a given state who actually took the SAT exam.
