# Multi-Threading

## Methodology :
The provided Python script demonstrates the utilization of multi-threading to perform matrix multiplication in Python. Here's a breakdown of the methodology:

### 1. Random Matrix Generation: The generate_random_matrices function generates a specified number of random matrices of a given size.
### 2. Matrix Multiplication: The multiply_matrices function takes a list of matrices and multiplies them sequentially.
### 3. Multi-threaded Matrix Multiplication: The perform_multiplication_with_threads function divides the list of matrices into chunks based on the number of threads and performs matrix multiplication using multiple threads.
### 4. Experiment Setup: The script generates a specified number of random matrices and then tests the performance of multi-threaded matrix multiplication using different numbers of threads.
### 5. Results Recording: The time taken for matrix multiplication with varying numbers of threads is recorded.

## Result Table :
The following table summarizes the time taken for matrix multiplication with different numbers of threads:


## Result Graph :
The graph below illustrates the relationship between the number of threads and the time taken for matrix multiplication:


## Observations :
#### 1. As the number of threads increases, the time taken for matrix multiplication initially decreases due to parallel execution but may plateau or even increase after a certain point due to overhead from thread management.
#### 2. The optimal number of threads depends on various factors such as the size of the matrices, the number of available CPU cores, and the efficiency of thread management.

## Conclusion:
Multi-threading can significantly improve the performance of certain computational tasks like matrix multiplication by leveraging parallelism. However, the effectiveness of multi-threading depends on careful consideration of factors such as task granularity, resource constraints, and overhead.