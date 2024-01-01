---
layout: default
---

# Welcome to my space

This is my porfolio. It has my projects and my work. 

## GPU-MATMUL

GPU-based matrix multiplication (matmul) is a critical operation in various computational fields, especially in deep learning and scientific computing. GPUs are highly efficient at handling parallel tasks, making them ideal for matrix multiplication, which involves multiple simultaneous arithmetic operations. This parallel processing capability allows for significantly faster computation compared to traditional CPUs, leading to quicker data processing and reduced execution times. Utilizing GPU for matrix multiplication is essential in applications that demand high-speed calculations and real-time data processing, such as neural network training, simulations, and large-scale data analysis.

## Getting Started


![DALL·E 2024-01-01 09 37 40 - An image of a modern GPU (Graphics Processing Unit) commonly used in computing and gaming  The GPU is depicted as a detailed, close-up view, showing i](https://github.com/amanrai1234/amanrai1234.github.io/assets/37281887/3913ec95-52c2-49d8-b42e-cbd8c00fb748)


my performance evaluation of Matmul on GPU/CPU using pthreads, CUDA, OpenMP, MPI.

![image](https://github.com/amanrai1234/amanrai1234.github.io/assets/37281887/816bf206-8617-4208-894d-7ad7bc728d7d)

The chart above visually represents the performance comparison of matrix multiplication across different methods and data types. It compares GPU, Sequential (SEQ), and OPENMP implementations for both float and double data types across various matrix sizes.

Key Observations:

GPU Performance: The GPU shows consistent and efficient performance, especially as the matrix size increases. For larger matrices, the GPU significantly outperforms other methods, highlighting its capability for high-level parallelism.
Sequential and OPENMP: These methods are more efficient for smaller matrices but become increasingly slower as matrix size grows, especially evident in the SEQ implementation.
Float vs. Double Precision: The use of float generally results in faster computations than double precision across all methods. However, the choice between float and double depends on the required precision of the calculations.
The chart clearly illustrates that for tasks requiring high parallelism, especially with larger matrices, GPU-based computation offers a significant advantage in terms of speed. This makes it a preferable choice for complex computations in fields like deep learning and scientific simulations.

