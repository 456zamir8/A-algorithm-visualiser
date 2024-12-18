# A-algorithm-visualiser
## Overview
This project is a Python-based visualizer for the A* pathfinding algorithm. It allows users to interactively explore how the algorithm finds the shortest path between two points in a grid-based environment. The tool is designed to be educational, visually engaging, and user-friendly.
## Features
- **Interactive User Interface**
- **Customizable Grid**
- **Real-Time Visualization**
- **Adjustable Parameters**
## Technologies Used
- **Python**
- **Python**
- **Tkinter**
- **PriorityQueue (for managing open nodes)**
- **Time (for visualization timing)**
- **Math (for heuristic calculations)**
## How it works
1. **Grid Setup**: Users interactively create a grid, placing start and end points, and adding obstacles.
2. **Algorithm Execution**: The A* algorithm calculates the shortest path by:
   - Maintaining an open list of nodes to explore.
   - Using a heuristic to prioritize nodes.
   - Traversing nodes until the shortest path is found.
3. **Visualization**: Nodes are highlighted in real-time to show the exploration process.
## Installation
1. **Clone the repository:**
```
git clone https://github.com/your-username/a-star-visualizer.git
```
2. **Navigate to the project directory:**
```
cd a-star-visualizer
```
3. **Install dependencies:**
```
pip install pygame
```
## Usage
1. **Run the script:**
```
python A-star visualizer.py
```
2. **Interact with the grid:**
   - Left-click to place start, end, or obstacle nodes.
   - Right-click to remove nodes.
   - Press the spacebar button to start the algorithm.
## Controls
- **Mouse:** Add or remove nodes.
- **Keyboard:** Reset grid or adjust parameters (based on Tkinter input fields).
## Contributions
Contributions are welcome! Feel free to fork the repository and submit pull requests.
