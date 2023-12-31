# Restricted-Tower-of-Hanoi
The Restricted Tower of Hanoi is a classic mathematical puzzle/game that consists of three rods and a set of different-sized disks. The objective of the game is to move the entire stack of disks from one rod to another, adhering to the following rules:

1. Only one disk can be moved at a time.
2. Each move consists of taking the top disk from one of the stacks and placing it on top of another stack or an empty rod.
3. No disk may be placed on top of a smaller disk.
   
The problem is to determine the minimum number of moves required to solve the Tower of Hanoi puzzle, given the number of disks initially placed on the starting rod and the configuration of the rods. The goal is to move all the disks to the destination rod, using the intermediate rod as necessary.

The problem statement can be formulated as follows:

Given: The number of disks, N, initially placed on the starting rod. The configuration of the three rods: the starting rod, the destination rod, and the intermediate rod.

Find: The minimum number of moves required to transfer all the disks from the starting rod to the destination rod, following the rules of the Tower of Hanoi game.

Constraints:

1. The number of disks, N, is a positive integer.
2. The configuration of the rods is valid, meaning the disks are initially placed in decreasing order of size on the starting rod, and the other two rods are 
   empty.
