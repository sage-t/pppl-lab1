# Lab 1 Writeup
* Sage Thomas

## Questions
1. TODO

2. 
```
(a) pi at line 4 is bound to the pi variable declared at line 3 because it is the most recently defined in the scope. The pi at line 7 is bound to the pi variable declared at line 1 because it is the only pi variable declared within its scope.

(b) 
x @ line 3 is bound to line 2 because the x function parameter is the most recently declared x in scope.
x @ line 6 and 10 are bound to line 5 because the x at line 5 is a placeholder x within the case statement. 
x @ line 13 is bound to line 1 because that is the only declared x in scope. 
```

3.
```
The body of g is well typed with type ((Int, Int), Int).

[if x == 0]
(b, 1):((Int, Int), Int) because
    b: (x, 3)
        x: Int
        3: Int
    1: Int
[else]
(b, a + 2):((Int, Int), Int) because
    b: (x, 3)
        x: Int
        3: Int
    a + 2:
        a: Int
        2: Int
```


