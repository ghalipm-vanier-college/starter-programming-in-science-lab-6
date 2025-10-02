# Programming in Science - Lab 6

This template repository is the starter project for **Programming in Science Lab 6**. Written in Python, and tested with Pytest.

### Question(s)

1. **(30%)** User-Defined Function - Factorial:
   
   - Write a function `factorial(n)`, n>=0,  that **returns the factorial** of a given number using recursion. ( n!=n*(n-1)*...*3*2*1, 0!=1 )   
   #### Example:
   ```python
   factorial(5)  # Returns 120
   factorial(7)  # Returns 5040
   ```
   ✅ **Hints:** Use recursion (`n * factorial(n - 1)`) and handle base cases (`n == 0 or n == 1`).

2. **(30%)** User-Defined Function - Fibonacci:
   
   - Write a function `fibonacci(n)`, n>=1,  that **returns the nth Fibonacci number** using recursion.
   
   #### Example:
   ```python
   fibonacci(1)  # Returns 0
   fibonacci(2)  # Returns 1
   fibonacci(3)  # Returns 1
   fibonacci(4)  # Returns 2
   fibonacci(5)  # Returns 3
   ```
   ✅ **Hints:** The Fibonacci sequence follows `F(n) = F(n-1) + F(n-2)`, with base cases `F(1) = 0` and `F(2) = 1`.

3. **(40%)** User-Defined Function - Prime Check:
   
   - Write a function `is_prime(n)`, n>=2,  that **checks if the number n is prime**.
   
   #### Example:
   ```python
   is_prime(2)  # Returns True
   is_prime(4)  # Returns False
   is_prime(11) # Returns True
   ```
   ✅ **Hints:** A number `n` is prime if it has **exactly two divisors: 1 and itself**. Optimize using `sqrt(n)` - optional.
   ```
   
### Run Command

To run the tests, use the following command:

```
pytest
```
