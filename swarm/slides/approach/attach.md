## Attachment

![](resources/angles.png)

note:
- Red is current tail
- Blue wants to attach
- Should make ideal angle, at least 120 degrees
- Red constantly shouts ideal angles to the next one, along with corresponding alpha
- Blue remembers beta and alpha and uses these to calculate gamma, angle to turn
- Blue turns, then drives towards the white goal
- Blue knows when he's at the goal because the angle difference has changed sign
- As soon as blue has moved to correct position,
  he moves straight away from the previous one
- Does this until contact is broken, then moves back a little
- This way distance is always optimized

- This is really robust: If anything happens, the procedures starts over again
- This is possible because red picks a new beta every step, blue just remembers 
