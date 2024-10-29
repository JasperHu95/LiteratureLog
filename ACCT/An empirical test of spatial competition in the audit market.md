# An Empirical Test of Spatial Competition in the Audit Market

Link: [An empirical test of spatial competition in the audit market - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S016541011100070X)

## Summary

This paper empirically investigates how spatial competition influences audit pricing in the U.S. audit market, particularly focusing on Big 4 audit firms. The authors build on economic theories of spatial competition, notably Hotelling’s model, to test how differentiation in auditor-client alignment (industry specialization) and competitive distance from the nearest competitor affect audit fees. The findings show that auditors can charge higher fees when they are more specialized in the client’s industry and when they are distanced from their closest competitor in terms of market share.

## Introduction

The introduction highlights that prior studies on audit pricing primarily focus on auditor size and industry specialization, often reporting premium fees for Big N auditors and industry specialists. However, these studies do not fully explain whether such fee premiums arise due to industry specialization itself or due to market power resulting from competitive differentiation. This study seeks to address this gap by distinguishing between the effects of industry specialization and spatial competition on audit pricing. It draws on spatial economics to develop hypotheses about how audit fees are influenced by auditor-client alignment and competition from nearby auditors.

## Institutional Background
The study is set within the highly concentrated U.S. audit market, dominated by Big 4 audit firms. This market is characterized by significant barriers to entry, with regulatory demands for auditing public firms and the reputational capital needed to attract large clients. Auditors often differentiate their services through industry specialization, which helps them mitigate direct price competition. The study explores the dynamics within this concentrated market, particularly how auditors position themselves relative to clients and competitors in terms of both geographical and industry specialization.

## Hypotheses

### Literature Review
Previous literature on audit pricing, such as Simunic (1980), Craswell et al. (1995), and Francis et al. (2005), has focused on understanding how factors like auditor size and specialization affect fees. These studies typically identify fee premiums for Big N auditors, often attributing these to higher audit quality. However, research like Pearson and Trompeter (1994) and Bandyopadhyay and Kao (2004) provides mixed results on whether market concentration leads to higher or lower fees, depending on the nature of competition.

Hotelling’s (1929) model of spatial competition and its extensions, such as those by Chan et al. (2004), suggest that firms competing in product-differentiated markets can sustain higher prices if they position themselves away from direct competitors. These models are used to argue that in the audit market, auditors who specialize in certain industries and differentiate themselves from close competitors can command higher fees.

### Hypothesis Development
1. **Hypothesis 1**: The alignment between an auditor’s industry specialization and a client’s industry will lead to higher audit fees. Clients are willing to pay a premium for auditors with industry expertise that aligns with their needs.
   
2. **Hypothesis 2**: The farther an auditor is from its closest competitor in terms of industry specialization (measured as the distance in market share), the higher the audit fees the auditor can charge. Greater differentiation reduces competitive pressure, enabling higher pricing.

## Research Design

### Model Specification
The authors use an OLS regression model to test their hypotheses. The primary regression equation is:

$${}
\text{LnFee} = \alpha_0 + \alpha_1 \text{Alignment}_{\text{client}} + \alpha_2 \text{Distance}_{\text{competitor}} + \alpha_3 \text{HerfIndex} + \alpha_4 \text{Size} + \alpha_5 \text{LnBu} + \alpha_6 \text{Foreign} + \alpha_7 \text{Cata} + \alpha_8 \text{Quick} + \alpha_9 \text{De} + \alpha_{10} \text{Roi} + \alpha_{11} \text{Loss} + \alpha_{12} \text{Ye} + \alpha_{13} \text{Year} + \alpha_{14} \text{Switch} + \alpha_{15} \text{Alignment}_{\text{client\_national}} + \varepsilon
$${}

### Variables

- **Dependent Variable**:
  - $\text{LnFee}$: Natural logarithm of audit fees.
  
- **Independent Variables**:
  - $\text{Alignment}_{\text{client}}$: Measures how well the auditor’s industry specialization aligns with the client’s industry, proxied by the auditor’s industry portfolio share.
  - $\text{Distance}_{\text{competitor}}$: Represents the market share distance between the incumbent auditor and its closest competitor within the same industry.
  
- **Control Variables**:
  - $\text{HerfIndex}$: Herfindahl index to measure market concentration.
  - $\text{Size}$: Logarithm of the client’s total assets.
  - $\text{LnBu}$: Logarithm of the number of business segments.
  - $\text{Foreign}$: Indicator for whether the client operates foreign subsidiaries.
  - $\text{Cata}$: Ratio of current assets to total assets.
  - $\text{Quick}$: Quick ratio (current assets excluding inventory divided by current liabilities).
  - $\text{De}$: Debt-to-equity ratio.
  - $\text{Roi}$: Return on investment.
  - $\text{Loss}$: Indicator variable for whether the client incurred a loss.
  - $\text{Ye}$: Indicator for whether the fiscal year-end is December 31.
  - $\text{Switch}$: Indicator for whether the client switched auditors.
  - $\text{Alignment}_{\text{client\_national}}$: National-level auditor-client alignment, measured as national industry specialization.

## Robustness Checks

1. **Alternative Variable Definitions**: The researchers tested different measures of auditor specialization and competitor distance, and the results remained consistent.
2. **National-Level Analysis**: Analyzing auditor-client alignment at the national level confirmed the local-level results.
3. **Clustered Standard Errors**: To control for heteroskedasticity and intra-cluster correlations, standard errors were clustered by audit firm.
4. **Fixed Effects**: Industry fixed effects were included to account for industry-wide factors influencing audit fees.
5. **Herfindahl Index**: The Herfindahl index was used to control for the effect of market concentration on audit pricing, ensuring that competitive differentiation rather than market power drives the results.

## Empirical Results

1. **Hypothesis 1**: Auditors with stronger alignment to the client’s industry specialization charge higher fees. For instance, a one standard deviation increase in the auditor’s industry specialization leads to a 6.92% increase in audit fees.
   
2. **Hypothesis 2**: The greater the distance between the auditor’s market share and its closest competitor, the higher the fees. A one standard deviation increase in competitive distance leads to a 7.55% increase in fees.
