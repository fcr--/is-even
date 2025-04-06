# sed

## String pattern
Contributed by: [fcr--](https://github.com/fcr--)

Check the last digit of the decimal representation:
```sed
s/^[0-9]*[02468]$/even/; t
s/.*/not even/
```

Test it by sending a number through the standard input:
```bash
$ echo 42 | sed -f iseven.sed
even
```
