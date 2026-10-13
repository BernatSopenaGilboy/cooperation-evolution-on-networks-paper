# Evolution of cooperation on graphs: reproduction and extension (2019)

Course project (MCS), June 2019, by Dimitris Dineff and Bernat Sopena Gilboy.

**Paper (PDF):** [cooperation-on-graphs-reproduction-and-extension.pdf](cooperation-on-graphs-reproduction-and-extension.pdf)

## What this is

1. **Reproduction** of Ohtsuki, Hauert, Lieberman and Nowak (2006), *A simple rule for the evolution of cooperation on graphs and social networks*, Nature 441, 502-505: death-birth dynamics of a prisoner's dilemma on cycles, lattices, random regular graphs, random graphs and scale-free networks, plus small-world networks.
2. **Extension** to adaptively weighted networks: individuals update the strength of their ties according to the payoffs they receive. A mean-field analysis and simulations show how the ratio of the weight-update rate to the strategy-update rate (delta) controls the spread of cooperation. Take-away: punish defectors by weakening ties, but not too hard.

## Code

Research prototype in MATLAB, written under time pressure in 2019 (not polished): [SaucePan1/final_MCS](https://github.com/SaucePan1/final_MCS/). Graph generators, the death-birth simulation, fixation-probability estimation and the weighted-network extension live in `resources/project/`.

## Note on compute

Simulations in the paper took more than 140 hours spread over 9 computers, so some figures use a cheaper proxy for the fixation probability (see footnote 18 of the paper).
