# Game-of-Life
A generative system displaying different patterns based on Conway life of game rules
Game of Life happens on a grid, and at each location on the grid we can have a cell that
is either alive or dead. If it’s alive, we color it so we can see it. If it’s dead, it’s just transparent.
Our Game of Life universe successively computes new generations of cells,
and to do that it applies the four rules to every location in the grid, after
which it updates all the cells at once, based on the outcome. It then does this
over and over and over, computing new generations.
