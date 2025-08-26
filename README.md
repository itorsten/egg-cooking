# egg-cooking

Simulate the cooking of an egg.

Open `index.html` in a web browser and configure:

- **Total time** for the simulation.
- **Water temperature profile**: choose a constant temperature or specify a time
  schedule using pairs of `time,temperature` values.

The app solves a physical two-zone heat transfer model. It tracks the
albumen and yolk temperatures and their denaturation (cooking degree) based
on simple energy balances and Arrhenius kinetics. After running, two charts
display the temperatures and cooking progression over time.
