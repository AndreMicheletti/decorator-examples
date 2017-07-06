# decorator-examples

See here some decorator implementation examples in Python 3.6

## Decorators

- [require_login](https://github.com/AndreMicheletti/decorator-examples/blob/master/decorator_examples.py#L10)
Exit the function depending on the return of another function

- [ensure_file](https://github.com/AndreMicheletti/decorator-examples/blob/master/decorator_examples.py#L21)
Ensure the file exists, and if not create it

- [ensure_file2](https://github.com/AndreMicheletti/decorator-examples/blob/master/decorator_examples.py#L33)
Same as before, but more flexible

- [string_format](https://github.com/AndreMicheletti/decorator-examples/blob/master/decorator_examples.py#L47)
Make sure that all string arguments passed to a function are formatted the same way

- [cached](https://github.com/AndreMicheletti/decorator-examples/blob/master/decorator_examples.py#L70)
Cache the result of functions to reduce CPU time

- [timer](https://github.com/AndreMicheletti/decorator-examples/blob/master/decorator_examples.py#L91)
Create a timer to track the time spent on the function call

- [profile_and_save](https://github.com/AndreMicheletti/decorator-examples/blob/master/decorator_examples.py#L105)
Same as before, but maintaining a history in a `.json` file

## Tests

Here are the results of the tests in the file end

```Shell
call to large_function took 1.100401 seconds
call to large_function took 0.000000 seconds
a
b
d
ef
f
g
```

