# Percentage Paradox

With this piece, I aim to theorise a paradox that many are aware of, yet one without a formal term assigned to it. Formalising it will allow us to use it in models of profit/loss, risk and compounding. Titling such a phenomenon 'Percentage Paradox' seemed fitting.

#### Second-order effects

Second-order effects are the indirect consequences that result from an initial event. These effects are often less obvious and may not be immediately noticeable, as they emerge from the chain reaction set in motion by the direct first-order effects.

##### *Example: The discovery and widespread use of antibiotics.*

*First-Order Effect*: Many previously lethal diseases can now be cured quickly and easily, drastically reducing death rates.

*Second-Order Effect*: Over time, bacteria evolve to become resistant to these antibiotics, leading to the emergence of "superbugs" that are extremely difficult to treat. This was not anticipated when antibiotics were first introduced.

Second order effects in numerical value changes - the direct impact of a positive change and a negative change might seem to have the same absolute impact in opposite directions, yet, as you will see, their impact varies.

## The Paradox

The phenomenon I am referring to is the difference in (1) the second order effects of a negative change and (2) the second order effects of a positive change - even when the changes are the same in absolute terms.

When a principal amount decreases by a certain amount, it takes a larger percentage change to return to the original amount as compared to when the principal amount increases - when there’s an increase, a smaller percentage change is needed to return to the original amount. This asymmetry is due to the changing base/principal on which subsequent percentage changes are calculated.

Three truths that allow us to classify this phenomenon as a paradox:
1. In absolute terms, the values hold the same weight, just in the opposite direction.
2. In absolute terms, a negative change (eg. -1) is by definition lesser than (<) an equivalent positive change (eg. +1).
3. The impact of both changes varies.

Let's consider an equal interval of changes in both directions to demonstrate the required subsequent changes to return to the principal.

Table 1: Negative percentage changes followed by their respective percentage changes required to return to the principal.

| Loss (%) | Required Gain (%) |
| -------- | ----------------- |
| 10%      | 11.11%            |
| 20%      | 25.00%            |
| 30%      | 42.86%            |
| 40%      | 66.67%            |
| 50%      | 100.00%           |
| 60%      | 150.00%           |
| 70%      | 233.33%           |
| 80%      | 400.00%           |
| 90%      | 900.00%           |

To explain how these numbers were calculated - Let's assume a principal of 100. If there's a 10% loss, the original value becomes 90. To get back to 100 from 90, it needs to gain approximately 11.11%. Similarly, for a 20% loss, the value becomes 80 and it needs to gain 25% to reach 100, and so on. This can seem counterintuitive, but it occurs due to the fact that when the base value decreases, the same absolute increase represents a larger percentage of the new, smaller base value.

Table 2: Positive percentage changes followed by their respective percentage changes required to return to the principal.

| Gain (%) | Required Loss (%) |
| -------- | ----------------- |
| 10%      | 9.09%             |
| 20%      | 16.67%            |
| 30%      | 23.08%            |
| 40%      | 28.57%            |
| 50%      | 33.33%            |
| 60%      | 37.50%            |
| 70%      | 41.18%            |
| 80%      | 44.44%            |
| 90%      | 47.37%            |

Similar to the calculations of the previous table - if there's a 10% gain, the original value becomes 110. To get back to 100 from 110, it needs to lose approximately 9.09%. Similarly, for a 20% gain, the value becomes 120 and it needs to lose 16.67% to reach 100, and so on.

### Proof

In mathematical terms, the second-order impact of a percentage change refers to the subsequent change required to return to the original value.

Let's consider a principal amount P.

1. If there is a negative 10% change in P, the new amount P' is:

P' = P - 0.10P  
P' = 0.90P

To return to the original amount P, the percentage change (A) needed on P' is calculated as:

A = (P - P') / P'  
A = (P - 0.90P) / (0.90P)  
A = (0.10P) / (0.90P)  
A = 0.1111 or approximately 11.11%

This shows that a negative 10% change requires an approximately 11.11% increase to return to the original principal.

2. If there is a positive 10% change in P, the new amount P' is:

P' = P + 0.10P  
P' = 1.10P

To return to the original amount P, the percentage change (A) needed on P' is calculated as:
‍
A = (P - P') / P'  
A = (P - 1.10P) / (1.10P)  
A = (-0.10P) / (1.10P)  
A = -0.0909 or approximately -9.09%

This indicates that a positive 10% change requires an approximately 9.09% decrease to return to the original principal.
So, even though -10% and +10% are the same in absolute terms, a negative 10% change has a greater second-order impact on the principal amount as it requires an approximately 11.11% increase to return to the original principal, compared to the 9.09% decrease required after a positive 10% change. This asymmetry results from the changing base amount (P') on which the percentage change is calculated.

### Conclusion

While some might credit such a phenomenon to a calculation discrepancy (where subsequent percentage changes are calculated with a new base value every time), it is actually the result of a change in initial state leading to a new value - the second order effect - which the 'calculation discrepancy' accounts for accurately.

It is proven that a negative change on an amount has a greater second order effect than its equivalent positive change.

I.e. the effort required to return an amount to its principal is far greater when there's a loss than when there's a gain.

For example - as an investor, it is far more important to not lose money, than to gain money.
