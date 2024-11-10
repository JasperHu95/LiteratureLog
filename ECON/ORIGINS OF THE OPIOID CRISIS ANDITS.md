# Origins of the Opioid Crisis and Its Enduring Impacts

Link: [Origins of the Opioid Crisis and its Enduring Impacts* | The Quarterly Journal of Economics | Oxford Academic](https://academic.oup.com/qje/article/137/2/1139/6427381)

## Summary

This paper investigates the initial causes of the U.S. opioid crisis, linking it primarily to the 1996 introduction and aggressive marketing of OxyContin by Purdue Pharma. The authors analyze cross-state variations in OxyContin exposure, leveraging differences in state policies—specifically, "triplicate prescription programs" that limited OxyContin's market entry in certain states. The findings reveal that states with triplicate programs experienced significantly lower rates of opioid overdose deaths over time. The results suggest that the marketing and distribution strategies for OxyContin were critical in driving the increase in opioid overdose deaths, which has persisted for over two decades.

## Introduction
The opioid crisis has led to a sharp increase in drug overdose deaths in the U.S. since the 1990s. A variety of hypotheses have been proposed to explain the crisis, with some attributing it to economic and social conditions, while others emphasize supply-side factors, such as changes in medical guidelines and pharmaceutical marketing strategies. This study examines the role of OxyContin's introduction and aggressive marketing as key drivers of the crisis, particularly in states without triplicate prescription programs, where OxyContin was marketed more freely.

## Literature Review

1. **Demand-Side Hypotheses**: Case and Deaton (2015, 2017) argue that the crisis is partly driven by "deaths of despair" caused by economic and social hardships. This theory suggests that deteriorating economic conditions increase the likelihood of substance abuse. However, empirical findings on the economic determinants of opioid misuse are mixed. For example, Ruhm (2019a), Pierce and Schott (2020), and Venkataramani et al. (2020) present varied evidence on the influence of economic factors on drug misuse and overdose rates.

2. **Supply-Side Hypotheses**: Other studies focus on supply factors, particularly the role of pharmaceutical companies in promoting opioid use. In the 1990s, there was a shift in attitudes toward pain management, encouraging more aggressive use of opioids (Quinones, 2015; Jones et al., 2018). Purdue Pharma's 1996 release of OxyContin marked a pivotal shift, as the drug became one of the most commonly abused prescription opioids (Cicero, Inciardi, and Muñoz, 2005). Despite widespread discussion of supply-side factors, there has been limited empirical evidence pinpointing the role of pharmaceutical marketing.

3. **Opioid Availability**: Ruhm (2019a) found that increased opioid availability was a significant driver of overdose rates, more so than economic conditions. Powell, Pacula, and Taylor (2020) further emphasize that healthcare access, such as through Medicare, amplified opioid misuse and overdose deaths.

4. **Place-Based Factors**: Finkelstein, Gentzkow, and Williams (2018) demonstrate that location-specific factors, rather than individual characteristics, are critical in determining opioid misuse. However, they do not separate the effects of local economic conditions from opioid availability.

## Institutional Background
The study explores the impact of triplicate prescription programs in certain states. These programs required physicians to use special prescription forms for Schedule II drugs, creating additional barriers to opioid prescribing. Due to these barriers, Purdue Pharma’s internal documents reveal that the company targeted non-triplicate states more aggressively with its marketing, as physicians in triplicate states were more hesitant to prescribe OxyContin. This variation in marketing exposure allows the authors to estimate the impact of OxyContin’s introduction on overdose deaths.

## Hypothesis
The authors hypothesize that the aggressive marketing and distribution of OxyContin significantly contributed to the rise in opioid overdose deaths. This hypothesis is grounded in prior research indicating that supply-side factors, including pharmaceutical marketing, played a major role in the opioid epidemic. The study specifically predicts that non-triplicate states, which received higher marketing exposure, would experience higher overdose rates.

## Research Design

1. **Event Study Specification**:
   Within the event study model, the equation is:
   $$
   y_{st} = \alpha_s + \gamma_t + \sum_{k=1983}^{2017} \beta_k \times \text{Nontriplicate}_s \times 1(t = k) + \varepsilon_{st}
   $$
   
   This model estimates the differential change in overdose death rates between non-triplicate and triplicate states for each year, with 1995 as the baseline.
   
2. **Difference-in-Differences Specification**:
   To capture effects over time, the authors define:
   
   $$
   y_{st} = \alpha_s + \gamma_t + \delta_1 \times \text{Nontriplicate}_s \times 1(1996 \leq t \leq 2000) + \delta_2 \times \text{Nontriplicate}_s \times 1(2001 \leq t \leq 2010) + \delta_3 \times \text{Nontriplicate}_s \times 1(2011 \leq t \leq 2017) + \varepsilon_{st}
   $$
   

- **Dependent Variables**: Overdose death rates (all drug overdoses and opioid-specific overdoses) per 100,000 population.
- **Independent Variables**: Indicators for triplicate and non-triplicate states, time dummies, and controls for demographics (e.g., racial composition, age groups, education, population size).

### Robustness

1. **Covariate Controls**: Models control for demographics (e.g., race, age, education) to account for population differences.

2. **Wild Cluster Bootstrap**: Standard errors are adjusted using a restricted wild cluster bootstrap with Webb’s six-point weight distribution, suitable for the small sample size of untreated states.

3. **Event Study**: The event study model checks pre-treatment trends to validate the parallel trends assumption.

4. **Geographic Controls**: Census region-year interactions are added to control for geographic variations in overdose trends.

5. **Permutation Tests**: Random assignments of triplicate status test whether similar effects might occur by chance.

6. **Alternative Data Sources**: The study uses multiple data sources (e.g., ARCOS, Medicaid, MEPS, NSDUH) to confirm results.

7. **Spillover Models**: Additional models assess whether OxyContin marketing influenced the use of other opioids, particularly oxycodone products.

8. **Alternative Definitions of Outcomes**: Broader overdose categories are analyzed to account for potential misclassification.

## Empirical Results

1. **OxyContin Distribution**: States without triplicate programs had significantly higher rates of OxyContin distribution.

2. **Overdose Rates**: Non-triplicate states saw substantial increases in overdose deaths, with this effect persisting over two decades.

3. **Robustness**: Results remain consistent across different model specifications and are not explained by other policies, economic shocks, or demographic factors.
