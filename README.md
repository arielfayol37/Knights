# Knights and Knaves Logic Puzzles

Welcome to the Knights and Knaves logic puzzles! In these puzzles, you will encounter characters who are either knights or knaves. Knights always tell the truth, while knaves always lie. Your objective is to determine the true identity (knight or knave) of each character based on the sentences they speak.

Furthermore, you could use the same principles to solve other custom puzzles of your own!

## Representing Puzzles Using Propositional Logic

In this project, we use propositional logic to represent the information provided by the characters. The logic is implemented in `logic.py`, which contains classes for different logical connectives. The function `model_check` in the same file utilizes model-checking to determine whether a knowledge base entails a query.

## Puzzle Descriptions

We have four puzzles (Puzzle 0 to Puzzle 3), each with different characters and statements.

### Puzzle 0
- Character: A
- Statement: A says "I am both a knight and a knave."

### Puzzle 1
- Characters: A and B
- Statements:
  - A says "We are both knaves."
  - B says nothing.

### Puzzle 2
- Characters: A and B
- Statements:
  - A says "We are the same kind."
  - B says "We are of different kinds."

### Puzzle 3
- Characters: A, B, and C
- Statements:
  - A says either "I am a knight." or "I am a knave.", but you don't know which.
  - B says "A said 'I am a knave.'"
  - B then says "C is a knave."
  - C says "A is a knight."

## Solving the Puzzles

For each puzzle, the knowledge bases (knowledge0, knowledge1, knowledge2, and knowledge3) which have been filled with knowledge bases with the corresponding puzzle.
You can extend the same ideas to solve other puzzles.

## How to Use

1. Clone this repository to your local machine using `git clone`.

2. Navigate to the project directory.

3. Run the script by executing `python puzzle.py`.

4. Observe the solutions to the puzzles and enjoy the logic-solving challenge!

## Notes

- Each character in the puzzles is either a knight or a knave.
- Sentences spoken by knights are true, and sentences spoken by knaves are false.
- The model-checking algorithm will deduce the true identities of the characters.


## License

This project is open-source and released under the [MIT License](https://opensource.org/licenses/MIT).

Prepare to exercise your logic skills! Solve the Knights and Knaves puzzles and unveil the true identities of the characters. Have fun! 🎲🤺
