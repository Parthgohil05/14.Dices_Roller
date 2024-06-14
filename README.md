# Digital Dice Simulator

## Overview
This project is a simple digital dice simulator implemented in Python. The program simulates the rolling of a six-sided die and displays the result in a graphical representation using text characters.

## Features
- Simulates the rolling of a six-sided die.
- Graphically displays the result of each roll.
- Allows the user to roll the die multiple times.

## Requirements
- Python 3.x

## Usage
1. Ensure you have Python 3.x installed on your system.
2. Copy the code provided below into a Python script file (e.g., `dice_simulator.py`).
3. Run the script using a Python interpreter.

## Code

```python
import random

print("This is a digital dice simulator")
x = "y"
while x == "y":
    number = random.randint(1, 6)

    if number == 1:
        print("===========")
        print("|         |")
        print("|    O    |")
        print("|         |")
        print("===========")

    elif number == 2:
        print("===========")
        print("|         |")
        print("| O     O |")
        print("|         |")
        print("===========")

    elif number == 3:
        print("===========")
        print("|    O    |")
        print("|    O    |")
        print("|    O    |")
        print("===========")
        
    elif number == 4:
        print("===========")
        print("| O     O |")
        print("|         |")
        print("| O     O |")
        print("===========")
        
    elif number == 5:
        print("===========")
        print("| O     O |")
        print("|    O    |")
        print("| O     O |")
        print("===========")
        
    elif number == 6:
        print("===========")
        print("| O     O |")
        print("| O     O |")
        print("| O     O |")
        print("===========")
    
    x = input("Press y to roll again ")
```

## How to Run
1. Open a terminal or command prompt.
2. Navigate to the directory where your script is saved.
3. Run the script with the following command:
   ```
   python dice_simulator.py
   ```
4. Follow the on-screen prompts to roll the die. Press 'y' and hit enter to roll again, or any other key to exit.

## License
This project is licensed under the MIT License.

## Acknowledgements
- This project uses Python's built-in `random` module to generate random numbers for the dice roll.
