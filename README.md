# 🐢 Turtle Racing Game

A simple and fun **Turtle Racing Game** built using Python's built-in `turtle` module.

The user can select between **2 and 10 racers**. Each turtle is given a random movement distance during the race. The first turtle to reach the finish line wins.

## 📌 Features

* 🐢 Supports 2 to 10 racers
* 🎨 Different colors for each turtle
* 🎲 Random movement for each racer
* 🏁 Automatically detects the winner
* 🖥️ Uses Python Turtle Graphics
* 🔄 Input validation for the number of racers

## 🛠️ Technologies Used

* Python
* Turtle module
* Random module
* Time module

## 📂 Project Structure

```text
turtle-racing-game/
│
├── main.py
└── README.md
```

## 🚀 How to Run the Project

### 1. Install Python

Make sure Python is installed on your computer.

Check your Python version:

```bash
python --version
```

or:

```bash
python3 --version
```

### 2. Clone the Repository

Clone this repository using:

```bash
git clone https://github.com/aanak30/turtle-racing-game.git
```

### 3. Open the Project

Move into the project directory:

```bash
cd turtle-racing-game
```

### 4. Run the Game

Run the Python file:

```bash
python main.py
```

If your system uses `python3`:

```bash
python3 main.py
```

## 🎮 How to Play

When the program starts, it asks:

```text
Enter the number of racers (2-10):
```

Enter a number between **2 and 10**.

For example:

```text
Enter the number of racers (2-10): 5
```

The game will create five turtles with different colors.

Each turtle moves forward by a random distance.

The first turtle to reach the finish line wins.

Example output:

```text
The winner is the turtle with color : blue
```

## 🧠 How the Program Works

The project is divided into four main functions.

### `get_number_of_racers()`

Gets the number of racers from the user and checks that the number is between 2 and 10.

### `init_turtle()`

Creates and configures the Turtle graphics window.

### `create_turtles(colors)`

Creates the turtles, assigns their colors, and places them at their starting positions.

### `race(colors)`

Runs the race by moving each turtle a random distance and checking whether a turtle has reached the finish line.

## 📚 Python Concepts Used

This project demonstrates several important Python concepts:

* Functions
* Lists
* Loops
* Conditional statements
* User input
* Type conversion
* Random numbers
* List indexing
* `enumerate()`
* `append()`
* Turtle graphics

## 🔮 Future Improvements

Possible improvements for the project:

* Add a visible finish line
* Add a race countdown
* Display the winner inside the Turtle window
* Add sound effects
* Add a restart button
* Add a scoreboard
* Track multiple race results
* Add player names
* Improve the graphical design

## 👩‍💻 Author

**Your Name**

GitHub: `https://github.com/aanak30`

## 📄 License

This project is created for learning and educational purposes.
