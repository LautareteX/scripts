<br/>
<p align="center">
  <h3 align="center">_PRINTF Function.</h3>

  <p align="center">
    Replicate of many of the functons of the original printf, only that we think that are more important, with us modifications.
    <br/>
    <br/>
    <a href="https://github.com/JereDev19/holbertonschool-printf"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/JereDev19/holbertonschool-printf/total) ![Contributors](https://img.shields.io/github/contributors/JereDev19/holbertonschool-printf?color=dark-green) ![Issues](https://img.shields.io/github/issues/JereDev19/holbertonschool-printf) 

## About The Project

This is a custom implementation of the printf function in C, developed as a project for Holberton School. The function supports the following format specifiers: %s, %d, %i, %c and %%, and works the same way as the original printf function.

## Usage

The _printf function works very similar as the original printf function.

* To call the function use this:

➡️_printf("format string", arguments);

The first argument is a string that contains format specifiers, which are replaced by the corresponding argument values. The function returns the number of characters printed (excluding the terminating null byte).

# There is an example-->>

    char *str = "This is a holberton project";
    int num = 42;

    _printf("String: %s\n", str);
    _printf("Decimal: %d\n", num);
    _printf("Character: %c\n", 'H');
    _printf("Percent sign: %%\n");


# Output:

    String: This is a holberton project
    Decimal: 42
    Character: H
    Percent sign: %

## Format Specifiers

* **%d:** Prints a decimal (base 10) integer.
* **%i:** Same as *%d*.
* **%s:** Prints a string.
* **%c:** Prints single character. 
* **%%:** Simply print a %.

## Authors

* **Jeremias Erba** - *Holberton Student* - [Jeremias Erba](https://github.com/JereDev19/) - *Software development and team leadership*
* **Lautaro Rodriguez** - *Holberton Student* - [Lautaro Rodriguez](https://github.com/LautareteX/) - *Software Developer and README Writer.md*
