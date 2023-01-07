The input type and output type of a function are fixed. So you can't write something like:

```haskell
f 4 = True
f 5 = 6
```

This is because the output type of `f` can be *either* `Bool`, as the first line implies, *or* a number