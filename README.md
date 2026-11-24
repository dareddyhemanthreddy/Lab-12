# Lab 12 — Traveling Salesperson Problem

This repository contains a C++ program for the Traveling Salesperson Problem (TSP), which seeks a minimum-cost tour visiting each city and returning to the start.

## Contents

- [`Lab12/TSP.cpp`](Lab12/TSP.cpp) — TSP program
- [`Lab12/output.png`](Lab12/output.png) — lab output image

## Build and run

Requires `g++` or another C++17 compiler:

```bash
g++ -std=c++17 -Wall -Wextra Lab12/TSP.cpp -o tsp
./tsp
```

Provide the city/graph data as requested by the program. TSP is computationally difficult as the number of cities grows, so test with small inputs unless the implementation uses an approximation or heuristic.

## Learning goals

- Represent tour costs and compare candidate routes.
- Understand the TSP objective and why exhaustive search scales poorly.
- Check that a reported tour visits each city and returns to its starting point.
