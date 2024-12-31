# X Gate Qubit Flip

A quantum circuit implementing the X gate (NOT gate) to flip a qubit from |0⟩ to |1⟩.

## Requirements
```
pennylane>=0.19.0
numpy>=1.19.0
```

## Implementation
- Initializes qubit in |0⟩ state
- Applies X gate (PauliX)
- Measures in computational basis
- Returns measurement probabilities

## Expected Output
- |0⟩: 0.0
- |1⟩: 1.0

## Usage
```python
python x_gate.py
```