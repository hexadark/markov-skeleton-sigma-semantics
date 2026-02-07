# markov-skeleton-sigma-semantics (computing)

This folder contains the Section 7 computational grounding notebooks.

## Contents
- `sigma_snf_validation.ipynb`
- `grounding_catastrophic_forgetting.ipynb`
- `grounding_neural_net.ipynb`
- `grounding_cifar10.ipynb`
- `figures/` (output image directory)

## Environment
- Python 3.10+
- `numpy`, `matplotlib`
- `torch`, `torchvision`
- Jupyter Notebook / JupyterLab

## How to run
1. Open any notebook.
2. Run all cells.
3. Figures are saved under `figures/`.

## Data (CIFAR-10)
- `grounding_cifar10.ipynb` is configured with `download=True`.
- CIFAR-10 is downloaded/extracted automatically to `root='data'`.
- Internet access is required for first-time setup.

## Notes
- Some metrics may vary slightly across reruns.
- This repository does not require redistributing CIFAR-10 raw files.

## License
- MIT
