# AI/ML Search Algorithms

## Overview

This repository features a collection of **search algorithms** commonly used in **Artificial Intelligence (AI) and Machine Learning (ML)**. These algorithms are designed to efficiently explore search spaces and find optimal solutions to complex problems.

## Features

### Uninformed Search Algorithms
- **Breadth-First Search (BFS)**
- **Depth-First Search (DFS)**

### Informed Search Algorithms
- **Greedy Search**
- **A* Search**

### Local Search Algorithms
- **Hill Climbing**
- **Simulated Annealing**

### Machine Learning-based Search
- **Reinforcement Learning (RL) for search optimization**

## Technologies

- **Language**: Python
- **Libraries**: NumPy, SciPy, scikit-learn

## Installation

### Prerequisites
- **Python 3.8 or higher**
- **Required libraries**: NumPy, SciPy, scikit-learn

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/gilianb/AI_ML_search_algorithms.git
   cd AI_ML_search_algorithms
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Here's an example of using the **A* search algorithm**:

```python
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
```

## Performance

- **Time Complexity**:
  - **BFS**: O(b^d)
  - **DFS**: O(b^d)
  - **A***: O(b^d) in the worst case, but typically much faster with a good heuristic

## Testing

To run the tests, execute the following command:

```bash
python -m unittest discover -s tests
```

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, please contact:

- **Gilian B.**
- GitHub: [@gilianb](https://github.com/gilianb)

---

⭐ If you find this project useful, please consider giving it a star! ⭐

