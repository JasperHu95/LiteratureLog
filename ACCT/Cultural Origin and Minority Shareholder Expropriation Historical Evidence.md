# Cultural Origin and Minority Shareholder Expropriation: Historical Evidence

Link: [Cultural Origin and Minority Shareholder Expropriation: Historical Evidence - GU - 2024 - Journal of Accounting Research - Wiley Online Library](https://onlinelibrary.wiley.com/doi/10.1111/1475-679X.12517)

## Introduction

The paper addresses the issue of regional variations in minority shareholder expropriation, defined as the exploitation of minority shareholders by controlling shareholders for private gains. Traditional literature attributes these differences to economic institutions that protect property rights, such as the rule of law and investor protections (e.g., La Porta et al., 1997; Johnson et al., 2000). However, recent studies indicate that similar regions often display significant differences in expropriation, suggesting a role for historical and cultural factors. This study focuses on the enduring impact of Confucian cultural values on corporate behavior, proposing that regions historically influenced by Confucianism demonstrate lower levels of minority shareholder expropriation due to norms of generalized morality and ethical behavior.

## Literature Review

The study builds on various streams of literature:

1. **Economic Institutions and Minority Shareholder Expropriation**: Previous research highlights how formal institutions influence minority shareholder protection. Foundational studies (La Porta et al., 1997; Johnson et al., 2000) argue that robust governance mechanisms reduce expropriation. However, these studies also note persistent regional differences within similar institutional frameworks, suggesting the influence of cultural factors.

2. **Cultural Persistence and Economic Outcomes**: Literature suggests that cultural values, once established, can persist and influence economic behavior across generations. Glaeser et al. (1996) and Alesina and Giuliano (2015) find that cultural norms affect governance practices, while Guiso, Sapienza, and Zingales (2016) demonstrate that cultural values can lead to regional economic variations.

3. **Confucian Culture and Generalized Morality**: Confucian values emphasize generalized morality, where ethical behavior extends beyond close personal networks. Studies by Lam (2003) and Tabellini (2008b) propose that Confucian morality promotes fairness in business interactions, potentially discouraging expropriation.

4. **Historical Confucian Influence on Governance**: Chen, Kung, and Ma (2020) and Du (2015) document how Confucian values relate to contemporary governance and educational outcomes, indicating that Confucian heritage may deter exploitative practices.

## Hypothesis Development

The authors hypothesize that regions with a historically strong influence of Confucian values, as indicated by the number of Jinshi (top Confucian scholars), experience lower rates of minority shareholder expropriation. Confucianism's emphasis on morality, transmitted across generations, discourages exploitative behavior, resulting in reduced expropriation in contemporary firms. The hypothesis is based on prior literature indicating that Confucian culture discourages self-serving behavior and fosters ethical oversight mechanisms like high-quality financial reporting and dividend payouts.

## Institutional Background

Confucianism, originating over 2,000 years ago from the teachings of Confucius, promotes a moral framework based on generalized ethics. During Imperial China, Confucianism became institutionalized through the civil service examination system, which selected government officials based on their knowledge of Confucian texts. This created a ruling class of scholar-bureaucrats (Jinshi), who promoted Confucian values in their regions. Despite political upheavals in the 20th century, such as the abolition of the civil service exams and the Cultural Revolution, Confucian values endured, particularly in regions historically associated with Jinshi scholars.

## Research Design

$$
OREC1_{i,t} = \beta_0 + \beta_1 \text{jsh50}_{i,t} + \gamma' X_{i,t} + \epsilon_{i,t}
$$

- **Dependent Variable ($OREC1$)**: This variable captures tunneling activities, measured by "other accounts receivable" tied to controlling shareholders, expressed as a percentage of total assets.
- **Independent Variable ($\text{jsh50}$)**: A proxy for Confucian cultural influence, calculated by the density of Jinshi within a 50-km radius around firm headquarters.
- **Control Variables ($X$)**: Includes firm size (log of assets), central or local government ownership indicators, and fixed effects for year and industry.


$$
\text{Morality}_{p,t} = \beta_{0,s} + \beta_{1,s} \text{jsh50}_p + \gamma' X_p + \epsilon_{p,t}
$$

- **Dependent Variable ($\text{Morality}$)**: A regional measure of Confucian values based on keyword frequency related to Confucian morality in local news articles.
- **Independent Variable ($\text{jsh50}$)**: Density of Jinshi as in the main model.
- **Geographical Control Variables ($X$)**: Includes indicators for Qing Dynasty population (log), Han control, northern location, centrally administered cities, and coastal status.

### Variable Settings

- **$OREC1$**: Minority shareholder expropriation proxy based on related-party transactions.
- **$\text{jsh50}$**: Jinshi density as a proxy for historical Confucian influence.
- **Geographical Controls**: Qing Dynasty population (economic prosperity), Han control, coastal status, etc.
- **Firm-Level Controls**: Firm size, government ownership, year, and industry fixed effects.

### Robustness Checks

1. **Instrumental Variables (IV) Approach**: To address endogeneity, the authors use two IVs:
   - **Number of Books Printed in the Ming Dynasty**: Availability of educational resources that may have supported Confucian transmission.
   - **Number of Confucian Philosophers in the Ming Dynasty**: Distribution of Confucian scholars influenced by factors unrelated to modern expropriation.
2. **Historical Shock (Taiping Rebellion)**: The study uses the Taiping Rebellion as a shock that could have disrupted cultural transmission, testing if Confucian influence persists despite such events.
3. **Alternative Geographic Boundaries**: Testing the robustness of the Jinshi density measure using different geographic boundaries (e.g., 100 km radius, province-level measures).
4. **Alternative Specifications and Controls**: Adding variables for religion, foreign trade influence, and past firm performance, as well as excluding geographic outliers.

## Empirical Results

1. **Negative Relation Between Confucian Influence and Tunneling**: The study finds a robust negative relationship between the density of Jinshi and tunneling, supporting the hypothesis that Confucian values reduce expropriation.

2. **Persistence of Confucian Values**: Despite the Cultural Revolution, Confucian values persisted, as evidenced by Confucian-related keywords in news articles, indicating continued cultural influence.

3. **Role of Governance Mechanisms**: Regions with higher Jinshi density show greater use of oversight mechanisms, such as increased dividend payouts and better financial reporting, further reducing expropriation.

4. **Substitutability with Formal Institutions**: The cultural impact on tunneling is moderated by the presence of formal oversight mechanisms, suggesting that culture and formal governance can act as substitutes.
