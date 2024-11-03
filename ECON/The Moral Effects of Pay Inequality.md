# The Morale Effects of Pay Inequality

Link: [Morale Effects of Pay Inequality](https://academic.oup.com/qje/article-abstract/133/2/611/4430649?redirectedFrom=fulltext)

## Summary

This study examines the impact of pay inequality on worker morale and productivity in an Indian manufacturing context. Using a randomized field experiment with over 300 workers, the researchers assess how wage differences among coworkers influence productivity, attendance, and group cohesion. Results indicate that when workers are aware that pay differences reflect relative productivity, pay inequality has limited effects on output or cohesion. However, when productivity differences are less visible, pay inequality significantly decreases both output (by 0.45 standard deviations) and attendance (by 18 percentage points), and undermines group cooperation.

## Introduction
Traditional economic models often assume that workers care primarily about their own wages. However, emerging research across economics, psychology, and sociology suggests that workers also compare their wages to those of coworkers. This study explores how relative pay impacts worker morale and productivity. The authors hypothesize that workers' responses to pay inequality are influenced by the perceived justification for wage differences—particularly when pay differences align with productivity disparities. The experiment contributes to understanding the conditions under which pay compression may emerge in labor markets.

## Institutional Background
The study was conducted among rural Indian manufacturing workers employed on short-term contracts during the agricultural lean season. Workers were assigned to production units with three members each and paid a daily wage for attendance, a common structure in the local labor market. To measure the effects of relative pay, each unit was assigned either an equal wage (compressed wage treatment) or differential wages based on baseline productivity rankings (pay disparity treatment). The experiment also included measures to assess social cohesion and cooperation among workers.

## Hypotheses
The study proposes two key hypotheses regarding the effects of pay inequality:

1. **Hypothesis 1**: Pay inequality reduces productivity and attendance when productivity differences between workers are less visible.
2. **Hypothesis 2**: Visible justifications for pay differences (i.e., clear productivity differences) mitigate the adverse effects of pay inequality on worker morale, productivity, and cohesion.

## Research Design
The field experiment involved randomly assigning workers to one of four wage structures within their production units:

- **Pay Disparity**: Workers received different wages ($w_{High}$, $w_{Med}$, or $w_{Low}$) based on their productivity ranking.
- **Compressed Low, Medium, and High**: All unit members received the same wage (either $w_{Low}$, $w_{Med}$, or $w_{High}$).

Workers' attendance and output were recorded daily, with production standardized across tasks. Each unit’s physical separation in the workspace was maintained, making peer comparison limited to unit coworkers. Additionally, two sources of variation (baseline productivity differences and task observability) were introduced to test perceived justifications.

### Regression Models
The main analysis uses a difference-in-differences model, comparing outcomes between pay disparity and compressed units. The basic model for output, $y_{it}$, is:

$$
y_{it} = \alpha_1 \left[ Post_t \times PayDispi \times Low_i \right] + \alpha_2 \left[ Post_t \times PayDispi \times Med_i \right] + \alpha_3 \left[ Post_t \times PayDispi \times High_i \right] + \lambda_i + \tau_t + \eta_1 x_{kt} + \eta_2 x_{kt}^2 + \epsilon_{it}
$$

- $y_{it}$: Worker $i$'s output on day $t$.
- $PayDispi$: Indicator for workers in the pay disparity condition.
- $Low_i$, $Med_i$, and $High_i$: Indicators for productivity rank within the unit.
- $\lambda_i$: Worker fixed effects.
- $\tau_t$: Day-round fixed effects.
- $\eta_1 x_{kt}$ and $\eta_2 x_{kt}^2$: Task-specific quadratic experience trends.

Additional models include controls for irrelevant workers and neighboring unit proximity.

### Variables
- **Attendance**: Binary measure indicating worker presence each day.
- **Output**: Standardized daily production measure.
- **Perceived Justification**: Binary indicators for high baseline productivity differences and task observability.

### Robustness Checks
The study includes several robustness checks:
1. **Control for Time Trends**: Fixed effects for days and rounds.
2. **Neighboring Units**: Controls for neighboring units' potential impact on behavior.
3. **Perceived Justifications**: Interaction models to test the mediating role of perceived justification for pay differences.

## Empirical Results
The results support both hypotheses:

1. **Effects of Pay Inequality on Output and Attendance**:
   - In units with pay disparity and low visibility of productivity differences, output decreased by 0.45 standard deviations, and attendance dropped by 18 percentage points.
   - High-rank workers in pay disparity units showed a similar decrease in attendance, suggesting potential discomfort with pay disparities, even when paid more.

2. **Role of Perceived Justifications**:
   - When productivity differences were substantial or tasks were observable, the negative effects of pay disparity on productivity and attendance were largely mitigated.
   - Workers were less likely to feel unfairly treated if they could clearly observe productivity differences justifying pay disparities.

3. **Social Cohesion and Cooperation**:
   - Workers in pay disparity units performed worse in cooperative games with their unit members than with “strangers” from other units, indicating decreased within-unit cohesion.
   - Endline survey data revealed fewer social ties among pay disparity workers, suggesting a potential breakdown in workplace relationships.

4. **Impact on Worker Well-being**:
   - Low-rank workers in pay disparity units were more likely to feel that wages were unfair. High-rank workers reported lower happiness despite higher pay, potentially due to social discomfort.

## Conclusion
The study finds that pay inequality, especially when perceived as unjustified, negatively affects worker morale, productivity, and social cohesion. These results highlight the importance of perceived fairness in workplace pay structures, as clear justifications for pay differences can help mitigate negative morale effects. The findings contribute to understanding why pay compression might be favored in some settings and illustrate how relative pay concerns influence labor supply and productivity.

## Limitations and Future Directions
The study does not account for dynamic incentive effects, as wages were fixed after the initial assignment. Future research could explore how relative pay concerns affect long-term productivity and career decisions, especially in contexts where performance-based wage adjustments are possible.