## State Overview

![](resources/highlevel.png)

note:
- Every robot starts in *Search*
- Once unf chain is found, Explore
- Explore: make your way towards end, then explore in vicinity of tail
- If at end and with prob, become the new tail
- Attach is an optimization state, large enough to deserve its own
- 

- There are exceptions to all of this, it's only highlevel depiction
