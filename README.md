README.md

This pojects aims to create a _printf() function that replicates the original C
printf() file.
The _printf() variadic function produces output to the stdout according to a
format.

_printf() function contains the "int printf(const char *format, ...);" protype
where;
@format: is the character string which returns the number of characters printed.

_printf() function will print each character as it is and when it enclounters
the "%", the function will print the next character according to a format then
it will go to the next argument to check the variable storing the format
specifier then prints it value.