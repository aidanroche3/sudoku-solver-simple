# sudoku-solver-simple
- This program takes a Sudoku board in SMTLIB format and outputs the set of assertions needed to prove the satisfiability of the current board in SMTLIB format to be passed to the Z3 Sat Solver.

## Running the Project
- Install [Node.js](https://nodejs.org/en/download)
- Clone the repository to your local file system.
- Add the SMTLIB Formatted constraints to the /input/sudoku_in.txt file as raw text.
- Open the root folder, and open a terminal to that folder.
- Install Dependencies:
  ```sh
  npm i
  ```
- Run the program on the input file:
  ```sh
  npm start
  ```
- After the program outputs "Done!" in the terminal, you should expect the output file /output/sudoku_out.txt to contain the assertions needed to prove the satifiability of the current sudoku board in SMTLIB format, which can be passed directly into the Z3 Sat Solver.

- *Note - to run again, quit the existing terminal ```^C```, modify the input file as needed, and run ```npm start``` again.

## Authors
- [Aidan Roche](https://github.com/aidanroche3)
- [Ethan Moskowitz](https://github.com/EthanMoskowitz)
- [Ethan Szeto](https://github.com/ethanszeto)
