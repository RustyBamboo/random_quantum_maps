# Quantum Benchmarking via Random Dynamical Quantum Maps [^1]

This repository contains the following:
- Jupyter notebook for creating random dynamical maps and executing on IBMQ (`data_gen/`)
- Raw data from IBMQ (`data/counts_kyoto.npy` and 
`data/counts_osaka.npy`)
- Jupyter notebook for performing noisy simulations using cached data, as well as plotting the results (`random_quantum_maps.ipynb`)

Install requirements:
```
pip install -r requirements.txt
```

Note, we assume `CUDA` is available for simulation of quantum circuits.

```bib
@misc{QuantumBenchmarkingRandom,
  title = {Quantum {{Benchmarking}} via {{Random Dynamical Quantum Maps}}},
  author = {Volya, Daniel and Mishra, Prabhat},
  year = {2024},
  month = apr,
  number = {arXiv:2404.18846},
  eprint = {2404.18846},
  primaryclass = {quant-ph},
  publisher = {arXiv},
  doi = {10.48550/arXiv.2404.18846},
  urldate = {2024-04-30},
}
```

[^1]: D. Volya and P. Mishra, *“Quantum Benchmarking via Random Dynamical Quantum Maps”* arXiv, Apr. 29, 2024. [doi: 10.48550/arXiv.2404.18846](https://doi.org/10.48550/arXiv.2404.18846).
