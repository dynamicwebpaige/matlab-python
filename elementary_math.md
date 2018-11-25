# Arithmetic
_Addition, subtration, multiplication, division, power, rounding._

### Functions

| Description | MATLAB | Python |
| --------- | ------- | -------- |
| Addition | `plus` | |

#### Add Scalar to Array

```
A = np.array([[0, 1], [1, 0]])
C = A + 2
C
```

#### Add Two Arrays

```
A = np.array([[1, 0], [2, 4]])
B = np.array([[5, 9], [2, 1]])

A + B
```

#### Add Vector to a Matrix

```
import numpy as np
A = np.array([[1, 2, 3], [4, 5, 6]])
b = np.array([10, 100])

A + b[:, None]
```

#### Concatenate Strings

```
s1 = ['Red', 'Blue', 'Green']
s2 = ['Truck', 'Sky', 'Tree']
[m+str(n) for m,n in zip(s1,s2)]
```

# Trigonometry
# Exponents and Logarithms
# Complex Numbers
# Discrete Math
# Polynomials
# Special Functions
# Cartesian Coordinate System Conversion
# Constants and Test Matrices
