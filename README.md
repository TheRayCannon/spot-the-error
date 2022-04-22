# Spot The Error

There are at least 5 errors in this code:

This function is supposed to accept a count, and for the numbers 1 up to and including that count:

* Print "fizz" if the number is divisible by 3
* Print "buzz" if the number is divisible by 5
* Print "fizzbuzz" if the number is divisible by 3 and 5
* Otherwise print the number

```
PROGRAM print_fizz_buzz_numbers
    SET count TO INPUT
    SET fizz_buzz_numbers = []
    SET fizz TO []
    SET buzz TO []
    SET number = 1

    WHILE number < count
        SET modulo3 TO number % 3
        SET is_divisible_by_3 TO modulo3
        SET modulo5 TO number % 5
        SET is_divisible_by_5 TO modulo5

        IF is_divisible_by_3 
            ADD number TO fizz
            OUTPUT fizz
       ELSE IF is_divisible_by_5
            ADD number TO buzz
            OUTPUT buzz
        ELSE IF is_divisible_by_3 AND is_divisible_by_5
            ADD number TO fizz_buzz_numbers
            OUTPUT fizz_buzz_numbers
        ELSE 
            OUTPUT ocunt 
     
```

Use reflection techniques and sample data to discover them. **Don't try to run the code**. Edit the program above as minimally as possible to correct the errors you find.
