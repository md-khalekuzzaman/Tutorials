# Quick Sort Theory

Quick sort is a highly efficient sorting algorithm that sorts elements by dividing the array into smaller sub-arrays based on a chosen pivot element. It's a divide-and-conquer algorithm that recursively sorts sub-arrays. Quick sort is widely used due to its fast average-case performance and its ability to sort arrays in-place.

## Theory

1. **Divide**: Select a pivot element from the array. Partition the array into two sub-arrays: elements less than the pivot and elements greater than the pivot.

2. **Conquer**: Recursively apply the same process to the sub-arrays.

3. **Combine**: The sub-arrays are sorted in place, so no additional combining step is needed.

## Example

Consider an unsorted array: `[7, 2, 1, 6, 8, 5, 3, 4]`.

1. Choose a pivot element. Let's pick `5`.
2. Partition the array into two sub-arrays: `[2, 1, 3, 4]` (elements less than `5`) and `[7, 6, 8]` (elements greater than `5`).
3. Recursively apply the same process to the sub-arrays.
   - For the sub-array `[2, 1, 3, 4]`, choose `2` as the pivot. Partition into `[1]`, `[2, 3, 4]`.
   - For the sub-array `[7, 6, 8]`, choose `7` as the pivot. Partition into `[6]`, `[7, 8]`.
4. Finally, combine the sorted sub-arrays to obtain the sorted array `[1, 2, 3, 4, 5, 6, 7, 8]`.

## Time Complexity

- **Best Case**: O(n log n) - when the pivot divides the array into approximately equal parts.
- **Average Case**: O(n log n) - average time taken for random input.
- **Worst Case**: O(n<sup>2</sup>) - when the pivot is consistently chosen poorly, leading to highly imbalanced partitions.
  
## Space Complexity

Quick sort has a space complexity of O(log n) for the recursive call stack, where n is the number of elements in the array.

## Conclusion

Quick sort is a highly efficient sorting algorithm with average-case time complexity better than many other sorting algorithms. However, it may exhibit poor performance on certain input distributions, such as already sorted arrays. Techniques like randomization and selecting a good pivot can mitigate these issues.
