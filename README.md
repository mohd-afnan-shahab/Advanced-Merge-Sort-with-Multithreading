# Parallel Merge Sort
A C++ implementation of the Merge Sort algorithm with parallel processing using multithreading.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/parallel-merge-sort.git
   ```

2. Compile the project using `g++`:
   ```bash
   g++ -std=c++11 -o parallel_sort main.cpp sorting/mergeSort.cpp sorting/parallelMergeSort.cpp -pthread
   ```

3. Run the executable:
   ```bash
   parallel_sort.exe
   ```

## Features
- Implements both a sequential and parallel version of Merge Sort
- Optimized with multi-threading for large datasets to enhance performance

## Performance
- The parallel version demonstrates significant time savings on multi-core processors compared to the sequential version.

## License
This project is licensed under the [MIT License](LICENSE).
