# Corruption and Insider Trading

Link: [Corruption and insider trading - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0929119924001160)

## Summary

This paper investigates the relationship between firm-level corruption and insider trading in Chinese firms. The authors develop a corruption measure based on excessive Entertainment and Travel Costs (ETC) reported in financial statements, which are a proxy for the relational spending associated with guanxi, a significant cultural factor in China. The study finds that corruption significantly impacts insider trading behavior, leading to more aggressive trading and increased informativeness of trades in both purchases and sales. This relationship remains robust across various factors, including trade characteristics, insider attributes, and firm-level governance. The authors employ a variety of robustness checks, including the Fama-French five-factor model and a stochastic frontier analysis, to validate their findings. Ultimately, they demonstrate that insiders in more corrupt firms are more likely to trade based on private information, enhancing their profitability from such trades.

---

## Introduction
The introduction highlights the growing interest in how culture influences financial decision-making, especially in a Chinese context where **guanxi** (relational networks) plays a critical role. The authors discuss how guanxi, while a normal part of business practice, is closely intertwined with **corruption**. The paper aims to explore the link between guanxi-driven corruption and insider trading informativeness. The authors emphasize the difficulty in measuring guanxi-related spending, which they address by focusing on ETC, a mandatory disclosure in Chinese financial statements since 2010.

---

## Institutional Background
The study focuses on China, a country heavily influenced by **Confucianism** and **guanxi** culture. Guanxi refers to the development of social and emotional ties between individuals and is deeply embedded in both personal and business contexts in China. Business guanxi often manifests through gift exchanges and entertainment, which can lead to favorable business outcomes. This cultural practice, however, has been linked to **corruption**, where excessive spending on entertainment and travel is used to secure government ties and reduce bureaucratic restrictions. Despite several anti-corruption efforts in China, including a significant campaign initiated in 2012, corruption remains pervasive, largely due to weak governance and regulatory enforcement.

---

## Literature Review
The paper builds its foundation on a broad array of existing literature, particularly focusing on how **culture** and **corporate governance** impact financial decision-making and insider trading behavior. Some of the key studies reviewed include:

1. **Culture's Impact on Financial Systems and Economic Growth:**
   - Levine (2005) and Gorodnichenko and Roland (2011) discuss the wide-reaching influence of culture, with an emphasis on its role in shaping a country's financial development, investor protection, and market regulations.

2. **Guanxi and Firm Behavior:**
   - Research by Peng and Luo (2000) and Li et al. (2008) shows how guanxi is crucial for conducting business, particularly in regions with weak institutional frameworks. However, as Luo (2008) argues, this practice can also lead to **corruption**, with corruption becoming normalized in certain organizations (Ashforth and Anand, 2003).

3. **Insider Trading Informativeness:**
   - Research by Seyhun (1986), Lakonishok and Lee (2001), and Huddart and Ke (2007) has consistently shown that insider trades can be predictive of future stock returns. Studies like Jeng et al. (2003) and Aboody and Lev (2000) further suggest that insider purchases tend to be more informative than sales.

4. **Corporate Governance and Corruption:**
   - Prior work by Gul et al. (2011) indicates that poor governance allows for greater corruption and opportunistic behavior, including insider trading.

---

## Hypotheses
The study develops two main hypotheses based on the literature:

1. **H1:** Insiders in more corrupt firms, as measured by abnormal ETC, will trade more aggressively and their trades will be more informative than those in less corrupt firms.
   - This hypothesis is grounded in research that shows how guanxi and corruption create opportunities for insiders to exploit their information advantage.

2. **H2:** The impact of corruption on insider trading will persist after controlling for trade, insider, and firm characteristics.

---

## Research Design

### Regression Equations
The primary regression equations used in the study are centered on the relationship between **abnormal Entertainment and Travel Costs (AbnETC)** and **cumulative abnormal returns (CARs)** following insider trades. The baseline regression for measuring CAR is:

$$
CAR_{i,k,t} = \alpha + \beta_1 AbnETC_{i,t} + \beta_2 Controls_{i,k,t} + \theta_{ipt} + \epsilon_{i,k,t}
$$

Where:
- $CAR_{i,k,t}$: Cumulative abnormal returns following the insider trade.
- $AbnETC_{i,t}$: Proxy for firm-level corruption, based on abnormal entertainment and travel costs.
- $Controls_{i,k,t}$: A series of control variables that capture firm characteristics, trade-specific factors, and insider attributes.
- $\theta_{ipt}$: Fixed effects controlling for firm, province, and year.
- $\epsilon_{i,k,t}$: Error term.

The abnormal ETC measure is derived using the following model:

$$
ETC_{i,t} = \alpha + \beta_1 ExecPay_{i,t} + \beta_2 OwnCon_{i,t} + \beta_3 BSize_{i,t} + \dots + \epsilon_{i,t}
$$

This model regresses **ETC** on several firm-specific variables (e.g., executive pay, board size) to extract the residuals, representing **AbnETC**.

### Variables
- **Dependent Variable:**
  - **CAR (Cumulative Abnormal Returns)**: Calculated over 10, 22, and 30-day windows following insider trades.
  
- **Key Independent Variable:**
  - **AbnETC**: Abnormal Entertainment and Travel Costs, a proxy for firm-level corruption.

- **Control Variables:**
  - **FirmSize**: Natural logarithm of the firm’s market value.
  - **Leverage**: Total debt over total assets.
  - **ROE**: Return on equity.
  - **MultiTrade**: Dummy variable for multiple directors trading on the same day.
  - **ExecDir**: Dummy variable for whether the insider is an executive director.
  - **CEO_Chair**: Dummy for whether the insider is the CEO or Chair of the firm.

---



## Robustness Checks

1. **Alternative Time Windows:** Abnormal returns are recalculated over windows of 10, 22, and 30 days to ensure the findings hold across different time periods.

2. **Alternative Measures of Corruption:** Instead of using raw AbnETC, the authors employ ranked AbnETC and additional proxies (e.g., corporate philanthropy) to rule out confounding variables.

3. **Stochastic Frontier Analysis (SFA):** This method extracts the efficient level of ETC spending, treating corruption as an inefficiency. The model is specified as:

$$
Y_{i,t} = \beta X_{i,t} + v_{i,t} + u_i 
$$

Where:

- $Y_{i,t}$ represents the firm's ETC,
- $v_{i,t}$ accounts for statistical noise,
- $u_i$ captures inefficiency (interpreted as corruption).

---

## Empirical Results

1. **Insider Trading Informativeness:** Insiders in more corrupt firms, as measured by AbnETC, exhibit higher informativeness in both purchases and sales, resulting in significant abnormal returns.

2. **Robustness:** This result holds after controlling for firm characteristics, trade-specific factors, and insider attributes, such as rank and role within the company.

3. **CEO and Chair Turnover:** The informativeness of insider trades decreases following the appointment of a new CEO or Chair, suggesting that new leadership temporarily disrupts insiders' ability to trade based on private information.

4. **Firm-Specific Factors:** Control variables like firm size, leverage, and past returns also affect trade informativeness, with smaller firms and those with higher leverage showing higher levels of insider trading profitability.
