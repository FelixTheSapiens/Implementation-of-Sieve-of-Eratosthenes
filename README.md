# primeFinder

`primeFinder` is a Python class that implements the Sieve of Eratosthenes algorithm for finding prime numbers within a given range.

## Features

- Efficiently finds prime numbers using the Sieve of Eratosthenes algorithm.
- Uses a boolean list to mark prime numbers, resulting in efficient memory usage.
- Measures and displays the execution time for finding prime numbers.
- Calculates and displays the percentage of prime numbers within the given range.

## Usage

### Instantiation

```python
# Import the primeFinder class
from primeFinder import primeFinder

# Instantiate the primeFinder class
pf = primeFinder()
```

### Generating Prime Numbers

```python
# Call the generate_primes method with the desired range
n = 100
pf.generate_primes(n)

# The prime numbers within the range are stored in the primes attribute
print(pf.primes)  # Example output: [2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97]
```

### Printing Results

```python
# Call the print_results method to display the percentage of primes and execution time
pf.print_results()

# Example output:
# Percentage of Primes: 25.0%
# Execution Time: 0.0012345678901234567 seconds

# Call the get_primes method to get a list of all found primes. PROCEED WITH CAUTION.

print(pf.get_primes())
```

## Requirements

- Python 3.x

## License

This code is released under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Author

[Gleb Meshvildishvili](https://github.com/FelixTheSapiens)
