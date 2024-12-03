## Mathable Score Calculator

The solution addresses the task of analyzing 200 images from 4 Mathable games, each consisting of 50 moves. During a round, players can make up to 7 moves, forming equations on the board to earn points. A round ends if no more moves are possible.

The objective is to:

- Task 1: Identify the position of the newly added piece on the board.
- Task 2: Recognize the number on the newly added piece.
- Task 3: Compute the score for each round corresponding to a player by summing earned points based on valid equations formed by the new piece placement in each move of the round.

## **Required Libraries**

To run the project, ensure the following libraries are installed:

```plaintext
opencv-python==4.10.0
matplotlib==3.9.2
numpy==2.0.1
```

You can install them using:

```
pip install -r requirements.txt
```

## **Usage Instructions**

1. Open the `mathable.ipynb` notebook.
2. Execute all cells sequentially.

### **Running all tasks**

- The final cell of the notebook calls the `run` function with two arguments:
  1. **input_folder_name:** Specifies the folder containing input files.
  2. **number_of_games:** Specifies how many games are present in the folder.

### **Output**

- The results are generated in the following directory:

```plaintext
  evaluare/fisiere_solutie/331_Rosu_Ana_Maria
```
