# test-f-string-with-variable-and-value

``` python
variable = 17

print(f"{variable=}")  # This is more space-efficient
print(f"variable={variable}") 
```

Output:

```
variable=17
variable=17
```

Both print statements work, but one has a neat shortcut where we can insert the variable and the value it represents all at once.
