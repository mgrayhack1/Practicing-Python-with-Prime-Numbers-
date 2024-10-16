This Jupyter Notebook provides functionality to check whether a given number is prime. It includes a function `is_prime()` to determine if a number is prime and a mechanism for applying this function to individual numbers or lists of numbers.
## Features

- **Prime Number Check**: The `is_prime()` function determines if a given number is a prime number by checking its divisibility.
- **List Processing**: The notebook can handle individual numbers or lists of numbers, checking whether each number is prime.
- **Efficient Checking**: The notebook optimizes prime checking by using the basic definition of prime numbers, ensuring numbers are only checked up to their square root for potential divisors.

## Usage

1. **Prime Number Check**:
   To check if a single number is prime, you can use the `is_prime()` function:
   ```python
   is_prime(29)  # Returns True, since 29 is prime
