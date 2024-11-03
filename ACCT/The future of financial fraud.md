# The Future of Financial Fraud

Link: [The future of financial fraud - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0929119920301383)

## 1. Introduction

The paper addresses a core research question: *Is financial fraud becoming more prevalent over time?* The author presents conflicting evidence and metrics to examine this question:

- **SEC enforcement actions**: Targeting public companies for financial misrepresentation, showing an upward trend until 2003, after which it leveled or slightly declined.
- **Class action lawsuits**: Cornerstone Research reports a significant increase in cases by 2019, indicating a potential rise in fraud.
- **Measurement limitations**: Trends based on observed enforcement data may be unreliable due to unobserved fraud that does not lead to regulatory actions or lawsuits.

In response, the author suggests a theoretical approach may offer deeper insights. Two main constructs are introduced:

- **The Trust Triangle**: A model that emphasizes various factors that deter fraud and foster trust in financial transactions.
- **The Klein-Leffler Model**: A theoretical framework that highlights reputational capital as a disciplinary mechanism in contractual relationships.

## 2. Construct #1: The Trust Triangle

The **Trust Triangle** model, developed by Dupont and Karpoff, examines factors that mitigate opportunistic behavior and build trust in economic exchanges. The model has three primary pathways:

- **Third-party enforcement**: Involves external enforcement through legal and regulatory systems to deter fraud through penalties. This includes SEC regulations, the Sarbanes-Oxley Act, and enforcement by entities like the DOJ.
- **Related-party enforcement**: Involves reputational capital where firms that act honestly build trust, retain customers, and maintain a competitive edge.
- **First-party enforcement**: Includes personal ethics and cultural values that encourage individuals to act honestly even without external penalties.

The Trust Triangle suggests that the synergy of these three forces helps prevent fraud in financial transactions, with each leg serving as a distinct mechanism for trust enforcement.

## 3. Construct #2: The Klein-Leffler Model

The **Klein-Leffler model** provides a theoretical framework to understand how reputational capital can deter fraud in the absence of direct regulatory enforcement. Key elements of the model include:

- **Profit from cheating** ($W1$): If a firm cheats by delivering a low-quality product under a high-quality promise, it earns a one-time profit:

    ```math
    W1 = \frac{1}{1 + r} \left( (P1 - P0) \cdot x3 - \int_{x0}^{x3} (MC_{\text{min}}(x) - P0) \, dx \right)
    ```

    where $P1$ and $P0$ represent the prices for high and low quality, $r$ is the discount rate, and $x3$ is the quantity produced at low cost.

- **Long-term profit** ($W2$): Firms that consistently produce high-quality goods at a premium price accrue a per-period quasi-rent:

    ```math
    W2 = \frac{1}{r} \left( (P2 - P1) \cdot x1 + \int_{x1}^{x2} (P2 - MC_{\text{high}}(x)) \, dx \right)
    ```

    Here, $W2$ is the present value of consistent high-quality production, with $P2$ representing the premium price for high-quality goods, and $MC_{\text{high}}$ the marginal cost of high-quality production.

- **Decision rule**: The firm decides whether to cheat based on comparing $W1$ and $W2$:

    ```math
    \text{Cheat if } W1 > W2
    ```

    ```math
    \text{Do not cheat if } W2 > W1
    ```

This model demonstrates that firms are more likely to maintain quality when the long-term profit from high-quality production ($W2$) outweighs the one-time gain from cheating ($W1$).

## 4. Comparative Statics of Fintech-driven Changes

This section explores how **financial technology (fintech)** impacts firms’ incentives and the occurrence of fraud. Key aspects include:

- **Reduced transaction and information costs**: Fintech innovations lower costs, potentially increasing firms' reliance on reputational capital.
- **Blockchain and anonymity**: While blockchain enhances third-party enforcement through transparency, increased anonymity on fintech platforms (e.g., crowdfunding) could incentivize fraud due to reduced traceability.
- **Reputational capital condition** (Eq. 4): The reliance on reputational capital depends on specific market dynamics, particularly when the discount rate $r$ is low and the supply elasticity of low-quality goods is not too high:

    ```math
    W2 > W3 \text{ iff } \frac{1}{r} > \frac{x4 - x2}{x2}
    ```

The author concludes that fintech developments can both increase and decrease reliance on reputational capital, contingent upon technological adaptation and regulatory environment.

## 5. Effects of Third-party and First-party Enforcement

Here, the **Klein-Leffler model** is extended to incorporate third-party and first-party enforcement mechanisms into the decision framework:

- **Third-party costs**: Penalties from regulatory bodies, depending on the probability of detection and punishment severity.
- **First-party costs**: Non-monetary costs, such as social stigma and ethical discomfort.

The revised decision rule becomes:

```math
\text{Cheat if } W1 > (W2 + \text{Third-party costs} + \text{First-party costs})
```

Technological advancements that assist regulatory bodies (e.g., big data for fraud detection) could increase third-party costs, potentially reducing the likelihood of fraud.

## 6. Offsetting Forces that Could Lead to More Fraud Over Time

The author highlights **external factors** that may counterbalance a long-term decline in fraud:

- **COVID-19 pandemic and economic downturn**: Increased financial pressures may incentivize firms to commit fraud, especially under high short-term survival costs.
- **Informational and behavioral frictions**: In practice, fraud detection by consumers may be delayed, allowing dishonest firms to operate longer. This delay increases $W1$ and can limit the effectiveness of reputational capital.
- **Institutional mistrust and income inequality**: Rising mistrust in institutions and economic inequality may weaken third-party enforcement and societal ethics, making fraud more likely.

These offsetting forces suggest that, although structural changes may reduce fraud over the long term, short-term crises and fluctuations can lead to temporary increases in fraudulent activities.

## 7. Conclusions

In conclusion, the paper posits that **technological and societal advancements may ultimately reduce financial fraud**. By improving transparency, reducing transaction costs, and enhancing enforcement, these trends could encourage ethical behavior, making it an income-normal good (i.e., demand increases with economic growth). However, the author notes that these conclusions are speculative, as they depend on the interactions between different components of the Trust Triangle.