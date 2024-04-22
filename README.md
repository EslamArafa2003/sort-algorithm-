1. Define the insertionSort function: This function takes an integer array arr and its length n as parameters. It implements the insertion sort algorithm to sort the array in ascending order.

2. Iterate over the array starting from the second element (i = 1): For each element, extract the key to be inserted (key = arr[i]).

3. Find the correct position for the key: Iterate over the sorted part of the array (from 0 to i-1) to find the correct position for the key. While iterating, shift elements greater than the key to the right 
(arr[j + 1] = arr[j]) until finding the correct position (arr[j] <= key).

4. Insert the key into its correct position: Once the correct position for the key is found, insert the key into its correct position in the sorted array (arr[j + 1] = key).

5. main function: Initialize an integer array arr with values {12, 11, 13, 5, 6} and calculate the length of the array (n = sizeof(arr) / sizeof(arr[0])).

6. Call the insertionSort function: Pass the array arr and its length n to the insertionSort function to sort the array.

7. Print the sorted array: After sorting, use a loop (for (int i = 0; i < n; i++)) to print the sorted array elements separated by spaces. Print a newline at the end (std::cout << std::endl) to format the output.

8. Compile and run the program
