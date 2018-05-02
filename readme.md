# Starting out with Python, 4:th Edition Toni Gaddis
This book is praised for its pedagogical approach to teaching Python. You
can learn a lot from it, but there are a few confusing and downright incorrect
parts in the book that I need to point out for my students, hence this unofficial
errata which is in no way endorsed by Pearson. If you want to contribute to this
errata, just clone it and make a pull request.

## Chapter 2
53: The program development cycle is oversimplified. Many programmers prefer to
(write tests before the rest of the code)[https://en.wikipedia.org/wiki/Test-driven_development].
There are far more types of errors than syntax errors and logic errors, such as name errors and type errors just to
name 2.
65: Incorrectly states that the first character of a Python function can not be
a letter in another language than English. Try this example in Idle:
```
>>> ålandsfärja = "Silja Line"
>>>
```
It *is* however required that all standard library code use ascii letters for
variables. You can read more in (PEP3131)[https://www.python.org/dev/peps/pep-3131/].

## Chapter 5
233: Introduces the terminology void-function from C which is confusing because
all functions in Python return a value, but that value can be None.

234: Repeats the incorrect statement about naming in Python, see Chapter 2 page 53.

## Chapter 6
311: Please do not use Notepad, ever. Atom is better in every way and free. If
you happen to like Notepad, at least switch to Notepad++. The time it takes will
be worth it in terms of shorter debugging times.

## Chapter 12
The text on recursion is a bit too negative. [Quicksort](https://en.wikipedia.org/wiki/Quicksort) is one
of the fastest sorting algorithms and it requires recursion for its implementation.
