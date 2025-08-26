# egg-cooking

Simulate the cooking of an egg.

This app is based on the research of periodic cooking of eggs [[1]](#1).
However, their study employs a finite element method while the model used here is ODE-based.

Open `index.html` in a web browser and configure:

- **Total time** for the simulation.
- **Water temperature profile**: choose a constant temperature or specify a time
  schedule using pairs of `time,temperature` values.

The app implements a two-zone lumped heat transfer model to simulate egg
cooking. It tracks both the albumen and yolk temperatures, along with their
denaturation (cooking degree), using simple energy balances combined with
Arrhenius kinetics. After running, two charts display the temperature profiles
and cooking progression over time. In this lumped formulation, the albumen
temperature and cooking degree correspond approximately to the values a little
less than 20 mm from the center, while the yolk values correspond to those at
about 10 mm from the center, as reported in [[1]](#1).

## References
<a id="1">[1]</a> Di Lorenzo, E., Romano, F., Ciriaco, L. *et al.* Periodic cooking of eggs. *Commun Eng* **4**, 5 (2025). https://doi.org/10.1038/s44172-024-00334-w
