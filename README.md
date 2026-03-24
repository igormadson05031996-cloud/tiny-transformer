# Tiny Transformer

A minimal educational implementation of the Transformer architecture.

## Components
- Multi-head attention mechanism
- Positional encoding
- Feed-forward networks
- Layer normalisation

## Usage
```python
from transformer import Transformer
model = Transformer(vocab_size=10000, d_model=512, nhead=8)
output = model(input_ids)
```
