# NumPy Learning Notes

NumPy (Numerical Python) Python ki core library hai jo fast numerical computing ke liye use hoti hai. Ye N-dimensional arrays (`ndarray`) aur un par vectorized operations provide karti hai, jo normal Python lists se kaafi fast hote hain.

## What's covered
- Array creation (`array`, `zeros`, `ones`, `arange`, `linspace`)
- Indexing, slicing, and reshaping
- Broadcasting and vectorized operations
- Mathematical and statistical functions (`sum`, `mean`, `std`)
- Linear algebra basics (`dot`, `matmul`, `inv`)
- Random number generation

## Installation
pip install numpy

## Quick example
import numpy as np

arr = np.array([1, 2, 3, 4])
print(arr * 2)       # [2 4 6 8]
print(arr.mean())    # 2.5

## Tech
- Python 3.x
- NumPy
