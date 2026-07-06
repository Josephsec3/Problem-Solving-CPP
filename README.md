# Problem Solving & Competitive Programming (C++)

## 🚀 Project Overview
This repository contains my clean and optimized solutions for various competitive programming and algorithmic problems using **C++**. 

## 🧠 Solved Problem: Basic Arithmetic Validation
The current implementation checks a fundamental relation between three integers ($a$, $b$, and $c$) to verify if the sum of the first two numbers equals the third one ($a + b = c$).

### 🛠️ Optimization Features
* **Fast I/O Operations:** Uses `ios_base::sync_with_stdio(false);` and `cin.tie(nullptr);` to untie standard C and C++ streams, ensuring maximum execution speed during standard input/output handling.
* **Memory Efficient:** Avoids heavy objects, using primitive types and standard comparison mechanics for $O(1)$ time complexity verification per test case.

## 💻 How to Compile and Run
You can compile this solution using any standard `g++` compiler:
```bash
g++ -O3 -std=c++17 solution.cpp -o solution
./solution
