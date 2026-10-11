# Deep Learning Basics with PyTorch

A deep learning lab from Nantes Université (2026/2027): a first full deep learning pipeline in PyTorch, from loading data to training a model, making predictions and evaluating them.

The lab was written by Alexandre Bruckert (Nantes Université) and is based on the official [PyTorch "Learn the Basics" tutorial](https://docs.pytorch.org/tutorials/beginner/basics/intro.html). This repository contains my completed version.

## Contents

| Path | Description |
| --- | --- |
| `pytorch_basics.ipynb` | The lab notebook, with my answers and experiments |
| `data/FashionMNIST/raw` | The Fashion-MNIST dataset files used in the lab |

## What the lab covers

- **Part 1 — Basics: tensors and autograd.** Creating and manipulating tensors (from Python lists, NumPy arrays, or pre-filled values) and computing gradients automatically.
- <!-- TODO: add one line per remaining part of the notebook, e.g. datasets and dataloaders, building the model, training loop, evaluation -->

## Dataset

The lab uses [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist): 70,000 grayscale images of clothing items (28×28 pixels) in 10 classes, split into 60,000 training and 10,000 test images.

## Getting started

Requirements: Python 3.9+ and Jupyter.

```bash
git clone https://github.com/youssra-abouelmawahib/Deep-Learning-basics-with-Python.git
cd Deep-Learning-basics-with-Python

python -m venv .venv
.venv\Scripts\activate        # Windows
# source .venv/bin/activate   # macOS / Linux

pip install torch torchvision numpy jupyter
```

Then open the notebook in VS Code or with `jupyter notebook`, and run the cells from top to bottom.

## Results

<!-- TODO: add your final test accuracy and loss, and a short note on what you tried (learning rate, batch size, epochs, architecture) -->

## Credits

- Lab subject: Alexandre Bruckert, Nantes Université
- Source material: [PyTorch tutorials](https://docs.pytorch.org/tutorials/beginner/basics/intro.html)
- Completed by: Youssra Abouelmawahib
