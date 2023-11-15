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
