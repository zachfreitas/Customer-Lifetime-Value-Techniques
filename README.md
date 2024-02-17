# Customer-Lifetime-Value-Techniques


## NPV Calculation
Summary of Metrics used to calculate Final NPV
\
\
$$\text{NPV} = \frac{\text{Total Cashflow}}{(1-\text{Discount Factor} * (1-\text{Avg. Mthly Churn Over Quarter}))}-\text{Total SAC}$$

\
\
\
Notes:\
$\text{Total Cashflow} = \text{Total Mthly ARPU} - \text{Total Mthly Variable Costs}$


Discount factor = <br>
$\huge df_{t} = \frac{1}{(1 + r_{t})^{t}}$<br>
$df_{t}:\text{discount factor at time }t$<br>
$r_{t}:\text{interest or risk rate at time }t$<br>