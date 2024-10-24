# Does Distance Matter? An Investigation of Partners Who Audit Distant Clients and the Effects on Audit Quality

Link: [Does Distance Matter? An Investigation of Partners Who Audit Distant Clients and the Effects on Audit Quality - Francis - 2022 - Contemporary Accounting Research - Wiley Online Library](https://onlinelibrary.wiley.com/doi/full/10.1111/1911-3846.12744)

## Summary

This paper investigates how the geographic distance between audit partners and their clients affects audit quality. Using hand-collected data, the authors find that nearly half of the audit partners in their sample are assigned to clients headquartered more than 100 kilometers away from the partners' home locations. Few partners relocate after receiving their assignments, leading to a situation where over one-third of clients are audited by partners who must commute long distances. The study shows that audit quality decreases as the distance between the partner and the client increases. However, the negative impact of distance is mitigated when direct flights are available to the client’s headquarters or when the client’s operations are geographically dispersed.

## Introduction
The introduction explains how partner-client matching processes are influenced by various criteria, including geographic proximity. The U.S. Public Company Accounting Oversight Board (PCAOB) mandates that audit partners rotate off engagements every five years, which sometimes results in assignments to distant clients. The authors aim to understand how this geographic separation impacts audit quality, using a novel dataset that includes the home locations of audit partners. They focus on two main questions: (1) How does geographic distance influence partner-client matching? and (2) How does the distance between audit partners and clients affect audit quality?

## Institutional Background
Audit standards in the U.S. require audit partners to rotate every five years, which often leads to partners being assigned to clients who are not local. The PCAOB emphasizes that lead engagement partners are responsible for audit quality, making their independence and direct involvement crucial. However, little academic research has examined how the geographic proximity of auditors affects the quality of audits. This study explores the role of distance in partner-client matching and assesses its effect on audit outcomes.

## Hypothesis

### Literature Review
Existing literature on partner-client relationships focuses primarily on how partner characteristics, such as expertise and independence, affect audit quality. Qualitative studies like those by Daugherty et al. (2012) indicate that long commutes can negatively affect client service and audit quality. There is also evidence from other fields, such as finance and economics, that geographic distance increases information asymmetry, leading to poorer decision-making. This study builds on these findings by investigating how the distance between auditors and clients affects audit quality in a large sample of audit engagements.

### Hypothesis Development
The authors hypothesize that audit quality is negatively affected when audit partners reside farther from their clients. This hypothesis is based on the assumption that geographic distance reduces the frequency and quality of face-to-face interactions, both with clients and with audit teams.

**Hypothesis**: Audit quality decreases when audit partners live farther away from their clients.

## Research Design

### Sample

The study's sample consists of 9,403 client-year observations from 2016 to 2019, covering 3,464 unique public companies and 1,833 unique audit partners. The data is sourced from PCAOB’s Form AP and the Audit Analytics database.

### Model Specification

The primary regression model used to test the hypothesis is as follows:

$$
\text{AuditQuality} = \alpha + \beta_1 \text{PartnerDistance} + \beta_2 \text{DirectFlight} + \beta_3 \text{ClientDispersion} + \gamma X + \varepsilon
$$

Where:
- **AuditQuality**: The likelihood of financial misstatements or whether the client meets/just beats analysts' forecasts.
- **PartnerDistance**: The distance between the partner’s home and the client’s headquarters.
- **DirectFlight**: A binary variable indicating whether a direct flight is available between the partner’s home city and the client’s headquarters.
- **ClientDispersion**: A measure of how geographically dispersed the client’s operations are.
- **X**: A vector of control variables including firm size, industry complexity, and partner workload.

### Variables
- **Dependent Variables**:
  - Likelihood of financial misstatement.
  - Whether the client meets or beats analysts’ forecasts.
  
- **Independent Variables**:
  - **PartnerDistance**: Natural logarithm of the distance (in kilometers) between the partner’s home and the client’s headquarters.
  - **DirectFlight**: Dummy variable indicating if direct flights exist between the partner's city and the client’s city.
  - **ClientDispersion**: The geographical dispersion of the client’s operations.

- **Control Variables**:
  - Partner workload, industry specialization, client characteristics (size, complexity, etc.), and firm tenure.

## Empirical Results

1. **Hypothesis Supported**: The results indicate that audit quality decreases as the distance between audit partners and clients increases. The likelihood of financial misstatements and the probability of clients meeting or just beating analysts’ forecasts both rise with greater partner distance.

2. **Mitigating Factors**: The availability of direct flights between the partner’s city and the client’s headquarters mitigates the negative effect of distance on audit quality. Similarly, when clients have geographically dispersed operations, the negative effect of partner distance is less pronounced.

## Robustness Checks

The authors conduct several robustness checks, including:

1. **Instrumental Variable Approach**: Using the availability of local partners as an instrument for partner distance, the authors find consistent results, supporting the primary findings.

2. **Partner-Client Matching Analysis**: The study investigates how partner characteristics, such as industry expertise and workload, affect the likelihood of a distant partner being assigned to a client. The results show that distant partners are more likely to be assigned when they possess specific expertise that the client values, confirming that distance is one of many factors in partner-client matching.

3. **Alternative Proximity Measures**: The authors test different distance thresholds (e.g., 100 km, 500 km) and find consistent results across various specifications.

## Conclusion

The study concludes that audit partners' geographic distance from their clients negatively impacts audit quality, primarily by increasing the likelihood of financial misstatements and earnings management. However, access to direct flights and the geographic dispersion of the client’s operations can mitigate this effect. These findings provide valuable insights for regulators and practitioners, suggesting that distance is an important consideration in the partner-client matching process and audit quality outcomes.