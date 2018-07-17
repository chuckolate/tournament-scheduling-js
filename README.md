# tournament-scheduling-js

These folder contains multiple javascript tournament scheduling algorithms.

As for round robin algorithm, you can enter between 2 to 16 teams, as well as the number of rounds desired (with no limit). Teams are designated with integer values starting from 0. Both of these fields work for even and odd numbers of team/rounds.

As for single seed elimination, you can enter between 2 to 64 teams. This algorithm places the top seeded team against the lowest seeded team. The teams are designated by integer values starting with the highest of 100 and then incremented from there.

As for playoffs, this algorithm so far only accepts 4/8/16/32/64 teams. As usual, the teams are assigned integer values. with each round, the number of teams is divided by two. I used a function to randomize the win/lose status of each team so that by the end of the tournament, there is only one winner.