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
`data = [[5, 3, 4, 6, 7, 8, 9, 1, 2, 8, 9, 1, 2, 8, 9, 1, 2],[6, 7, 2, 1, 9, 5, 3, 4, 8, 8, 9, 1, 2, 8, 9, 1, 2],[1, 9, 8, 3, 4, 2, 5, 6, 7, 8, 9, 1, 2, 8, 9, 1, 2],[1, 9, 8, 3, 4, 2, 5, 6, 7, 8, 9, 1, 2, 8, 9, 1, 2],[8, 5, 9, 7, 6, 1, 4, 2, 3, 8, 9, 1, 2, 8, 9, 1, 2],[4, 2, 6, 8, 5, 3, 7, 9, 1, 8, 9, 1, 2, 8, 9, 1, 2],[7, 1, 3, 9, 2, 4, 8, 5, 6, 8, 9, 1, 2, 8, 9, 1, 2],[1, 9, 8, 3, 4, 2, 5, 6, 7, 8, 9, 1, 2, 8, 9, 1, 2],[9, 6, 1, 5, 3, 7, 2, 8, 4, 8, 9, 1, 2, 8, 9, 1, 2],[2, 8, 7, 4, 1, 9, 6, 3, 5, 8, 9, 1, 2, 8, 9, 1, 2],[3, 4, 5, 2, 8, 6, 1, 7, 9, 8, 9, 1, 2, 8, 9, 1, 2],[1, 9, 8, 3, 4, 2, 5, 6, 7, 8, 9, 1, 2, 8, 9, 1, 2],[9, 6, 1, 5, 3, 7, 2, 8, 4, 8, 9, 1, 2, 8, 9, 1, 2],[2, 8, 7, 4, 1, 9, 6, 3, 5, 8, 9, 1, 2, 8, 9, 1, 2],[3, 4, 5, 2, 8, 6, 1, 7, 9, 8, 9, 1, 2, 8, 9, 1, 2],[1, 9, 8, 3, 4, 2, 5, 6, 7, 8, 9, 1, 2, 8, 9, 1, 2]]`
