# Quantum Benchmarking via Random Dynamical Quantum Maps

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