## gcd

### Instructions

Write a program that takes two strings representing two strictly positive
integers that fit in an int.

Display their greatest common divisor followed by a newline (It is always a
strictly positive integer).

If the number of parameters is not 2, display a newline.

All arguments tested will be valid positive `int` values.

Example of output :

```console
student@ubuntu:~/student/gcd$ go build
student@ubuntu:~/student/gcd$ ./gcd 42 10 | cat -e
2$
student@ubuntu:~/student/gcd$ ./gcd 42 12 | cat -e
6$
student@ubuntu:~/student/gcd$ ./gcd 14 77 | cat -e
7$
student@ubuntu:~/student/gcd$ ./gcd 17 3 | cat -e
1$
student@ubuntu:~/student/gcd$ ./gcd | cat -e
$
student@ubuntu:~/student/gcd$ ./gcd 50 12 4 | cat -e
$
student@ubuntu:~/student/gcd$
```