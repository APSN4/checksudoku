# Check Sudoku Python

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=Let's+check+your+Sudoku+for+validity)](https://git.io/typing-svg)

(Install in Python: `pip install checksudoku`)

![ezgif-5-fa41583a1f](https://user-images.githubusercontent.com/45320521/196675485-72062881-ce17-45cb-a974-3174e7a59c1d.gif)

# Input Data
Input `сsudoku(data)` data is a two-dimensional array of numbers from 1 to n.
Example:  

![аннотация_2022-10-19_135800 dErTU](https://user-images.githubusercontent.com/45320521/196678717-331c6cc4-172b-4379-9774-d2286bcd36f4.png)

# Output Data
The checksudoku returns `True` if the sudoku matches the rules of the game, and `False` if the sudoku does not match the rules

checksudoku also returns an error in the form of `print()`, example: `[Error] [1, 2, 2, 3, 4, 5, 6, 7, 8, 9]` . From this example, it can be seen that the string does not match the conditions of the game (the number "2" is repeated twice)

# Example of input data for verification
Sudoku 9x9:  
`data = [[5, 3, 4, 6, 7, 8, 9, 1, 2],[6, 7, 2, 1, 9, 5, 3, 4, 8],[1, 9, 8, 3, 4, 2, 5, 6, 7],[8, 5, 9, 7, 6, 1, 4, 2, 3],[4, 2, 6, 8, 5, 3, 7, 9, 1],[7, 1, 3, 9, 2, 4, 8, 5, 6],[9, 6, 1, 5, 3, 7, 2, 8, 4],[2, 8, 7, 4, 1, 9, 6, 3, 5],[3, 4, 5, 2, 8, 6, 1, 7, 9]]`

Sudoku 16x16:  
`data = [[4,8,2,3,9,7,15,14,10,5,16,11,13,12,6,1],[1,5,11,9,6,10,12,16,7,13,8,3,15,14,2,4],[16,12,10,6,5,3,1,13,2,15,14,4,9,11,8,7],[13,15,7,14,2,8,4,11,9,12,1,6,16,10,5,3],[2,6,12,7,4,13,10,15,8,1,11,16,5,3,9,14],[8,3,15,10,14,11,7,2,13,9,6,5,12,4,1,16],[5,4,16,1,12,9,6,8,14,10,3,2,7,15,13,11],[11,14,9,13,3,16,5,1,15,4,12,7,2,6,10,8],[15,16,3,5,1,4,14,10,12,6,9,13,11,8,7,2],[7,9,14,2,16,15,3,5,1,11,4,8,6,13,12,10],[12,13,1,11,8,6,2,7,3,16,15,10,4,9,14,5],[6,10,4,8,13,12,11,9,5,7,2,14,3,1,16,15],[10,11,5,12,15,1,8,6,4,2,7,9,14,16,3,13],[9,2,13,4,11,14,16,3,6,8,5,1,10,7,15,12],[3,7,8,15,10,2,9,4,16,14,13,12,1,5,11,6],[14,1,6,16,7,5,13,12,11,3,10,15,8,2,4,9]]`
