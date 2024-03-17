### Quick Sort Algorithm

#### Steps:
1. Choose a pivot element from the array. Typically, you can select the last element in the array.
2. Partition the array into two sub-arrays: elements less than the pivot and elements greater than the pivot.
3. Recursively apply the above steps to the sub-arrays.
4. Combine the sorted sub-arrays to obtain the final sorted array.

#### Pseudocode:

```c++
```python
function quick_sort(arr, low, high):
    if low < high:
        # Partition the array
        pivot_index = partition(arr, low, high)
        
        # Recursively sort the sub-arrays
        quick_sort(arr, low, pivot_index - 1)
        quick_sort(arr, pivot_index + 1, high)

function partition(arr, low, high):
    pivot = arr[high]   # Choose pivot (usually last element)
    i = low - 1         # Index of smaller element

    for j = low to high - 1:
        if arr[j] <= pivot:
            i += 1
            swap(arr[i], arr[j])

    swap(arr[i + 1], arr[high])
    return i + 1

```
