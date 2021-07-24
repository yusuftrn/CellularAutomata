
This swift demonstration is based on Conway's Game of Life algorithm.

![Gosper's Glider Gun](https://upload.wikimedia.org/wikipedia/commons/e/e5/Gospers_glider_gun.gif)

image: wikipedia / cellular automaton

The Game of Life takes place on a 2-dimensional grid of cells, for example, like a pixel image. Each cell can be alive or dead. Every generation of the game, you determine which cells live on to the next generation. This happens based on the alive/dead state of the 8 neighbors of a cell, and 3 rules.

These rules, to be exact:

- Survivals: Every counter with two or three neighboring counters survives for the next generation
- Deaths: Each counter with four or more neighbors dies (is removed) from overpopulation. Every counter with one neighbor or none dies from isolation.
- Births: Each empty cell adjacent to exactly three neighbors -no more, no fewer- is a birth cell. A counter is placed on it at the next move.

The description can be read here: https://en.wikipedia.org/wiki/Cellular_automaton

