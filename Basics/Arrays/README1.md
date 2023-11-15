# Introduction to Arrays

An array in C is a collection of elements of the same data type, stored in contiguous memory locations. Each element is identified by its index or position within the array.

### Declaration:
```C
int numbers[5]; // Declares an integer array with 5 elements
```

### Initialization:
```C
int numbers[5] = {1, 2, 3, 4, 5}; // Initializes an integer array during declaration
```
### Accessing Elements:
```C
printf("First element: %d\n", numbers[0]); // Accesses the first element of the array

```
### Array Size:
The size of an array is fixed once it is declared, and it cannot be changed during the program's execution. The **sizeof** operator can be used to find the size of an array in bytes:
```C
int size = sizeof(numbers); // Gives the total size of the array in bytes
```
### Iterate through an Array
Below is an example of using a for loop to iterate through an array in C. In this example, we use an array of integers:
```C
#include <stdio.h>

int main() {
    // Declare and initialize an array
    int numbers[] = {1, 2, 3, 4, 5};

    // Determine the size of the array
    int arraySize = sizeof(numbers) / sizeof(numbers[0]);

    // Use a for loop to iterate through the array
    for (int i = 0; i < arraySize; i++) {
        printf("Element at index %d: %d\n", i, numbers[i]);
    }

    return 0;
}
```

The Output is
```
Element at index 0: 1
Element at index 1: 2
Element at index 2: 3
Element at index 3: 4
Element at index 4: 5
```

### Matrix Representation:

C supports multidimensional arrays, allowing you to create tables or matrices. Let's consider the following Matrix.

| 1 | 2 | 3 |
|---|---|---|
| 4 | 5 | 6 |
| 7 | 8 | 9 |

This can be represented by the following array.
```C
int matrix[3][3] = {
    {1, 2, 3},
    {4, 5, 6},
    {7, 8, 9}
};
```
