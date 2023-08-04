# Sort-Doku: A New Spin on Sudoku 🌀

Welcome to Sort-Doku, an innovative take on the classic puzzle game Sudoku! By introducing a simple twist—interchangeability of Sudoku elements—we uncover a whole new dimension of gameplay and mathematical fascination.

## The Premise 🎯

The central idea behind Sort-Doku is the introduction of 'exchangeable properties'. In a classic [Sudoku](https://en.wikipedia.org/wiki/Sudoku), numbers are fixed; once a 5 is placed, it remains a 5. But what if we could swap all the 5s with 4s, or rotate the entire puzzle 90 degrees? What if we could rearrange the larger columns and move smaller columns within their larger bounds? 🔄

Sort-Doku enables exactly this—making Sudoku not only a game of logic but a dynamic puzzle that evolves as you play. This leads to a significant reduction in the number of states a Sudoku game can have, theoretically bringing us closer to achieving a 'total order'.

## Total Order 📈

In Sort-Doku, the concept of '[total order](https://en.wikipedia.org/wiki/Total_order)' pertains to arranging the Sudoku grid's elements such that they adhere to a predefined sequence or pattern. Achieving a 'total order' means we have 'sorted' the Sudoku into its most ordered state. 

### State Reduction 🔄

In the context of Sort-Doku, state reduction happens through the interchangeability rules. By allowing numbers or blocks to be swapped or rotated, we effectively reduce the number of unique game states. This introduces a whole new dimension of strategy into the game: players can now manipulate the game state to reduce complexity, potentially making the puzzle easier to solve.

### Graphs and Coloring 🎨

A Sudoku puzzle can be viewed as a graph where each cell represents a node, and nodes are connected if they are in the same row, column, or box. '[Coloring](https://en.wikipedia.org/wiki/Graph_coloring)' in graph theory is like solving a Sudoku puzzle, with the added complexity in Sort-Doku that the 'colors' (numbers) are no longer static but can be swapped. This adds a new strategic depth to the game.

## The Project Goals 🏁

Sort-Doku focuses on two major aspects:

- **Analysis:** Through this project, we aim to explore and understand the implications of these interchangeability rules on Sudoku's combinatorial complexity. By doing so, we hope to shed light on new perspectives and insights into this timeless puzzle game.

- **Interactive Gameplay:** In addition to the analysis, we're also building an interactive Sudoku game. As you fill in the numbers, the game board will animate and sort itself into the 'total order' state. It's not just a game; it's a spectacle in itself! 🎆

## Get Involved! 🙌

If you're a fan of Sudoku or just intrigued by this unique twist on it, we invite you to contribute! Whether it's working on the game logic, enhancing the user interface, or diving deep into the mathematical analysis, there's plenty to do. Let's together unravel the mysteries of Sort-Doku! 💫

To get started:

1. Clone the Repository: `git clone https://github.com/bdelanghe/sort-doku.git`
2. Navigate to the project directory: `cd sort-doku`
3. Have a look at the project issues for possible contribution points

Remember, every Sudoku you solve brings us one step closer to solving the riddle of Sort-Doku! Let's embark on this exciting journey together! 🎲🚀🌈
