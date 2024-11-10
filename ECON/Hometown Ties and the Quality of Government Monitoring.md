# Hometown Ties and the Quality of Government Monitoring

Link: [Hometown Ties and the Quality of Government Monitoring: Evidence from Rotation of Chinese Auditors - American Economic Association](https://www.aeaweb.org/articles?id=10.1257/app.20190516)

## Summary

This paper investigates whether provincial chief auditors in China exhibit leniency when auditing their hometowns, potentially compromising the quality of government oversight. Using data from Chinese prefecture audits between 2006 and 2016, the authors find that hometown auditors report significantly lower suspicious expenditures compared to non-hometown auditors, an effect termed "hometown favoritism." This effect persists throughout the auditor's tenure and diminishes when additional oversight is applied during turnover events of top local officials, implying that favoritism rather than deterrence drives the reduced findings. Complementary analyses on state-owned enterprises reveal increased real activity manipulation under hometown auditors, reinforcing the leniency explanation. The study contributes to literature on government oversight, corruption, and the role of social ties in bureaucracies, especially within environments with weak institutions.

## Introduction

Audits are widely used to curb corruption and improve the management of government investments. However, the independence of audits can be compromised when auditors have pre-existing social ties with those they are auditing. In this study, the researchers focus on China, where "hometown favoritism" has been documented, to test if provincial chief auditors exhibit leniency toward officials in their hometowns. The research contributes to multiple literatures by providing insights into government monitoring, auditor independence, and the role of social ties in bureaucratic oversight. Additionally, the study examines whether the leniency observed is due to favoritism or if auditors act as deterrents, using China’s institutional structure as a basis for identification.

## Institutional Background

China’s governmental audit system was formalized in the 1982 Constitution, establishing the National Audit Office (NAO) and outlining the responsibilities of local audit offices. Provincial chief auditors, who oversee prefecture-level audits, are frequently rotated to prevent local influence. When top local officials leave office, the provincial Organization Department mandates an audit, limiting the chief auditor's discretion and increasing oversight. This structured rotation and hierarchy within China’s government auditing system allow researchers to study the influence of hometown ties on audit quality in a controlled environment.

## Literature Review and Hypothesis Formulation

1. **Auditing and Corruption**: Audits are a key mechanism for reducing corruption, especially in government projects. Past studies have shown that government investments are vulnerable to corruption, with independent audits serving as an effective check (Tanzi and Davoodi, 1998; Dabla-Norris et al., 2012).

2. **Social Ties and Auditor Bias**: Personal relationships between auditors and auditees have been shown to reduce audit quality. Studies, such as He et al. (2017), document lower audit quality when Chinese auditors share social ties with audit committee members. Similar findings have been observed in the United States (Baber, Krishnan, and Zhang, 2014) and in other parts of China (Guan et al., 2016), emphasizing the potential for favoritism and collusion.

3. **Favoritism in Bureaucracies**: Hometown favoritism has been documented in China (Fisman et al., 2018) and other countries with weak institutions (Do, Nguyen, and Tran, 2017). These studies show that auditors or bureaucrats with local ties may exhibit favoritism, compromising oversight quality.

4. **Independent Auditors in Private and Public Sectors**: Previous studies focus on private sector oversight, where auditors are either hired by the firm (creating conflicts) or are third-party agents (Duflo et al., 2013). This paper uniquely examines government-appointed auditors, exploring public sector monitoring where conflicts of interest may differ.

5. **Deterrence vs. Favoritism**: The authors consider two mechanisms by which hometown ties could impact audits. First, auditors might exhibit favoritism, leading to reduced findings of suspicious expenditures. Alternatively, hometown auditors may act as deterrents, enforcing stricter compliance due to their local reputation, which would result in fewer underlying suspicious activities but potentially higher findings when misconduct is detected.

### Hypothesis

Based on the literature, the primary hypothesis is that **hometown auditors will exhibit leniency** towards local officials, leading to lower reported suspicious expenditures. An alternative hypothesis suggests that **hometown auditors may deter misconduct**, resulting in stricter compliance by officials who wish to avoid scrutiny.

## Research Design

To test these hypotheses, the authors employ regression models that control for city and year fixed effects, isolating the effect of hometown ties on audit outcomes. Below are the main regression equations, variable definitions, and robustness checks.

### Regression Equations

The core regression equation used in the analysis is:

$$
\log(\text{SuspiciousExpenditures}_{cy}) = \beta \cdot \text{Hometown}_{a(c)y} + \beta_a X_{a(c)y} + \beta_c X_{cy} + \gamma_c + \nu_y + \epsilon_{cy}
$$

where:

- $\log(\text{SuspiciousExpenditures}_{cy})$: The natural logarithm of the amount of suspicious expenditures uncovered by the auditor for city $c$ in year $y$.

- $\text{Hometown}_{a(c)y}$: Indicator variable set to 1 if the auditor $a$ was born in city $c$.

- **Auditor Characteristics ($X_{a(c)y}$)**: Includes attributes such as age, gender, tenure, education level, finance background, and prior job position.
- **City Characteristics ($X_{cy}$)**: City-level controls like GDP per capita, population, industrial ratio, government revenue, fiscal balance, foreign direct investment, and average years of education.

- $\gamma_c$: City fixed effects.
- $\nu_y$: Year fixed effects.
- $\epsilon_{cy}$: Error term, clustered at the city level to account for within-city correlation over time.

### Additional Models

- **Suspicious expenditures per audit**: $\log(\text{SuspiciousExpenditures per Audit})$
- **Number of audits conducted**: $\log(\text{Projects Audited})$

### Tenure Interaction Models

$$
\log(\text{SuspiciousExpenditures}_{cy}) = \beta \cdot \text{Hometown}_{a(c)y} + \theta \cdot \text{Tenure}_{a(c)y} \cdot \text{Hometown}_{a(c)y} + \ldots
$$

where tenure interactions like $\text{Tenure}_{a(c)y} \cdot \text{Hometown}_{a(c)y}$ and higher-order terms (e.g., $\text{Tenure}^2 \cdot \text{Hometown}_{a(c)y}$) allow for testing changes in favoritism over time.

### Turnover Model

$$
\log(\text{SuspiciousExpenditures}_{cy}) = \beta \cdot \text{Hometown}_{a(c)y} + \delta \cdot \text{CityTurnover}_{cy} \cdot \text{Hometown}_{a(c)y} + \ldots
$$

where $\text{CityTurnover}_{cy}$ is an indicator variable for years in which a turnover occurs for top local officials.

### Variable Settings

- **Dependent Variables**:
  - $\text{SuspiciousExpenditures}$: Total amount of flagged suspicious expenditures.
  - $\text{SuspiciousExpenditures per Audit}$: Suspicious expenditures divided by the number of audited projects.
  - $\text{Projects Audited}$: The count of projects audited.

- **Independent Variables**:
  - $\text{Hometown}$: Binary variable indicating if the provincial chief auditor was born in the city under audit.
  - $\text{CityTurnover}$: Binary variable indicating a turnover event for top local officials.
  - $\text{Tenure}$: The number of years the auditor has served in their role.

- **Control Variables**:
  - **Auditor Attributes**: Age, gender, tenure, education, finance background, and prior positions.
  - **City Attributes**: Economic and demographic indicators such as GDP per capita, population size, industrial output ratio, government fiscal metrics, and education levels.

### Empirical Results

1. **Hometown Effect**: Hometown auditors report 38% less in suspicious expenditures compared to non-hometown auditors, consistent across tenure.
2. **Turnover Events**: The hometown effect is mitigated when top city officials depart, implying oversight constrains favoritism.
3. **SOE Analysis**: State-owned enterprises display higher earnings manipulation under hometown auditors, supporting the leniency hypothesis.