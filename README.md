Symbolic Regression Benchmarks (Ideal Gas, Rydberg, and Schechter)
The file newBenchmarks_dataset.xlsx contains the training datasets for the three symbolic regression benchmark problems:
Ideal Gas
Rydberg
Schechter
These datasets were generated using the code from the paper "Interpretable Machine Learning for Science with PySR and SymbolicRegression", available at:
https://github.com/MilesCranmer/pysr_paper

Results
The computation times and the best symbolic regression equations obtained for each random seed are available in:
benchmark/taken_results/

Training the Arithmetic Neural Network
The following notebooks train the Arithmetic Neural Network (ANN) on each benchmark dataset:
IdealGas_model.ipynb
Rydberg_model.ipynb
Schechter_model.ipynb
Each notebook is located in its corresponding benchmark directory.
KAN-ODEs Benchmark
The original KAN-ODEs implementation is available at:
https://github.com/DENG-MIT/KAN-ODEs

Original paper

KAN-ODEs: Kolmogorov–Arnold Network Ordinary Differential Equations for Learning Dynamical Systems and Hidden Physics.
Training the Arithmetic Neural Network
To train the Arithmetic Neural Network on the Lotka–Volterra benchmark, run:
predator_prey_model.ipynb
This notebook is designed to run in Google Colab.
Reproducing the Comparison
To reproduce the comparison figures between the Arithmetic Neural Network and the original KAN-ODEs implementation, run:
comparison_original&ArithmeticPapers.ipynb
This notebook is located in:
Lotka-Volterra-Pytorch/efficient_kan/

alongside efficientkan.py.
