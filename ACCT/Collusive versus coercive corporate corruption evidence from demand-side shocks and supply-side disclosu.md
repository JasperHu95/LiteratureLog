# Collusive versus Coercive Corporate Corruption: Evidence from Demand-Side Shocks and Supply-Side Disclosures

Link: [Collusive versus coercive corporate corruption: evidence from demand-side shocks and supply-side disclosures | Review of Accounting Studies](https://link.springer.com/article/10.1007/s11142-022-09678-0)

## Summary

This study examines the impact of collusive and coercive forms of corporate corruption on firm value, using exogenous criminal prosecutions of regional government officials in China as demand-side shocks and the unique reporting of entertainment and travel costs by Chinese firms as supply-side disclosure of corruption-related spending. The research finds that exposure to corruption-related political risk, measured by abnormal entertainment and travel costs, has a significantly negative relation with market reactions to anti-corruption prosecutions among firms perceived to engage in collusive corruption, and a significantly positive relation among firms perceived to engage in coercive corruption. The findings suggest that investors anticipate a future decline in potential benefits from rent-sharing collusion and a reduction in costs from rent-extracting coercion. The study also finds that the collusion effect is more pronounced for firms in regions with greater government economic intervention, and the coercion effect is more pronounced in industries with stronger business competition. Additionally, the ex ante market reactions are corroborated by the direction of changes in ex post operating performance of firms. Overall, the results indicate that investors can recognize differences in the economic consequences between collusive and coercive corruption, and that the disclosure of corruption-related spending can help investors assess a firm’s exposure to corruption-related risk.

## Introduction

The study investigates whether and how firm value can be influenced differently by collusive and coercive forms of corporate corruption. It draws on exogenous demand-side shocks based on corrupt officials’ prosecutions and supply-side disclosure of corruption-related corporate spending. Corporate corruption can occur through rent sharing with public officials to reduce overall costs or through rent extraction by public officials to increase overall costs. The study aims to provide systematic evidence on the differential economic consequences of collusive versus coercive corporate corruption, focusing on the heterogeneous effects on shareholder wealth.

## Institutional Background

### Demand Side of Corporate Corruption

The Chinese government has made longstanding efforts to curb corruption by prosecuting corrupt officials. During the 18th National Congress of the Chinese Communist Party in November 2012, the government launched its most high-profile anti-corruption campaign, resulting in the prosecution of over 300,000 officials. This campaign provides a quasi-natural experimental setting to evaluate the impact of entertainment and travel costs disclosure on the demand side of corporate corruption.

### Supply Side of Corporate Corruption

Since 2009, all listed firms in China have been required to disclose their entertainment and travel costs in their financial statements. Studies suggest that disclosed entertainment and travel costs mainly comprise managerial excess spending, expenses to build relational capital with clients and suppliers, and bribes to corrupt officials. The normal entertainment and travel costs are a function of the first two components, whereas abnormal entertainment and travel costs reflect the third component. Abnormal entertainment and travel costs are interpreted as a measure of alleged bribes and capture the degree of a firm’s exposure to corruption-related political risk.

### State-Owned versus Non-State-Owned Enterprises

The Chinese stock exchanges comprise two distinct groups of listed firms: state-owned enterprises (SOEs) and non-state-owned enterprises (non-SOEs). SOEs differ from non-SOEs in terms of government-to-business revolving door relations and state financial support. SOEs have more opportunities to engage in rent-sharing with corrupt officials due to their stronger government ties and support, whereas non-SOEs are more susceptible to coercion or extortion by corrupt officials due to their weaker government ties.

## Hypothesis

The study formulates two sets of testable hypotheses based on the literature and institutional background. The first set of hypotheses predicts a valuation discount (premium) for firms on the supply side of collusive (coercive) corporate corruption following negative demand-side shocks to such practices. The second set of hypotheses predicts that the valuation effect for firms on the supply-side of either collusive or coercive corporate corruption is driven by two primary antecedents: the degree of government economic intervention and the intensity of business competition.

## Research Design

### Regression

1. **Estimation of Abnormal Entertainment and Travel Costs (AETC):**
   $$
   ETC = \alpha_0 + \alpha_1 ExecPay + \alpha_2 OwnCon + \alpha_3 BSize + \alpha_4 AccPay + \alpha_5 AccRev + \alpha_6 Size + Industry + Year + \epsilon
   $$
   - **Variables:**
     - $ ETC $: Entertainment and travel costs scaled by sales revenue.
     - $ ExecPay $: Pay for top three managers in the firm, scaled by sales revenue.
     - $ OwnCon $: Ownership percentage of the firm’s 10 largest shareholders.
     - $ BSize $: Total number of directors on the firm’s board.
     - $ AccPay $: Accounts payable, scaled by sales revenue.
     - $ AccRev $: Accounts receivable, scaled by sales revenue.
     - $ Size $: Log of total assets.
     - $ Industry $: Industry fixed effects.
     - $ Year $: Year fixed effects.
     - $ \epsilon $: Residual term capturing abnormal entertainment and travel costs (AETC).

2. **Preliminary Test Based on Total Entertainment and Travel Costs (ETC):**
   $$
   CAR = \beta_0 + \beta_1 Treat + \beta_2 SOE + \beta_3 Treat \times SOE + \beta_4 ETC + \beta_5 ETC \times SOE + \beta_6 Treat \times ETC + \beta_7 Treat \times ETC \times SOE + Controls + Industry + Year + \epsilon
   $$
   - **Variables:**
     - $ CAR $: Cumulative abnormal return from days -1 to +1 around the event date.
     - $ Treat $: Indicator variable for treatment firms (firms headquartered in regions where officials were prosecuted).
     - $ SOE $: Indicator variable for state-owned enterprises.
     - $ ETC $: Actual value of entertainment and travel costs scaled by sales revenue.
     - $ Controls $: Control variables including firm governance characteristics and performance.

3. **Baseline Analysis to Test Hypotheses H1 and H2:**
   $$
   CAR = \gamma_0 + \gamma_1 Treat + \gamma_2 SOE + \gamma_3 Treat \times SOE + \gamma_4 AETC + \gamma_5 AETC \times SOE + \gamma_6 Treat \times AETC + \gamma_7 Treat \times AETC \times SOE + \gamma_8 PETC + \gamma_9 PETC \times SOE + \gamma_{10} Treat \times PETC + \gamma_{11} Treat \times PETC \times SOE + Controls + Industry + Year + \epsilon
   $$
   - **Variables:**
     - $ AETC $: Abnormal entertainment and travel costs.
     - $ PETC $: Predicted entertainment and travel costs.

4. **Preliminary Test Based on Total Entertainment and Travel Costs (ETC) for Conditional Effects:**
   $$
   CAR = \beta_0 + \beta_1 Treat + \beta_2 ETC + \beta_3 IndComp + \beta_4 Treat \times IndComp + \beta_5 GovInt + \beta_6 Treat \times GovInt + \beta_7 Treat \times ETC + \beta_8 ETC \times IndComp + \beta_9 Treat \times ETC \times IndComp + \beta_{10} ETC \times GovInt + \beta_{11} Treat \times ETC \times GovInt + Controls + Industry + Year + \epsilon
   $$
   - **Variables:**
     - $ IndComp $: Indicator variable for industry competition.
     - $ GovInt $: Indicator variable for government intervention.

5. **Baseline Analysis to Test Hypotheses H3 and H4:**
   $$
   CAR = \gamma_0 + \gamma_1 Treat + \gamma_2 IndComp + \gamma_3 Treat \times IndComp + \gamma_4 GovInt + \gamma_5 Treat \times GovInt + \gamma_6 AETC + \gamma_7 Treat \times AETC + \gamma_8 AETC \times IndComp + \gamma_9 Treat \times AETC \times IndComp + \gamma_{10} AETC \times GovInt + \gamma_{11} Treat \times AETC \times GovInt + \gamma_{12} PETC + \gamma_{13} Treat \times PETC \times IndComp + \gamma_{14} PETC \times IndComp + \gamma_{15} Treat \times PETC \times IndComp + \gamma_{16} PETC \times GovInt + \gamma_{17} Treat \times PETC \times GovInt + Controls + Industry + Year + \epsilon
   $$

### Variable Settings

- **ETC**: Entertainment and travel costs scaled by sales revenue.
- **ExecPay**: Pay for top three managers in the firm, scaled by sales revenue.
- **OwnCon**: Ownership percentage of the firm’s 10 largest shareholders.
- **BSize**: Total number of directors on the firm’s board.
- **AccPay**: Accounts payable, scaled by sales revenue.
- **AccRev**: Accounts receivable, scaled by sales revenue.
- **Size**: Log of total assets.
- **Industry**: Industry fixed effects.
- **Year**: Year fixed effects.
- **CAR**: Cumulative abnormal return from days -1 to +1 around the event date.
- **Treat**: Indicator variable for treatment firms.
- **SOE**: Indicator variable for state-owned enterprises.
- **AETC**: Abnormal entertainment and travel costs.
- **PETC**: Predicted entertainment and travel costs.
- **IndComp**: Indicator variable for industry competition.
- **GovInt**: Indicator variable for government intervention.
- **Controls**: Control variables including firm governance characteristics and performance.

### Robustness Tests

1. **Using Only the Treatment Group**: The effects were tested using only the treatment group to ensure the results were not driven by an unidentified effect associated with the control group.
2. **Alternative Measure of Abnormal Stock Returns**: The analysis was repeated using an alternative measure of abnormal stock returns based on the market model.
3. **Placebo Event Tests**: Placebo event dates were counterfactually assigned as five months before the actual event dates to test for spurious correlations.
4. **Difference-in-Differences Analysis**: The changes in net profit margins between firms suspected of collusive and coercive corruption were compared to verify whether the observed relations between abnormal ETC and market reactions aligned with the economic consequences.
5. **Influence of Firm-Specific Political Connections**: The study examined whether firm-specific political connections influenced the effects of collusive and coercive corruption.
6. **Cross-Sectional Variations in the Level of Abnormal ETC**: The baseline findings were tested for firms with positive versus negative abnormal ETC to ensure the results were not driven by underspending on entertainment and travel costs.
7. **Changes in Abnormal ETC**: The study examined how the average level of abnormal ETC and its volatility changed from before to after the anti-corruption prosecutions to support the maintained assumption that these prosecutions could be viewed as negative demand-side shocks to corporate corruption.

### Conclusion

The study concludes that investors can recognize differences in the economic consequences between collusive and coercive corruption and that the disclosure of corruption-related spending can help investors assess a firm’s exposure to corruption-related risk. The findings offer useful policy implications for other jurisdictions, particularly given the increasing international attention to the role of accounting information in fighting corporate corruption.