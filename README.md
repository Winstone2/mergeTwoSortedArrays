# mergeTwoSortedArrays
To merge two sorted arrays into a single sorted array, we can use the Two-Pointers approach. The idea is to compare elements from both arrays and add the smaller element to the merged array. We keep advancing the pointers until we have processed all elements from both arrays.
Thought Process:

    The function mergeSortedArrays takes two sorted arrays arr1 and arr2 as input.
    We create an empty array mergedArray to store the merged result.
    We use two pointers i and j to keep track of the current positions in arr1 and arr2, respectively.
    We use a while loop to compare elements from both arrays and add the smaller element to the mergedArray. We increment the respective pointer after adding the element to the mergedArray.
    After the loop, if there are any remaining elements in either arr1 or arr2, we add them to the mergedArray.
    We return the mergedArray, which contains the combination of both input arrays in sorted order.

Edge Cases to Consider:

    Empty Arrays: If either or both input arrays are empty, the function should return the non-empty array as the merged result, as there are no elements to compare and merge.
    Arrays with Different Lengths: The function should handle cases where arr1 and arr2 have different lengths and correctly merge the elements from both arrays into the final result.
    Duplicate Elements: The function should handle cases where both input arrays contain duplicate elements and merge them accordingly while maintaining the sorted order.

    In this example, the mergeSortedArrays function correctly merges the two sorted arrays arr1 and arr2 into a single sorted array [1, 2, 3, 4, 5, 6, 7, 8].
