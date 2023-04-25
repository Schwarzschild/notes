# Python

Python
- [x] [map/reduce](https://stackabuse.com/map-filter-and-reduce-in-python-with-examples/)
- [x] lazy
- [x] iterators
- [x] generators
* def generate_integers(n):
*     i = 0 # Make this -1 to start from zero
*     while i < n:
*         i += 1
*         yield i
- [x] Recursion- fibonacci - when is recursion good? Trees and graphs. 
- [When to Loop? When to recurse?](https://betterprogramming.pub/when-to-loop-when-to-recurse-b786ad8977de)

```python
def factorial(x):
     if x == 1:
         return 1
     else:
         return (x * factorial(x-1))
```

- [x] [Slots](https://wiki.python.org/moin/UsingSlots)
* a class variable that is usually assigned a sequence of strings that are variable names used by instances.
* Reserve separate memory for those vars outside of the class dict.
- [x] Stacks - LIFO list - append() and pop()
- [x] from collections import deque # (doubly linked list) O(1)
- [x] decorators
    - [x] from functools import wraps
- [x] itertools: Combinations/permutations
- [x] functools: lru_cache, partial, 
- [x] Properties 
- [x] inspection - getattr()
- [x] modify class - setattr()
- [x] Why is p3 better than p2? only one way
- [x] Typed args float string ?
- [x] duck (the) typing - relates to dynamic typing - write without caring what types things are but make the code work independent of that.  __len__() is an example.
- [x] Boto3 - The AWS SDK for Python
- [ ] classC(metaclass=M): vs __metaclass__ = M
- [x] walrus operator print(i := 7)
* words = []
* while (word := input("Enter word: ")) != "quit":
*     words.append(word)
* print(words)
- [x] How to eliminate lots of nested if/then/else blocks? case or dicts
- [x] weakref - defer garbage collection until necessary but allow it to happen.

