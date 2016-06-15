## Probability Grid Search

![](resources/prob1_clean.png)

note:
- Did a grid search to find best combination of join and leave probs
- Worst category has pretty high leave chance: nothing interesting there
- Best performers have high join chances, though the middle leave chance
  seems to be best.
  This can be explained by the tradeoff: You don't want to leave too quickly
  but you do want to leave if this is not going anywhere
- As a result of these findings did a search for the ideal join chance
  for a fixed leave chance
