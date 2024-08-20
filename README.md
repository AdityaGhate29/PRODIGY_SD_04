# Sudoku Solver🧩
Sudoku is a logic-based puzzle that involves placing numbers in a 9x9 grid to solve a constraint satisfaction problem. The puzzle is divided into nine 3x3 boxes, also called regions, blocks, or boxes. The goal is to fill the grid so that each row, column, and box contains the numbers 1–9 without repeating any numbers. The puzzle setter provides a partially completed grid with a single solution. 

This is a web-based Sudoku Solver built using HTML, CSS, and JavaScript. The solver can take any standard 9x9 Sudoku puzzle as input, validate the board, and solve it. The project also includes features to clear the board and handle invalid inputs.

## Features

- **Solve Sudoku Puzzles:** Automatically solves any 9x9 Sudoku puzzle.
- **Clear Board:** Clears the board to allow for a new puzzle.
- **Input Validation:** Ensures only valid numbers (1-9) are entered into the cells.

## Demo
Screenshots:

![Screenshot 2024-08-20 175131](https://github.com/user-attachments/assets/ecbfb96b-7959-46aa-9bd7-18ba932317ed)

![Screenshot 2024-08-20 175307](https://github.com/user-attachments/assets/ad4bca34-6898-4da7-b0a3-b60dd4aa7fc7)

![Screenshot 2024-08-20 175326](https://github.com/user-attachments/assets/ae975844-cc2f-4fe4-86f3-7ed38a2134ec)

![Screenshot 2024-08-20 180035](https://github.com/user-attachments/assets/e0d94be5-937f-4c1b-a4a4-826f903dc8a9)



## How It Works

- **User Interface:** The board is a 9x9 grid where users can input the numbers for their Sudoku puzzle.
- **Solver Logic:** The core solving algorithm is implemented in JavaScript, utilizing a backtracking approach to fill in the board.
- **Input Handling:** The script ensures that only valid numbers are entered, and the grid cells are automatically updated when the puzzle is solved.

## Getting Started

### Prerequisites

You will need a modern web browser to run this project. No additional software is required.

### Running the Project

1. Download zip file of code and open it in VS code or any of your code editor. 
2. Navigate to the project directory and open the index.html file in your web browser.
3. Then right click in index.html file click show preview or open in live server in your browser.

### Solve a Sudoku Puzzle:

Enter your Sudoku puzzle into the grid, and click the "Solve" button. The solution will be displayed on the board.

## Project Structure
index.html: The main HTML file that contains the structure of the webpage.
sudoku.js: The JavaScript file containing the Sudoku solving logic and board manipulation functions.
style.css: The CSS file for styling the Sudoku board and page layout.
sudoku.png: An optional image used in the project, such as a logo or banner.
Example Puzzles
Here are some example puzzles to test the solver:

Easy Puzzle: 1-58-2----9--764-52--4--819-19--73-6762-83-9-----61-5---76---3-43--2-5-16--3-89--
Medium Puzzle: -3-5--8-45-42---1---8--9---79-8-61-3-----54---5------78-----7-2---7-46--61-3--5--
Hard Puzzle: 8----------36------7--9-2---5---7-------457-----1---3---1----68--85---1--9----4--
Contributing
If you have suggestions for improvements or want to report a bug, feel free to open an issue or submit a pull request. Contributions are always welcome!


## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
If you have any questions or feedback, feel free to reach out:

GitHub: AdityaGhate29

Email: adityaghate29@gmail.com
