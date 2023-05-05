# assignment-

# Date Program

This program is a C language program that calculates the date of the next day, given a specific date. It also checks if the given year is a leap year.

## Functionality

The program uses a `struct` to represent a date with month, day, and year. It has two functions:

1. `is_leap_year(struct date day)`: This function takes a `struct date` as an argument and checks if the year is a leap year or not.

2. `tomorrow(struct date day)`: This function takes a `struct date` as an argument and returns the date of the next day.

The `main()` function takes user input for a specific date, calls the `tomorrow()` function to calculate the next day's date, and prints the result in the required format.

## How to Run

To run this program, you need to have a C compiler installed on your computer. You can use any C compiler of your choice. Here are the steps to run the program:

1. Open a text editor and copy the code from the program.

2. Save the file with a `.c` extension.

3. Open a terminal and navigate to the directory where you saved the file.

4. Compile the code using the command `gcc -o dateprogram dateprogram.c`.

5. Run the program using the command `./dateprogram`.

6. Enter the date in the format "mm dd yyyy".

7. The program will output the date of the next day in the format "mm/dd/yy".

## Conclusion

This program is a simple C program that demonstrates the use of `structs` and functions in C. It provides an easy way to calculate the date of the next day and check if a year is a leap year or not.
