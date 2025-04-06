# sed

## String pattern
Contributed by: [fcr--](https://github.com/fcr--)

```sed
s/^[0-9]*[02468]$/even/; t
s/.*/not even/
```
```bash
echo 42 | sed -f iseven.sed
```
