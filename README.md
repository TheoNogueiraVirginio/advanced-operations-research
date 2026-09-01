# Advanced Operations Research 

> 🇧🇷 [Versão em Português](README.pt-BR.md)

This repository contains practical algorithms, simulation techniques, and code developed during the **Advanced Operations Research** graduate course (Master's level) at the Federal Institute of Paraíba (IFPB), taught by Prof. Thiago Gouveia da Silva.

As an undergraduate student invited to take this graduate-level course, I maintain this repository as a technical devlog to document my learning process, experiments, and implementations in C++.

## Tech Stack & Requirements
* **Language:** C++ (C++17 or C++20)
* **Compiler:** `g++`

## Course Log
Classes are organized chronologically using the ISO 8601 standard (`YYYY-MM-DD`):
| Date | Topic | Description |
| :--- | :--- | :--- |
| `2026-08-31` | [Monte Carlo Simulation](./2026-08-31-monte-carlo) | C++ implementation of Monte Carlo simulation techniques using standard `<random>`. |

## Compiling and Running
To compile and run any class code using `g++`:
```bash
# 1. Clone the repository
git clone [https://github.com/TheoNogueiraVirginio/advanced-operations-research.git](https://github.com/TheoNogueiraVirginio/advanced-operations-research.git)

# 2. Navigate to the class folder
cd advanced-operations-research/2026-08-31-monte-carlo

# 3. Compile with C++17 standard and O2 optimization
g++ -std=c++17 -O2 main.cpp -o main

# 4. Run executable
./main
