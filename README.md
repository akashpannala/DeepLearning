# X-DEEP

Deep learning fundamentals, built through the NVIDIA Deep Learning Institute's
"Getting Started with Deep Learning" course and the CampusX PyTorch playlist.

## What's covered

- **PyTorch basics** — tensors, autograd, manual training loops
- **Training pipelines** — raw loop → refactored with `nn.Module` → `Dataset`/`DataLoader`
- **ANN on Fashion-MNIST** — CPU → GPU → GPU + optimized → hyperparameter tuning with Optuna
- **CNN on Fashion-MNIST** — GPU training + Optuna tuning
- **Transfer learning** — applied to Fashion-MNIST
- **Sequence models** — RNN-based QA system, LSTM next-word predictor

## Structure

Notebooks are numbered in learning order (`[1]` → `[13]`), tracking tensors →
autograd → training pipelines → ANN → CNN → transfer learning → RNN/LSTM.

## Data

- `fmnist_small.csv` — Fashion-MNIST subset
- `100_Unique_QA_Dataset.csv` — QA pairs for the RNN/LSTM notebooks

## Reference

`CampusX.pdf` — course notes

## Stack

PyTorch, Optuna, CUDA/GPU training
