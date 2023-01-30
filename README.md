# C - printf team project

## Synopsis

This is a simple implementation of printf function that formats and prints data.

## Description

The _printf() function produces output according to a format which is given. The functions will write output to stdout, the standard output stream. The function returns the number of characters printed (excluding the null byte used to end output to strings) when successful. 
format is a character string. The format string is composed of zero or more directives.
The conversion specifiers handled in this project include:
<ul>
<li>%c: Prints a single character.</li>
<li>%s: Prints a string of characters.</li>
<li>%d: Prints integers.</li>
<li>%i: Prints integers.</li>
<li>%b: Prints the binary representation of an unsigned decimal.</li>
<li>%u: Prints unsigned integers.</li>
<li>%x: Prints the hexadecial representation of an unsigned decimal in lowercase letters.</li>
<li>%X:Prints the hexadecial representation of an unsigned decimal in uppercase letters.</li>
<li>%r: Prints a reversed string.</li>
# tasks


# mandatory
**0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life**
<li>Write a function that produces output according to a format.</li>
<li>Prototype: int _printf(const char *format, ...);</li>
<li>Returns: the number of characters printed (excluding the null byte used to end output to strings)</li>

                                                                                                                                                           
<li>write output to stdout, the standard output stream
format is a character string.</li> 

**The format string is composed of zero or more directives. See man 3 printf for more detail. 
You need to handle the following conversion specifiers:**
<li>c</li>
<li>s</li>
<li>%</li>
<li>You don’t have to reproduce the buffer handling of the C library printf function</li>
<li>You don’t have to handle the flag characters</li>
<li>You don’t have to handle field width</li>
<li>You don’t have to handle precision</li>
<li>You don’t have to handle the length modifiers</li>

**Repo:**
**GitHub repository: printf**

# mandatory
**1. Education is when you read the fine print. Experience is what you get if you don't**
# mandatory


Handle the following conversion specifiers:

<li>d</li>
<li>i</li>
<li>You don’t have to handle the flag characters</li>
<li>You don’t have to handle field width</li>
<li>You don’t have to handle precision</li>
<li>You don’t have to handle the length modifiers</li>

**Repo:**

**GitHub repository: printf**


**2. With a face like mine, I do better in print**

# advanced


Handle the following custom conversion specifiers:

<li>b: the unsigned int argument is converted to binary</li>

alex@ubuntu:~/c/printf$ cat main.c
#include "main.h"

/**
 * main - Entry point
 *
 * Return: Always 0
 */
int main(void)
{
    _printf("%b\n", 98);
    return (0);
}
alex@ubuntu:~/c/printf$ gcc -Wall -Wextra -Werror -pedantic -std=gnu89 main.c
alex@ubuntu:~/c/printf$ ./a.out
1100010
alex@ubuntu:~/c/printf$

Repo:

    GitHub repository: printf


**3. What one has not experienced, one will never understand in print**

# advanced


Handle the following conversion specifiers:
    u
    o
    x
    X
    You don’t have to handle the flag characters
    You don’t have to handle field width
    You don’t have to handle precision
    You don’t have to handle the length modifiers

Repo:

    GitHub repository: printf


**4. Nothing in fine print is ever good news**

# advanced


Use a local buffer of 1024 chars in order to call write as little as possible.

Repo:

    GitHub repository: printf


**5. My weakness is wearing too much leopard print**

# advanced


Handle the following custom conversion specifier:

    S : prints the string.
    Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)**

alex@ubuntu:~/c/printf$ cat main.c
#include "main.h"

/**
 * main - Entry point
 *
 * Return: Always 0
 */
int main(void)
{
    _printf("%S\n", "Best\nSchool");
    return (0);
}
alex@ubuntu:~/c/printf$ gcc -Wall -Wextra -Werror -pedantic -std=gnu89 main.c
alex@ubuntu:~/c/printf$ ./a.out
Best\x0ASchool
alex@ubuntu:~/c/printf$

Repo:

    GitHub repository: printf


**6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print**

# advanced


Handle the following conversion specifier: p.

    You don’t have to handle the flag characters
    You don’t have to handle field width
    You don’t have to handle precision
    You don’t have to handle the length modifiers

Repo:

    GitHub repository: printf


**7. The big print gives and the small print takes away**

# advanced


Handle the following flag characters for non-custom conversion specifiers:

    +
    space
    #

Repo:

    GitHub repository: printf


**8**. Sarcasm is lost in print

# advanced


Handle the following length modifiers for non-custom conversion specifiers:

    l
    h
Conversion specifiers to handle: d, i, u, o, x, X

Repo:

    GitHub repository: printf


**9**. Print some money and give it to us for the rain forests

# advanced

Handle the field width for non-custom conversion specifiers.

Repo:

    GitHub repository: printf


**10**. The negative is the equivalent of the composer's score, and the print the performance

# advanced


Handle the precision for non-custom conversion specifiers.

Repo:

    GitHub repository: printf


**11**. It's depressing when you're still around and your albums are out of print

# advanced


Handle the 0 flag character for non-custom conversion specifiers.

Repo:

    GitHub repository: printf


**12**. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection

# advanced


Handle the - flag character for non-custom conversion specifiers.

Repo:

    GitHub repository: printf


**13**. Print is the sharpest and the strongest weapon of our party

# advanced

Handle the following custom conversion specifier:

    r: prints the reversed string

Repo:

    GitHub repository: printf


**14**. The flood of print has turned reading into a process of gulping rather than savoring

# advanced


Handle the following custom conversion specifier:

    R: prints the rot13'ed string

Repo:

    GitHub repository: printf


**15**. 

# advanced


All the above options work well together.

Repo:

    GitHub repository: printf


