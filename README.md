# Sorting Algorithms in C++

![C++](https://img.shields.io/badge/C%2B%2B-blue) ![Course](https://img.shields.io/badge/CS315-Algorithm%20Design%20%26%20Analysis-lightgrey)

## Overview
A C++ program that implements three classic sorting algorithms (Insertion, Quick, and Merge Sort) and uses them to order video game datasets by revenue. Built for my CS315 Algorithm Design and Analysis class.

## Algorithms Implemented
| Algorithm | Approach | Best | Average | Worst |
|---|---|---|---|---|
| Insertion Sort | Inserts each element into its place in the sorted portion | O(n) | O(n^2) | O(n^2) |
| Quick Sort | Pivot-based partitioning, sorted recursively | O(n log n) | O(n log n) | O(n^2) |
| Merge Sort | Divide and conquer: split, sort, merge | O(n log n) | O(n log n) | O(n log n) |

The provided datasets in `data/` let you compare how each algorithm behaves on best-case and worst-case input.

## Project Structure
- `sorting.cpp`: all three algorithms and the CSV handling
- `data/`: input CSV datasets

## How to Run
```bash
git clone https://github.com/lilBiggy101/algorithms-sorting.git
cd algorithms-sorting
g++ sorting.cpp -o sorting
./sorting data/<filename>.csv
```
Replace `<filename>` with any CSV file in the `data/` folder. On Windows, use `sorting.exe data\<filename>.csv`.

## Technologies
- C++
- CSV file handling

## What I Learned
- How insertion, quick, and merge sort work and how to implement each one on real data.
- Why algorithm analysis matters: the same algorithm can perform very differently on best-case and worst-case inputs.
