# Introduction to Data Types:

In C programming, data types specify the type of data a variable can hold. C supports various data types, categorized into basic types and derived types. Some of them are 
- int: Represents integers (whole numbers)
- long: Represents integers with a larger range than the standard int data type.
- float: Represents floating-point numbers (decimal numbers).
- double: Similar to float but with double precision.
- char:Represents single characters.

The following example shows how to use int data type. Assume that the file is named as numbers.c. 
```C
#include <stdio.h>

int main() {
    int age = 25;
    printf("Age: %d\n", age);
    return 0;
}
```
 You can run the above code using the Linux terminal and GCC as follows.
```bash
gcc num numbers.c
./num
```
 
