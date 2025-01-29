# 🧮 Goldbach’s Conjecture & Goldbach Deuce  

## 📜 Overview
This project implements **two variations** of **Goldbach’s Conjecture**, a famous unsolved problem in number theory:  

1. **Goldbach’s Conjecture**:  
   - **Original Hypothesis**: _Every even integer greater than 2 can be expressed as the sum of two prime numbers._
   - This program iterates through even numbers up to a given limit and finds prime pairs that sum to each number.

2. **Goldbach Deuce**:  
   - A variation of Goldbach’s Conjecture that **adds an extra condition** to analyze the properties of prime summations.
   - It checks **whether there are multiple unique prime pairs** for a given even number.
   - Used to explore Goldbach’s Conjecture beyond basic verification.
   - Applied **BINARY SEARCH.**

## 🎯 Features
✅ **Goldbach’s Conjecture Solver**:  
- Finds **two prime numbers** that sum to each even number.  
- Uses **Sieve of Eratosthenes** for fast prime number generation.  
- Efficiently computes solutions for numbers up to **millions**.  

✅ **Goldbach Deuce Analyzer**:  
- Extends the classic problem by checking **multiple prime pair solutions**.  
- Determines whether **Goldbach’s sum pairs are unique or diverse**.

### **Goldbach’s Conjecture Algorithm**
1. **Generate Prime Numbers**: Uses the **Sieve of Eratosthenes** to generate all primes up to a given limit.
2. **Check Goldbach’s Conjecture**: For each even number, find at least one prime pair that sums to it.
3. **Print Results**: Outputs the first valid prime pair.

🔢 **Example Output:**
4 = 2 + 2  
6 = 3 + 3  
8 = 3 + 5  
10 = 3 + 7  
...
98 = 19 + 79
100 = 3 + 97

### **Goldbach Deuce Algorithm**
1. **Find All Prime Pairs**: Instead of returning only one pair, this variation finds multiple unique prime sums for each even number.
2. **Analyze Prime Pair Properties**: Determines if some numbers have more unique solutions than others.

🔢 Example Output:
10 has 2 prime pair solutions: (3, 7), (5, 5)
20 has 3 prime pair solutions: (3, 17), (7, 13), (11, 9)
50 has 4 prime pair solutions: (3, 47), (7, 43), (13, 37), (19, 31)
