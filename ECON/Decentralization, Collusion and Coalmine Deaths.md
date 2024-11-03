# Decentralization, Collusion, and Coalmine Deaths

Link: [EconPapers: Decentralization, Collusion, and Coal Mine Deaths](https://econpapers.repec.org/article/tprrestat/v_3a99_3ay_3a2017_3ai_3a1_3ap_3a105-118.htm)

## Summary

The paper investigates the impact of decentralization on workplace safety, particularly in the context of China's coalmine industry. The authors argue that decentralization increases the likelihood of collusion between regulators and firms, which in turn leads to higher workplace mortality. They test this hypothesis by examining the effects of decentralization on coalmine death rates, contingent on the characteristics of regulators, specifically whether the regulator is a native of the province. The study finds that decentralization is correlated with an increase in coalmine death rates, and this effect is more pronounced when the regulator is a native, indicating lower transaction costs for collusion. The paper contributes to the literature on decentralization, collusion, and workplace safety, providing empirical evidence on the theoretical link between decentralization and collusion.

## Introduction

The introduction outlines the importance of workplace safety in both developing and developed countries and highlights the role of collusion between regulators and regulated firms in workplace safety issues. The authors cite examples such as the Upper Big Branch mine explosion and the Fukushima nuclear power plant accident to illustrate the real-world implications of collusion. They note that while theoretical literature exists on how decentralization of regulatory authority may affect collusion, empirical evidence is scarce. The paper aims to fill this gap by using data from China's coalmine industry to study the effects of collusion between regulators and firms on coalmine deaths. The authors focus on China's coalmine industry due to the prevalence of collusion and a unique decentralization experiment that took place in key state coalmines from 1998 to 2000.

## Institutional Background

The institutional background section provides details on the decentralization process in China's coalmine industry. Chinese coalmines are divided into key state coalmines, local state coalmines, and township and village coalmines. The management of key state coalmines was decentralized in 1998, when the management and safety supervision powers were delegated to provincial governments. This decentralization period lasted until 2001 when the State Administration of Work Safety was established, and safety supervision was re-centralized. The authors argue that this decentralization made collusion between regulators and coalmine firms more feasible, leading to higher death rates.

## Hypothesis

The hypothesis section includes a literature review on decentralization and collusion. The authors review theoretical models that suggest decentralization of authority to regulators can induce collusion, leading to adverse outcomes such as lower workplace safety. They propose two main hypotheses:
1. Decentralization increases coalmine death rates due to increased collusion between regulators and firms.
2. The effect of decentralization on death rates is stronger when the regulator is a native of the province, as natives are likely to have lower transaction costs for collusion.

## Literature Review

### Decentralization Literature

- **Empirical Studies on Decentralization**: The authors note that one of the challenges in the empirical literature on decentralization is finding exogenous variations in decentralization. Existing studies often explore either cross-sectional comparisons or changes in one direction (from centralization to decentralization or vice versa). The authors highlight studies that have examined the impacts of both fiscal and political decentralization. For example, Fisman and Gatti (2002) and Arikan (2004) find that fiscal decentralization is associated with less corruption, while Treisman (2002) and Fan et al. (2009) find that political decentralization can lead to lower accountability.
- **China-Specific Studies**: Within the context of China, fiscal decentralization since 1994 is often seen as one of the driving forces of China's growth miracle. Studies like Jin et al. (2005) and Lin and Liu (2000) find a positive impact of decentralization on growth, despite some opposite findings in Zhang and Zou (1998).

### Organizational Literature on Decentralization/Delegation
- The authors review theories in the organizational literature that focus on the costs and benefits of decentralization/delegation. These theories generally argue that decentralization of authority to regulators induces collusion, leading to adverse outcomes. Key references include Tirole (1996), Kofman and Lawarree (1993), Baliga and Sjostrom (1998), Laffont and Martinort (1998), Mookherjee and Tsumagari (2004), and Mookherjee (2006).

### Literature on Political Connections
- This body of work documents the benefits captured by agents with strong political connections, often at the cost of public interest. Examples include Fisman (2001) and Faccio (2006). The closest study to the authors' research is Fisman and Wang (2013), who document that politically connected firms in China have higher mortality using firm-level data from different industries between 2008 and 2011.

### Literature on Corrupt Local Bureaucrats and Politicians
- The authors mention studies that examine how corrupt local bureaucrats and politicians affect the provision of public goods or bads. For example, Burgess et al. (2012) document that local officials' incentives affect the environment using the case of deforestation in Indonesia.

## Research Design

### Regression

1. **Correlation between Decentralization and Death Rates**:
   $$
   \text{DeathRate}_{pt} = \beta D_t + \lambda_p + \lambda_p \times t + \varepsilon_{pt}
   $$
   - $D_t$: Decentralization dummy for the years 1998-2000.
   - $\lambda_p$: Province fixed effects.
   - $\lambda_p \times t$: Province-specific trends.
   - $\varepsilon_{pt}$: Error term.

2. **Decentralization and Collusion: Within-province Evidence**:
   $$
   \text{DeathRate}_{spt} = \beta_1 N_{spt} \times D_t + \beta_N N_{spt} + \gamma' X_{spt} \times D_t + v' X_{spt} + \lambda_p + \gamma_t + \lambda_p \times t + \varepsilon_{spt}
   $$
   - $N_{spt}$: Native regulator dummy.
   - $X_{spt}$: Vector of controls including logs of coal output and coalmine industry wages, safety regulator characteristics (age and tenure), provincial characteristics, and traffic deaths per capita.
   - $\lambda_p$: Province fixed effects.
   - $\gamma_t$: Year fixed effects.
   - $\lambda_p \times t$: Province-specific trends.
   - $\varepsilon_{spt}$: Error term.

3. **Decentralization and Collusion: Within-regulator Evidence**:
   $$
   \text{DeathRate}_{spt} = \beta_1 N_{spt} \times D_t + \beta_N N_{spt} + \gamma' X_{spt} \times D_t + v' X_{spt} + \lambda_p + \gamma_t + \mu_s + \varepsilon_{spt}
   $$
   - $\mu_s$: Regulator fixed effects.
   - $\varepsilon_{spt}$: Error term.

### Variable Settings

- **Dependent Variables**:
  - Death rate: Number of deaths per million tons of coal production.
  - Logged number of deaths.

- **Independent Variables**:
  - Decentralization dummy ($D_t$): 1 for the years 1998-2000, 0 otherwise.
  - Native regulator dummy ($N_{spt}$): 1 if the safety regulator is a native of the province, 0 otherwise.
  - Interaction term ($N_{spt} \times D_t$): Interaction between the native regulator dummy and the decentralization dummy.

- **Controls ($X_{spt}$)**:
  - Logs of coal output and coalmine industry wages.
  - Safety regulator characteristics: Age and tenure.
  - Provincial characteristics: Logs of GDP per capita, electricity consumption, distance to Beijing, whether the provincial governor or secretary is a native, and traffic deaths per capita.

### Robustness Tests

1. **Placebo Tests**:
   - **Traffic Deaths**: The authors use traffic deaths per capita as a placebo test to check if the findings are driven by misreporting.
   - **Local State Coalmine Deaths**: They also use death rates in local state coalmines as another placebo test.

2. **Examining Pre-trends**:
   - The authors use a more flexible specification to evaluate the effect of having a native regulator year by year to check for pre-trends.

3. **Evaluating the Impacts on Deaths and Output Separately**:
   - The authors examine the impact on the logged number of deaths and the logged coal output separately.

4. **Comparing the Impacts of Decentralization and Re-Centralization**:
   - The authors estimate separate regressions for different subperiods (1995-2000 and 1998-2005) to compare the impacts of decentralization and re-centralization.

5. **Additional Evidence**:
   - **Media Exposure**: The authors investigate the effect of media exposure on the interaction effect of decentralization and having native regulators.
   - **Firm-Level Information**: They use firm-level data to examine the impact on firm-level output, employment, average wages, and welfare expenditure.

## Empirical Results

The empirical results section summarizes the findings of the empirical research. The authors find that decentralization is correlated with an increase in coalmine death rates, with an average increase of 0.7 deaths per million tons of coal production. This effect is more pronounced when the regulator is a native, leading to an additional increase of three deaths per million tons of coal production. The results are robust to various robustness checks, including placebo tests and examining pre-trends. The authors also find that the impact of decentralization is larger for native regulators, providing further evidence for the collusion hypothesis.
