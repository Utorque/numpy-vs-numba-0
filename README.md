# numpy-vs-numba-0

This follows [this linkedin post](https://www.linkedin.com/posts/habib-boukrana-755479175_python-numba-optimisation-activity-7244822650022244352-3_Q0?utm_source=share&utm_medium=member_desktop) and aims to compare numba njit to optimization using numpy.  
Here are an example of results, feel free to PR yours :  
| Method        | Time (s) | Speedup |
|---------------|----------|---------|
| Without Numba | 4.2702   | 1.00x   |
| With Numba    | 0.9970   | 4.28x   |
| NumPy v1      | 1.2485   | 3.42x   |
| NumPy v2      | 0.8243   | 5.18x   |
| NumPy v3      | 0.0900   | **47.44x**  |
| NumPy v4      | 0.7364   | 5.80x   |
