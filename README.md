# Switch-or-Die-Game

This project simulates a classic logic puzzle where you need to determine which of three switches controls a light bulb located in another room. The simulation is built using Python and [SimPy](https://simpy.readthedocs.io/), a process-based discrete-event simulation framework.

## Game Description

You are presented with **three switches**: `A`, `B`, and `C`. Only one of them controls a bulb in a separate room. You can **turn ON and OFF** these switches and **observe the bulb** to figure out which one is correct.

### Gameplay Mechanics

* Only one switch is active at a time.
* The bulb glows when the correct switch is ON.
* You have **60 seconds** to determine the correct switch.
* The system tracks how long each switch is ON.
* Once you are ready, you can make a **final guess**.

## Requirements

* Python 3.6+
* `simpy` library

Install dependencies using:

```bash
pip install simpy
```

## How to Run

1. Open the Jupyter Notebook:
   `Code.ipynb`

2. Run the cells sequentially to:

   * Initialize the simulation
   * Play the game (through input prompts)
   * Make your final guess

3. Observe the feedback after your final guess.

## Technologies Used

* Python
* SimPy (Discrete-event simulation)
* Random module
* Time module

## License

This project is licensed under the MIT License.

## Author

Developed by Harsh Arora.
