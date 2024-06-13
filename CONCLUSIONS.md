# goit-algo-hw-04-

Based on the provided timings for sorting random arrays of different sizes:

Size: 100:

Merge Sort: 7.8 microseconds
Insertion Sort: 9.94 microseconds
Timsort (sorted): 7.67 microseconds
Size: 1000:

Merge Sort: 0.94 milliseconds
Insertion Sort: 12.27 milliseconds
Timsort (sorted): 75.3 microseconds
Size: 10000:

Merge Sort: 12.51 milliseconds
Insertion Sort: 1.25 seconds
Timsort (sorted): 975.83 microseconds
Observations:

For small arrays (Size: 100), Insertion Sort and Merge Sort are both relatively fast, with Timsort being the fastest due to its optimized implementation in Python's sorted function.
As the array size increases, Insertion Sort becomes significantly slower compared to Merge Sort and Timsort.
Merge Sort exhibits a consistent performance increase with the increase in array size, whereas Insertion Sort's performance degrades drastically.
Timsort consistently outperforms both Merge Sort and Insertion Sort across all array sizes, especially for larger arrays, demonstrating its efficiency and effectiveness in sorting.
Overall, these results confirm the expected behavior of these sorting algorithms, with Timsort showing superior performance, especially for larger datasets.
