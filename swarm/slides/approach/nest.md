## Nest

![](resources/nest.png)

note:
- The first one to exist becomes the nest beacon (only ever 1)
- All chains start at the nest
- Nest takes some time to calibrate its orientation:
  away from the grey area and perpendicular to the walls.
- This is the only part of the code that is specific to the scenario
  definition: needed some place to start building from.
  Alternative is to not have the nest calibrate but it becomes
  a lot less powerful, though it's an approach that would still work,
  just impede efficiency.
