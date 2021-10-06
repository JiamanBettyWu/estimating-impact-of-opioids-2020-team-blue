# [Estimating the Effect of Policies on Opioid Prescriptions and Overdose Deaths in The U.S.](https://github.com/JiamanBettyWu/estimating-impact-of-opioids-2020-team-blue/blob/master/40_docs/Report%20(Technical).pdf)

## Motivation

As the Opioid Overdose Crisis becomes increasingly concerning, many states have taken actions to regulate opioid prescriptions in hope to lower the addiction rate and the overdose mortality rate due to the misuse of opioids. However, policy interventions are not guaranteed to be effective. While strict regulations on opioid prescriptions would have a direct impact on the amount of opioids prescribed by medical practitioners, reducing the risk of potential addiction, it is unclear that overdose mortality rate would decrease correspondingly.

With these concerns in mind, we evaluate the effectiveness of policy interventions in Florida, Texas and Washington. While most of the states did not publish regulations until recent years, Texas, Florida, and Washington were the pioneers in regulating opioids abuse and they passed laws in 2007, 2010, 2012, respectively. In this project, we investigate the following research questions: 

- Does policy change on opioid drugs reduce the opioid prescriptions?
- Does policy change on opioid drugs reduce the mortality rate? 

## Research Design

We estimate the effect of policy interventions on opioid prescriptions and drug overdose deaths using: 
- pre-post analysis
- difference-in-difference analysis. 

## Data 
### Population Dataset

Since the population varies across different counties in the United States, it would be reasonable to normalize the amount of drug prescriptions and drug overdose deaths by population in each county. Therefore, we need the population data at county levels for all 49 states (except Alaska) from 2003 to 2015.

The data we find is from the U.S. Department of Energy Office of Scientific and Technical Information. It contains 3,144 observations and 23 columns and includes the intercensal estimates of the resident population from 2000 to 2019 for all counties from 50 states as well as Washington DC. Column 1 - 3 contains state, county, and FIPS code. Column 4 - 23 contains the population from 2000 to 2019.

### Opioids Prescriptions Dataset

This dataset released by Washington Post contains all prescribed opioid drug shipments in the United States from 2006 to 2013.

### Vital Statistics Mortality Dataset

US Vital Statistics records data is used to obtain drug overdoses death. US Vital Statistics records include data on death in the United States on county levels by years. 

National mortality data is provided from 2003 to 2015. In the data, seven categories of death causes are recorded on county levels: All other non-drug and non-alcohol causes, Drug poisonings (overdose) Unintentional (X40-X44), All other alcohol-induced causes, Drug poisonings (overdose) Suicide (X60-X64), Drug poisonings (overdose),  Undetermined (Y10-Y14), All other drug-induced causes, and Alcohol poisonings (overdose) (X45, X65, Y15). Other information included in the datasets are county names, state, year, and the count of the death for each category in each county for a given year.

## Conclusion

Our analysis shows that Florida is effective in reducing opioid prescriptions and mitigating drug overdose deaths. Texas and Washington are successful in restricting the amount of the opioid prescriptions. However, the effects of policies on drug overdose deaths in Texas and Washington are ambiguous, since the trend for both states fluctuates  -- it generally decreases after the policy before it increases again. Therefore, we believe that a more rigorous analysis and longer time span are needed in order to extract more informative conclusions.




