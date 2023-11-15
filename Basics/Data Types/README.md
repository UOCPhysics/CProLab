# Introduction to Data Types:

In C programming, data types specify the type of data a variable can hold. C supports various data types, categorized into basic types and derived types. Some of them are 
- **int**: Represents integers (whole numbers)
- **long**: Represents integers with a larger range than the standard int data type.
- **float**: Represents floating-point numbers (decimal numbers).
- **double**: Similar to float but with double precision.
- **char**:Represents single characters.

## Data Types: int and long 
The following example shows how to use **int** and **long** data types. Assume that the file is named as numbers.c. 
```C
#include <stdio.h>

int main() {
    int mass = 25;
    long distance = 1000000;
    printf("Mass: %d in kg\n", age);
    printf("Distance: %d in m\n", distance);
    return 0;
}
```
 You can run the above code using a Linux terminal and GCC as follows.
```bash
gcc -o num numbers.c
./num
```

## Data Types:  float and double
The following example shows how to use **float** and **double** data types. Assume that the file is named as floats.c. 
```C
#include <stdio.h>

#include <stdio.h>

int main() {
    // Declare variables of type float and double
    float floatVar = 3.14159265358979323846;  
    double doubleVar = 3.14159265358979323846;

    // Display the values with different precisions
    printf("Float Variable: %.7f\n", floatVar);  // Display with 7 decimal places
    printf("Double Variable: %.15lf\n", doubleVar);  // Display with 15 decimal places

    // Perform some arithmetic operations
    float resultFloat = floatVar / 2.0;
    double resultDouble = doubleVar / 2.0;

    // Display the results
    printf("Result of float division: %.7f\n", resultFloat);
    printf("Result of double division: %.15lf\n", resultDouble);

    return 0;
}

}

```
 You can run the above code using a Linux terminal and GCC as follows.
```bash
gcc -o num floats.c
./num
```

Note that **float** has less precision than **double**. Using **printf** with format specifiers like **%f** and **%lf** allows you to control the precision when displaying floating-point numbers.

Remember that the choice between float and double depends on the required precision and the range of values you need to represent. In general, double is more commonly used due to its higher precision, but it also requires more memory.

# Data Type: char

 In C programming, **char** is not limited to representing only letters; it can represent any ASCII character, including letters, digits, punctuation, and control characters. The following code contains three char variables including a alphebatical character, a digit, and a special character.

```C
#include <stdio.h>

int main() {
    char letter = 'B';
    char digit = '0';
    char special = '#';
    printf("Letter: %c\n", letter);
    printf("Digit: %c\n", digit);
    printf("Special Character: %c\n", special);
    return 0;
}
```
