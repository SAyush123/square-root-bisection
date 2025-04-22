# Square Root Bisection Method 

This repo contains a Python implementation of the **bisection method** to approximate the square root of a given non-negative number.

## Features

- Handles square roots of both integers and floats
- Accepts a custom tolerance level for accuracy
- Handles invalid inputs like negative numbers
- Prints and returns the approximate root
- Stops early if the desired precision is met

## How It Works

The **bisection method** repeatedly narrows down an interval where the square root lies by checking the midpoint of the current interval until the squared midpoint is within a given tolerance of the target.

## Example Usage

```python
from square_root import square_root_bisection

# Find square root of 25
square_root_bisection(25)

# Approximate square root of 2 with custom tolerance
square_root_bisection(2, tolerance=1e-10)
