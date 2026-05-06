# Tensors in PyTorch

This repository contains a single Jupyter notebook demonstrating basic PyTorch tensor concepts and operations.

## Repository contents

- `Tensors.ipynb` — A notebook that covers:
  - tensor creation and initialization
  - tensor attributes (`dtype`, `device`, `layout`)
  - sparse tensor creation
  - tensor concatenation and reshaping
  - basic arithmetic operations

## Requirements

The notebook requires Python, PyTorch, and Jupyter.

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

## Run the notebook

Start Jupyter and open the notebook:

```bash
jupyter notebook Tensors.ipynb
```

Then run the notebook cells to explore tensor examples.

## Notes

- The notebook uses `torch` for tensor operations.
- For GPU support, install a compatible PyTorch build for your system and CUDA version.
- If you do not use Jupyter, you can also open the notebook in VS Code or another notebook editor.
