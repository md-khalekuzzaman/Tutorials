# Complexity Analysis Overview

Complexity analysis is a critical concept in computer science, essential for assessing algorithm performance as input size varies. It broadly includes evaluations of time complexity and space complexity.

## Time Complexity Analysis

Time complexity measures the computational time required by an algorithm relative to its input size. Key time complexities, expressed in Big O notation, include:

- **O(1)**: Constant time - Execution time remains constant regardless of input size.
- **O(log n)**: Logarithmic time - Execution time increases logarithmically as input size increases.
- **O(n)**: Linear time - Execution time increases linearly with input size.
- **O(n log n)**: Log-linear time - Common in efficient sorting algorithms like Quick Sort and Merge Sort.
- **O(n<sup>2</sup>)**: Quadratic time - Execution time increases quadratically with input size.
- **O(2<sup>n</sup>)**: Exponential time - Execution time increases exponentially with input size.

## Space Complexity Analysis

Space complexity denotes the amount of memory an algorithm requires relative to its input size, also expressed in Big O notation:

- **O(1)**: Constant space - Memory usage is unaffected by input size.
- **O(n)**: Linear space - Memory usage increases linearly with input size.
- **O(n<sup>2</sup>)**: Quadratic space - Memory usage increases quadratically with input size.

## Example: Bubble Sort Complexity

The Bubble Sort algorithm, used for sorting arrays, offers a clear example of complexity analysis:

- Time Complexity: 
  - Best Case: **O(n)** (when the array is already sorted).
  - Average Case: **O(n<sup>2</sup>)** (for randomly arranged elements).
  - Worst Case: **O(n<sup>2</sup>)** (when elements are in reverse order).

- Space Complexity: **O(1)** (Bubble Sort operates in-place, requiring constant extra space).


