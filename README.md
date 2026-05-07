# PyTorch Notebook Examples

This repository contains Jupyter notebooks demonstrating PyTorch basics and neural network concepts.

## Repository contents

- `1-Tensors.ipynb` — A notebook that covers:
  - tensor creation and initialization
  - tensor attributes (`dtype`, `device`, `layout`)
  - sparse tensor creation
  - tensor concatenation and reshaping
  - basic arithmetic operations

- `2-Pytorch.ipynb` — A notebook focused on building neural networks in PyTorch.

## Requirements

The notebooks require Python, PyTorch, Jupyter, and an IPython kernel.

## Installation

1. Create and activate a virtual environment (recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Run the notebooks

Start Jupyter and open either notebook:

```bash
jupyter notebook
```

Then open `1-Tensors.ipynb` or `2-Pytorch.ipynb` and run the notebook cells.

## Notes

- The notebooks use `torch` for PyTorch operations.
- For GPU support, install a compatible PyTorch build for your system and CUDA version.
- You can also open the notebooks in VS Code or another notebook editor.
