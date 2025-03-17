# QNN House Price Prediction

A hybrid **Quantum Neural Network (QNN)** for predicting house prices using the **California Housing dataset**. The model integrates classical machine learning with quantum variational circuits using **PennyLane** and **PyTorch**.

## Features
- **Quantum Variational Circuit** using **RY, RX, RZ** rotations and entanglement.
- **Hybrid Quantum-Classical Model** with PennyLane's `TorchLayer`.
- **California Housing Dataset** for real-world regression.
- **GPU Acceleration** with `pennylane-lightning-gpu`.

## Model Architecture
- **Quantum Circuit:** 8 qubits, 8 variational layers.
- **Quantum Feature Encoding:** RY rotations.
- **Variational Layers:** RX, RY, RZ rotations with trainable parameters.
- **Entanglement:** CNOT gates between adjacent qubits.
- **Output Layer:** Classical linear layer to scale predictions.
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam


## Evaluation
Model achieved:
- MSE: 0.5431
- RMSE: 0.7370
- R² Score: 0.5855
- MAPE: 27.81%


## License
This project is licensed under the MIT License.

