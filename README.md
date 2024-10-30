# Series Programs in Python

This repository contains Python programs that generate various mathematical series, each implemented as an individual function. These examples are helpful for learning programming concepts, practicing recursive functions, and understanding series calculations. 

## Project Contents

The project includes the following series programs:

1. **Prime Number Series**  
   Generates a list of prime numbers up to a specified limit.  
   **Function:** `prime_series(limit)`  
   **Example Usage:** `prime_series(50)`  # Generates prime numbers up to 50

2. **Factorial Series**  
   Calculates the factorial of numbers up to a specified limit.  
   **Function:** `factorial_series(limit)`  
   **Example Usage:** `factorial_series(10)`  # Calculates factorials from 0 to 9

3. **Perfect Numbers Series**  
   Generates a list of perfect numbers up to a specified limit. A perfect number is one that is equal to the sum of its divisors (excluding itself).  
   **Function:** `perfect_numbers(limit)`  
   **Example Usage:** `perfect_numbers(1000)`  # Finds perfect numbers up to 1000

4. **Geometric Sequence**  
   Generates a geometric sequence given the initial term (`a`), common ratio (`r`), and the number of terms (`n`).  
   **Function:** `geometric_sequence(a, r, n)`  
   **Example Usage:** `geometric_sequence(2, 3, 10)`  # Starting with 2, ratio of 3, 10 terms

5. **Square and Cube Series**  
   Calculates squares and cubes of numbers up to a specified limit.  
   **Functions:** `square_series(limit)`, `cube_series(limit)`  
   **Example Usage:**  
   - `square_series(10)`  # Squares numbers from 1 to 10  
   - `cube_series(10)`    # Cubes numbers from 1 to 10  

6. **Fibonacci Sequence with Memoization**  
   Generates Fibonacci numbers up to a specified limit using memoization for optimized performance.  
   **Function:** `fibonacci_series(limit)`  
   **Example Usage:** `fibonacci_series(10)`  # Generates the first 10 Fibonacci numbers

7. **Lucas Series**  
   Generates the Lucas series up to a specified limit, which follows a sequence similar to the Fibonacci sequence but starts with 2 and 1.  
   **Function:** `lucas_series(limit)`  
   **Example Usage:** `lucas_series(10)`  # Generates the first 10 Lucas numbers

8. **Harmonic Series**  
   Calculates the harmonic series up to a specified limit, represented by the series: \( 1 + \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n} \).  
   **Function:** `harmonic_series(n)`  
   **Example Usage:** `harmonic_series(10)`  # Calculates the harmonic series up to 1/10

## Running the Programs

To run any of these series programs:

1. Clone the repository:
   git clone https://github.com/your-username/series-programs.git
   cd series-programs
   
2. Open a Python environment and import the functions, or run the functions directly in a script or interactive shell.

3. Modify the parameters as needed to generate series based on different ranges or limits.

## Requirements
These programs require Python 3.x. No additional libraries are required.

## License
This project is open-source and available under the MIT License.

This `README.md` file provides a structured and clear overview of the project, making it easy for anyone to understand the purpose and usage of each series function.
