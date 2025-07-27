
# 3X3 Cube Solver

A dynamic and visually engaging Rubik's Cube solver application built using Python. This project includes features like custom scrambles, a 3D visualization using VPython, and automated solving mechanisms. Perfect for both Rubik's Cube enthusiasts and developers interested in exploring computational approaches to puzzle-solving.

---

## Features

- **3D Visualization**: Real-time 3D Rubik's Cube simulation powered by VPython.
- **Custom Scrambles**: Create and visualize your own scrambles.
- **Random Scrambles**: Generate random scrambles and visualize them.
- **Automated Solving**: Solve the cube using pre-defined algorithms, displayed step-by-step in the 3D environment.
- **Tkinter GUI**: User-friendly interface for cube control, scrambles, and solving.
- **Multiple Rotations**: Perform all standard cube moves (U, D, R, L, F, B) and rotations (x, y, z), along with their inverses.
- **Solve Algorithms**: Incorporates advanced solving techniques, including F2L (First Two Layers), OLL (Orientation of Last Layer), and PLL (Permutation of Last Layer).

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ShubhamAggarwal6105/3x3-CUBE-SOLVER.git
   cd 3x3-CUBE-SOLVER
   ```

2. **Install Required Libraries**
   Ensure you have Python installed, then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**
   Execute the main script to launch the application:
   ```bash
   python main.py
   ```

---

## Usage

### GUI Overview
1. **New Cube**: Resets the cube to its solved state.
2. **Shuffle**: Generates a random scramble and displays it on the cube.
3. **Custom Scramble**: Enter a custom scramble to visualize.
4. **Solve Cube**: Automatically solves the scrambled cube step-by-step.

### Command Execution
- Input standard cube moves (e.g., `U`, `R'`, `F2`) in the "Enter move(s)" field.
- Use the rotation buttons to rotate the entire cube in the 3D view.

### Features in Action
- Explore various solving techniques via the automated solving feature.
- Generate and study custom or random scrambles with ease.

---

## Code Highlights

- **3D Visualization**: Using VPython for a detailed and interactive rendering of the cube.
- **Move Execution**: Implements all standard moves and their inverses with real-time rotation animations.
- **Scrambling and Solving**:
  - Generates valid random scrambles.
  - Uses efficient solving algorithms for demonstration purposes.

---

## Contributions

Contributions are welcome! Feel free to fork the repository and create pull requests for any feature enhancements or bug fixes.

---

## Acknowledgements

- **VPython**: For enabling 3D visualization.
- **Tkinter**: For the user-friendly graphical interface.
