Performance was evaluated on an NVIDIA H100 GPU (Ours) versus a commercial FEM solver (CPU), averaged over 10,000 test samples.

## 1. Thermal Analysis Results
![Simulation Results](https://user-images.githubusercontent.com/placeholder/simulation_results.png)

| Method | Latency | Speed-up | MAE | MSE | nMAE (%) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **FEM** | 1.20 s | - | - | - | - |
| **Ours** | **0.47 ms** | **x2,553** | 0.2288 | 0.0939 | **0.0925%** |

## 2. Stress Analysis Results
![Simulation Results](https://user-images.githubusercontent.com/placeholder/simulation_results.png)

| Method | Latency | Speed-up | MAE | MSE | nMAE (%) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **FEM** | 1.90 s | - | - | - | - |
| **Ours** | **0.49 ms** | **x3,877** | 0.1142 | 0.0254 | **0.1481%** |
