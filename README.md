# Sorting Algorithms
This project includes implementations of the most well-known sorting algorithms, and the parallel implementation of them using STL's threads.

The implemented algorithms include:

- Counting Sort
- Parallel Counting Sort
- Insertion Sort
- Merge Sort
- Parallel Merge Sort
- Quick Sort

The implementations were timed and compared between them and with `std::sort()`, on a vector with 10,000,000 uniformly distributed random values, in the range [-1000, 1000]. The runtime of each algorithm is shown bellow, as the output of `main()`.

```text
[T] Timing [std::sort]
[T] Timing [std::sort] completed in 456 ms
[T] Timing [Counting Sort]
[T] Timing [Counting Sort] completed in 24 ms
[T] Timing [Parallel Counting Sort]
[T] Timing [Parallel Counting Sort] completed in 27 ms
[T] Timing [Insertion Sort]
[T] Timing [Insertion Sort] completed in 18153338 ms
[T] Timing [Merge Sort]
[T] Timing [Merge Sort] completed in 829 ms
[T] Timing [Parallel Merge Sort]
[T] Timing [Parallel Merge Sort] completed in 387 ms
[T] Timing [Quick Sort]
[T] Timing [Quick Sort] completed in 12709 ms
```
