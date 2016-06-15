## Robustness

![](resources/robustness.png)

note:
- Chains are stateful, yet there are always robots walking in the way
- Everything is designed with timeout timers:
  a connection is maintained for X amount of time (up to 200 steps),
  then a timeout occurs and a _LEAVE_ signal gets sent.
  Everyone upstream propagates this forward and leaves as well.
- This timeout occurs in multiple scenarios: also happens during attachment
