# CS576-Tetris-Sample

This version of Tetris expanded on the cloned repo by adding the option for the enemy to swap pieces with the player. 

The decision to swap is built into the original logic as an additional option in the array. It also accounts for looking ahead by 2 moves, so there is an option of ....
1. 2 left moves
2. 2 right moves
3. rotate and left
4. rotate and right
5. swap and left
6. swap and right

Regardless of if the "best" move is 2 moves away, the enemy still only chooses one action per update.