# Audit Office Labor Market Proximity and Audit Quality

Link: [Audit Office Labor Market Proximity and Audit Quality | The Accounting Review | American Accounting Association](https://publications.aaahq.org/accounting-review/article-abstract/97/2/317/4357/Audit-Office-Labor-Market-Proximity-and-Audit?redirectedFrom=fulltext)

## Summary

This study explores the relationship between the proximity of Big 4 audit offices to key feeder schools and accredited universities and the quality of audits performed by these offices. The research finds that audit offices located closer to a higher number of these feeder schools tend to deliver higher audit quality, as evidenced by a lower likelihood of financial misstatements. The findings suggest that labor market proximity allows audit offices to recruit higher-quality staff auditors, which enhances audit quality. The results are robust to various measures of labor market proximity, audit quality proxies, and multiple robustness checks, including an instrumental variable approach and entropy balancing.

## Introduction

The introduction frames the study in the context of the ongoing talent search challenge faced by audit firms, particularly Big 4 firms. The American Institute of Certified Public Accountants (AICPA) has long highlighted staff recruitment as a top concern for audit firms. Big 4 firms tend to recruit from a select group of feeder schools with accredited accounting programs. This study examines whether audit quality is influenced by the proximity of audit offices to these feeder schools, which are key suppliers of staff auditors. The study focuses on how audit offices can benefit from better recruiting outcomes due to proximity, which may lead to improved audit quality.

## Institutional Background
The U.S. audit market is dominated by Big 4 firms, which rely heavily on university graduates to fill staff auditor positions. These firms maintain recruitment relationships with feeder schools, which are universities that offer accredited accounting programs. The study highlights that Big 4 audit firms recruit between 67% and 78% of their new hires from a select group of 256 feeder schools, which represents only 6% of all U.S. universities. The research investigates whether the proximity of audit offices to these feeder schools has a tangible impact on audit quality by allowing offices to recruit better talent, improving employee retention, and fostering a better match between recruits and the firm.

## Hypotheses

### Literature Review
Previous research has focused on the human capital aspects of audit quality, with studies indicating that higher levels of education and staff auditor quality are associated with better audit outcomes. Notable studies like Beck et al. (2018) and Hoopes et al. (2018) found that audit quality improves in cities with high concentrations of educated adults and higher salaries for staff auditors. Other studies, such as those by Francis et al. (2013) and Kohlbeck and Mayhew (2017), have shown that labor market characteristics, including auditor talent pools, significantly influence audit quality. This study builds on this literature by examining the specific impact of proximity to feeder schools.

### Hypothesis Development
The authors hypothesize that audit offices located closer to more feeder and accredited schools will produce higher audit quality due to their ability to recruit better graduates and reduce staff turnover. Specifically:

1. **Hypothesis 1**: The proximity of audit offices to more feeder and accredited schools is positively associated with audit quality, measured by a lower likelihood of financial misstatements.
   
2. **Hypothesis 2**: The benefits of proximity are more pronounced for larger audit offices and those located in cities with a higher concentration of audit offices, as these offices face greater demand for new staff auditors.

## Research Design

### Sample

The sample includes 39,337 firm-year observations from Big 4 clients over the period 2000-2016. The focus is on U.S.-based audit offices, and firms audited by non-Big 4 firms or located outside the U.S. are excluded. The analysis concentrates on how the number of feeder and accredited schools within 60 miles of an audit office influences audit quality.

### Model Specification

The study uses a logistic regression model to test the relationship between audit office proximity to feeder schools and audit quality, with the following model:

$$
\text{MISSTATE} = f(\text{ACCFEDR/FEDR}, \text{Control Variables})
$$

Where:
- $\text{MISSTATE}$: An indicator variable for whether the client firm issued a financial misstatement in a given year.
- $\text{ACCFEDR}$: The number of feeder and accredited schools within 60 miles of the audit office.
- $\text{FEDR}$: The number of feeder schools within 60 miles of the audit office.

### Variables
- **Dependent Variable**:
  - $\text{MISSTATE}$: Indicator of financial restatements or misstatements by client firms.
  
- **Independent Variables**:
  - $\text{ACCFEDR}$: Count of feeder and accredited schools within 60 miles of an audit office.
  - $\text{FEDR}$: Count of feeder schools within 60 miles of an audit office.

- **Control Variables**:
  - $\text{LNTA}$: Natural logarithm of total assets.
  - $\text{MTB}$: Market-to-book ratio.
  - $\text{LEV}$: Leverage ratio.
  - $\text{LOSS}$: Indicator for whether the firm posted a loss.
  - $\text{CHGTA}$: Change in total assets.
  - $\text{MNA}$: Indicator for mergers and acquisitions activity.
  - $\text{SWITCH}$: Indicator for auditor switches.
  - $\text{ROA}$: Return on assets.
  - $\text{ROAVOL}$: Volatility of return on assets.
  - $\text{LIT}$: Indicator for high litigation risk industries.
  - $\text{LNFEES}$: Natural logarithm of audit fees.
  - $\text{LEADER}$: Industry leadership of the audit firm.
  - **City-Level Controls**: These include education levels (EDU), salary levels (SALARY), and commuting time (COMMUTE).
  - **Additional Controls**: Proximity to the Securities and Exchange Commission (SEC) and PCAOB offices (PCAOBPROX).

## Robustness Checks

1. **Instrumental Variable Approach**: The study uses the historical presence of railroad tracks in metropolitan areas as an instrument for labor market proximity to address endogeneity concerns. The results remain significant.

2. **Entropy Balancing**: The analysis reweights the sample using entropy balancing to ensure that the control variables are balanced across treatment and control groups. The findings continue to hold.

3. **Additional City- and State-Level Controls**: Further analyses include additional controls for corporate governance and city-level economic conditions. These tests confirm the main findings.

4. **Moderating Effect of Demand**: The study also finds that the proximity effect is stronger in larger offices and those located in cities with higher demand for staff auditors.

## Empirical Results

1. **Hypothesis 1 Supported**: Audit offices closer to more feeder and accredited schools are associated with higher audit quality. Specifically, an interquartile increase in the number of feeder schools reduces the likelihood of a client misstatement by around 9.44%.
   
2. **Larger and More Concentrated Offices**: The positive effect of proximity on audit quality is more pronounced for larger offices and those located in cities with a higher concentration of audit offices, supporting Hypothesis 2.
