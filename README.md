# RP Dice Roller

RP Dice Roller is a small Python app that simulates dice rolling events. This code supplements the article [Build a Dice-Rolling Application With Python](https://realpython.com/python-dice-roll/) on realpython.com.

## Running RP Dice Roller

The project's code was tested with Python 3.9.5. However, it should work with any Python versions greater than or equal to 3.6. There are no external dependencies. To run the project's code, execute the following command with the appropriate Python interpreter:

```sh
$ python dice.py
How many dice do you want to roll? [1-6] 5

​~~~~~~~~~~~~~~~~~~~~~~~~~ RESULTS ~~~~~~~~~~~~~~~~~~~~~~~~~
┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐
│  ●   ●  │ │  ●      │ │  ●   ●  │ │  ●   ●  │ │         │
│    ●    │ │         │ │    ●    │ │    ●    │ │    ●    │
│  ●   ●  │ │      ●  │ │  ●   ●  │ │  ●   ●  │ │         │
└─────────┘ └─────────┘ └─────────┘ └─────────┘ └─────────┘
```

The application prompts the user for the number of dice they want to roll and generates a dice faces ASCII diagram with the results.

Each folder in this repository contains the code for the corresponding step in the companion article in a file called `dice.py`.

## Next Steps 

Now that you’ve finished building your dice-rolling application, you can take the project a step further by adding new functionality. Adding new features by yourself will help you continue to learn exciting new coding concepts and techniques.

Here are some ideas to take your project to the next level:

- **Support for any number of dice:** Modify the code so that you can roll any number of dice.
- **Support for dice with different numbers of faces:** Add code to support not only six-sided dice but dice with any number of sides.

The first feature will require you to modify the code that processes the user’s input for the number of dice to roll. You’ll also need to modify the code that generates and displays the diagram of dice faces. For example, you can generate a diagram that displays the dice faces in several rows to avoid cluttering your screen with cramped output.

On the other hand, supporting dice with a different number of faces will demand that you tweak the code that simulates a dice-rolling event. You’ll also need to create new ASCII art for any dice with more than six faces.