AI/ML Search Algorithms
Overview
This repository contains a collection of search algorithms used in Artificial Intelligence (AI) and Machine Learning (ML) applications. These algorithms are designed to find optimal solutions to complex problems by navigating through vast search spaces efficiently.

Features
Uninformed Search Algorithms:
Breadth-First Search (BFS)
Depth-First Search (DFS)
Informed Search Algorithms:
Greedy Search
A* Search
Local Search Algorithms:
Hill Climbing
Simulated Annealing
ML-based Search Algorithms:
Reinforcement Learning (RL) for search
Technologies
Language: Python
Libraries: NumPy, SciPy, scikit-learn
Installation
Prerequisites
Python 3.8 or higher
Required libraries: numpy, scipy, scikit-learn
Steps
Clone the repository:

BASH

git clone https://github.com/gilianb/AI_ML_search_algorithms.git
cd AI_ML_search_algorithms
Install required libraries:

BASH

pip install -r requirements.txt
Usage
Here's an example of using the A* search algorithm:

Python

Collapse
from search_algorithms import AStarSearch

# Define the problem
problem = {
    'start': (0, 0),
    'goal': (10, 10),
    'obstacles': [(5, 5), (5, 6), (6, 5), (6, 6)]
}

# Create an A* search instance
astar = AStarSearch(problem)

# Find the shortest path
path = astar.search()

print(path)
Performance
Time Complexity:
BFS: O(b^d)
DFS: O(b^d)
A*: O(b^d) in the worst case, but typically much faster with a good heuristic
Testing
To run the tests, execute the following command:

BASH

python -m unittest discover -s tests
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes.
Push to your fork and submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or suggestions, please contact:

Gilian B.
GitHub: @gilianb
