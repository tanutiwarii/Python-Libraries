# PyTorch and OpenCV Notebook Examples

This repository contains Jupyter notebooks demonstrating PyTorch basics, neural network concepts, and OpenCV image processing.

## Repository contents

- `1-Tensors.ipynb` — A notebook that covers:
  - tensor creation and initialization
  - tensor attributes (`dtype`, `device`, `layout`)
  - sparse tensor creation
  - tensor concatenation and reshaping
  - basic arithmetic operations

- `2-PyTorch.ipynb` — A notebook focused on building neural networks in PyTorch.

- `3-OpenCV.ipynb` — A notebook demonstrating OpenCV image processing with NumPy and Matplotlib.

## Requirements

The notebooks require Python, PyTorch, OpenCV, NumPy, Matplotlib, Jupyter, and an IPython kernel.

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

Start Jupyter and open the notebooks:

```bash
jupyter notebook
```

Then open `1-Tensors.ipynb`, `2-PyTorch.ipynb`, or `3-OpenCV.ipynb` and run the notebook cells.

## Notes

- `1-Tensors.ipynb` and `2-PyTorch.ipynb` use `torch` for PyTorch operations.
- `3-OpenCV.ipynb` uses `cv2`, `numpy`, and `matplotlib.pyplot` for image processing.
- For GPU support, install a compatible PyTorch build for your system and CUDA version.
- You can also open the notebooks in VS Code or another notebook editor.
