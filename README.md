# Symbolic Regression Benchmarks (Ideal Gas, Rydberg, and Schechter)

- `newBenchmarks_dataset.xlsx` contains the training datasets for the three benchmark problems: **Ideal Gas**, **Rydberg**, and **Schechter**. These datasets were generated using the code from the original paper, *[Interpretable Machine Learning for Science with PySR and SymbolicRegression](https://github.com/MilesCranmer/pysr_paper)*.
- Computation times and the best symbolic regression equations obtained for each random seed are available in `benchmark/taken_results`.
- Notebooks for training the Arithmetic Neural Network are provided in the corresponding benchmark folders:
  - `IdealGas_model.ipynb`
  - `Rydberg_model.ipynb`
  - `Schechter_model.ipynb`

  Each notebook trains the Arithmetic Neural Network on its respective benchmark dataset.

## KAN-ODEs Benchmark

- Original implementation and source code: [DENG-MIT/KAN-ODEs](https://github.com/DENG-MIT/KAN-ODEs)
- Original paper: *KAN-ODEs: Kolmogorov–Arnold Network Ordinary Differential Equations for Learning Dynamical Systems and Hidden Physics*
- To train the Arithmetic Neural Network, run `predator_prey_model.ipynb` in Google Colab.
- To compare the Arithmetic Neural Network with the original KAN-ODEs implementation and reproduce the comparison figures, use `comparison_original&ArithmeticPapers.ipynb`, located in `/Lotka-Volterra-Pytorch/efficient_kan` (alongside `efficientkan.py`).
