## Operator Snippets

Min and max of a set.
```tla
Min(s) == CHOOSE x \in s : \A y \in s : x <= y
Max(s) == CHOOSE x \in s : \A y \in s : x >= y
```

Range of a function.
```tla
Range(f) == {f[x] : x \in DOMAIN f}
```
