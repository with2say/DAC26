Performance was evaluated on an NVIDIA H100 GPU (Ours) versus a commercial FEM solver (CPU), averaged over 10,000 test samples.

## 1. Thermal Analysis Results
![Thermal Samples](https://github.com/with2say/DAC26/blob/main/thermal_samples.png)
> **Figure 1. Thermal Analysis (Normal).** Prediction results for typical thermal distribution cases.

| Method | Latency | Speed-up | MAE | MSE | nMAE (%) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **FEM** | 1.20 s | - | - | - | - |
| **Ours** | **0.47 ms** | **x2,553** | 0.2288 | 0.0939 | **0.0925%** |


## 2. Stress Analysis Results
![Simulation Results](https://github.com/with2say/DAC26/blob/main/stress_samples.png)
> **Figure 2. Stress Analysis (Normal).** Predicted von Mises stress distribution for standard test scenarios.

![Simulation Results](https://github.com/with2say/DAC26/blob/main/stress_worst.png)
> **Figure 3. Stress Analysis (Worst).** Evaluation of samples with the highest prediction errors. Even in these cases, the model still accurately captures the sharp stress gradients.

| Method | Latency | Speed-up | MAE | MSE | nMAE (%) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **FEM** | 1.90 s | - | - | - | - |
| **Ours** | **0.49 ms** | **x3,877** | 0.1142 | 0.0254 | **0.1481%** |
