# Awareness of SEC Enforcement and Auditor Reporting Decisions

Link: [Awareness of SEC Enforcement and Auditor Reporting Decisions - Defond - 2018 - Contemporary Accounting Research - Wiley Online Library](https://onlinelibrary.wiley.com/doi/abs/10.1111/1911-3846.12352)

## Summary

This paper examines the impact of auditor awareness of SEC enforcement activities on their reporting decisions, particularly regarding going-concern opinions. The research uses two measures of awareness: the proximity of audit offices to SEC regional offices and the proximity of audit offices to specific SEC enforcement actions against auditors. The findings reveal that non-Big 4 audit offices located closer to SEC regional offices or near recent enforcement actions are more likely to issue going-concern reports to financially distressed clients. However, these offices also tend to over-report going-concern issues (false positives), leading to higher audit fees and increased auditor switching rates. For Big 4 auditors, some evidence suggests that awareness of SEC enforcement improves reporting accuracy by reducing Type II errors (failing to issue a going-concern report when needed).

## Introduction
The study explores how the SEC’s enforcement activities, carried out through its 11 regional offices, influence auditors' decisions, particularly with regard to going-concern reports. The authors argue that proximity to SEC offices increases auditor awareness of enforcement actions, which in turn affects auditor behavior. The paper focuses on how this heightened awareness influences the issuance of first-time going-concern reports, which are important because they reflect the auditor's independent judgment about the client’s ability to continue operating.

The key research question addressed is whether auditors located near SEC offices or in cities with recent SEC enforcement actions adjust their reporting behavior to mitigate the risk of SEC investigations, and whether this effect is more pronounced for non-Big 4 auditors.

## Institutional Background
The U.S. Securities and Exchange Commission (SEC) is responsible for enforcing federal securities laws, ensuring the accuracy of financial reporting, and overseeing the work of external auditors. The SEC operates through its national office in Washington, D.C., and 11 regional offices, which handle much of the enforcement work. The proximity of auditors to these regional offices or to SEC enforcement actions is posited to increase the auditors’ awareness of enforcement risks, potentially affecting their decisions on issuing going-concern opinions.

Non-Big 4 audit firms, which audit a large proportion of SEC-registered companies and issue most going-concern reports, may be particularly sensitive to the local SEC enforcement environment. Big 4 firms, on the other hand, are expected to have more standardized quality control mechanisms that may mitigate the influence of geographic proximity on their reporting behavior.

## Hypotheses

### Literature Review
Prior research has examined factors influencing auditor reporting decisions, such as financial distress and the risk of bankruptcy. Studies like those of Carcello and Palmrose (1994) and Cox et al. (2003) have shown that auditors face litigation and reputational risks if they fail to issue appropriate going-concern reports. The influence of proximity to regulators has also been studied in contexts like investment decisions (Coval and Moskowitz, 2001), but the impact on auditing decisions has been underexplored.

### Hypothesis Development
The authors hypothesize that auditors who are more aware of SEC enforcement are more likely to issue first-time going-concern reports for financially distressed clients to avoid the risk of regulatory sanctions.

1. **Hypothesis 1**: Audit offices with greater awareness of SEC enforcement (as measured by proximity to SEC offices and recent enforcement actions) are more likely to issue first-time going-concern reports to distressed clients.

2. **Hypothesis 2**: The impact of SEC awareness on going-concern reporting is stronger for non-Big 4 audit offices than for Big 4 offices, given the Big 4’s superior reputation incentives and internal control systems.

## Research Design

### Sample

The sample consists of 14,354 firm-year observations of financially distressed companies audited between 2000 and 2014, including both Big 4 and non-Big 4 auditors. Firms with prior going-concern reports and firms audited by Arthur Andersen are excluded, resulting in 5,149 non-Big 4 firm-years and 9,205 Big 4 firm-years.

### Model Specification
The authors use a logistic regression model to examine whether auditors’ awareness of SEC enforcement activities affects the likelihood of issuing first-time going-concern reports:

$\require{enclose}
\enclose{box}{
\text{Prob}(GoingConcern) = \alpha + \beta_1 \text{Auditor Proximity} + \beta_2 \text{Auditor AAER}_{t-1} + \beta_3 \text{Non-Auditor AAER}_{t-1} + \gamma X + \text{Fixed Effects} + \varepsilon
}$

- **Dependent Variable**: 
  - $\text{GoingConcern}$: A binary variable indicating whether a first-time going-concern report is issued.
  
- **Independent Variables**:
  - $\text{Auditor Proximity}$: The distance between the audit office and the nearest SEC regional office.
  - $\text{Auditor AAER}_{t-1}$: Whether an SEC Accounting and Auditing Enforcement Release (AAER) was issued against an auditor in the same city in the prior year.
  - $\text{Non-Auditor AAER}_{t-1}$: Whether an AAER was issued against a company or executive in the same city in the prior year.

- **Control Variables**: 
  - Firm characteristics (e.g., size, leverage, profitability), earnings quality, client proximity to SEC offices, industry, year, and SEC region fixed effects.

## Robustness Checks

1. **Alternative Proximity Measures**: The authors test different measures of proximity, including whether the audit office is within 100 kilometers of an SEC office, and the results remain consistent.
2. **Earnings Quality Controls**: Measures of accrual quality and earnings management are included to ensure that the results are not driven by poor financial reporting quality.
3. **Client Proximity**: Client proximity to SEC offices is controlled for to ensure that the effects are not confounded by the client’s location relative to the SEC.

## Additional Analyses

1. **Higher Audit Fees**: Non-Big 4 clients in SEC cities pay approximately 10% higher audit fees.
2. **Increased Auditor Switching**: These clients are also more likely to switch auditors, with the switching rate increasing by 50% in SEC cities.

## Empirical Results
1. **Hypothesis 1 Supported**: Non-Big 4 auditors located closer to SEC offices or recent enforcement actions are significantly more likely to issue first-time going-concern reports. For example, non-Big 4 auditors in cities with SEC regional offices issue 45% more going-concern reports compared to those in other cities.
   
2. **Conservatism in Reporting**: Non-Big 4 auditors closer to SEC offices are also more likely to issue false positives (i.e., going-concern reports to firms that do not fail), reflecting a conservative bias driven by heightened awareness of SEC enforcement risks.

3. **Big 4 Offices**: For Big 4 auditors, the effect of proximity is weaker, but there is some evidence that closer proximity to SEC offices reduces Type II errors (failing to issue a going-concern report when necessary).
