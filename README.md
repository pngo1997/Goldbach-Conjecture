# 🧮 Goldbach's Conjecture Solver

## 📜 Overview
This project verifies **Goldbach’s Conjecture** for even numbers up to **100**.  
Goldbach's Conjecture states that: _Every even integer greater than 2 can be expressed as the sum of two prime numbers._  
This program iterates through even numbers up to 100 and finds at least one prime pair for each.

## 🎯 Features
- **Automated Verification**: Checks all even integers < 100.
- **Prime Number Decomposition**: Finds two prime numbers that sum to the target.
- **Efficient Computation**: Uses an optimized **prime sieve** algorithm.

## 🛠 How It Works
1. **Generate Prime Numbers**: Uses the **Sieve of Eratosthenes** to generate all prime numbers up to 100.
2. **Check Goldbach’s Conjecture**: For each even number, find two primes that sum to it.
3. **Print Results**: Outputs the first valid pair found for each number.

## 📝 Example Output
```shell
4 = 2 + 2
6 = 3 + 3
8 = 3 + 5
10 = 3 + 7
...
98 = 19 + 79
100 = 3 + 97
