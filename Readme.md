# Phylogenetic Tree Construction

This project implements two widely used algorithms in computational biology:
- **UPGMA (Unweighted Pair Group Method with Arithmetic Mean)**
- **Neighbor Joining**

Both algorithms generate phylogenetic trees based on a given distance matrix, enabling evolutionary relationship analysis between species or genes.

## Features

- Reads distance matrix from file
- Constructs and displays phylogenetic trees
- Calculates branch distances
- Supports:
  - UPGMA method
  - Neighbor Joining method
- Clean visualization with `networkx` and `matplotlib`

## Project Structure

```
phylo-tree/
├── main.ipynb                # Main notebook for execution
├── utils.py                  # Helper functions (if needed for separation)
├── requirements.txt
├── README.md
└── .gitignore
```

## Dependencies

Make sure you have Python 3.8+ installed. You can install the necessary dependencies using pip:

```bash
pip install -r requirements.txt
```

## How to Run

1. Open the notebook `main.ipynb`.
2. Provide your distance matrix in the appropriate format (square symmetric matrix with headers).
3. Run the cells to generate the UPGMA and Neighbor Joining trees.

## Example Input

```
    A   B   C   D
A   0   5   9   9
B   5   0  10  10
C   9  10   0   8
D   9  10   8   0
```

## Output

- Distance calculations at each step
- Final tree structure printed
- Graphical display of the resulting tree

## License

This project is open source and distributed under the MIT License.
