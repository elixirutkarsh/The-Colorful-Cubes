# The-Colorful-Cubes
Problem Statement:
There are five identical-looking cubes, each painted with a different color: red, blue, green, yellow, and purple. The cubes are arranged in a row, one behind the other, in a random order. The following clues are given:

The red cube is somewhere to the left of the green cube.
The blue cube is adjacent to the yellow cube.
The purple cube is not at either end of the row.
Your task is to determine the order of the cubes from left to right.

Solution:

Based on clue 2, the blue cube must be adjacent to the yellow cube. Therefore, they can only be in the following order: BY or YB.
According to clue 1, the red cube is somewhere to the left of the green cube. Since the red cube cannot be at the rightmost position, the possible arrangements are RYBG or YBRG.
Finally, clue 3 states that the purple cube is not at either end of the row. Thus, the only valid arrangement is RYBGP.
