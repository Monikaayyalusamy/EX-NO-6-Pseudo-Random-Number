# EX-NO-6-Pseudo-Random-Number

## AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

## ALGORITHM:

1. Start
2. Declare variables i and
3. Initialize the random number generator using the current system time.
4. Read the number of random numbers ( n ) from the user.
5. Display a message indicating that random numbers are being generated.
6. Repeat from i = 0 to i < r
. Generate a random number between 0 and 99.
. Display the generated random number.
7. Print a new line.
8. Stop

n
## PROGRAM:
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
int i, n;
srand(time(0));
printf("Enter how many pseudorandom numbers you want to generate: ");
scanf("%d", &n);
printf("Generating %d pseudorandom numbers between 0 and 99:\n", n);
for (i= 0; i <n; i++) {
int randomNumber = rand() % 100;
printf("%d ", randomNumber);
printf("\n");
return 0;
```

## OUTPUT:
<img width="1918" height="881" alt="image" src="https://github.com/user-attachments/assets/f9b3a979-7d1e-4ffe-94ff-69f91bc3443e" />

## RESULT:
The program successfully generated and displays the specified number of pseudorandom numbers between 0 and 99 based on the user's input.
