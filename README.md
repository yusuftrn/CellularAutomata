
This swift demonstration is based on Conway's Game of Life algorithm.

![Gosper's Glider Gun](https://upload.wikimedia.org/wikipedia/commons/e/e5/Gospers_glider_gun.gif)

The Game of Life takes place on a 2-dimensional grid of cells, for example, like a pixel image. Each cell can be alive or dead. Every generation of the game, you determine which cells live on to the next generation. This happens based on the alive/dead state of the 8 neighbors of a cell, and 3 rules.

These rules, to be exact:

- A live cell with 2 or 3 live neighbours survives.
- A dead cell with 3 live neighbours becomes a live cell.
- All other live cells die in the next generation, and all other dead cells stay dead.

The description can be read here: https://en.wikipedia.org/wiki/Cellular_automaton

