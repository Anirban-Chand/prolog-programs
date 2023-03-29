To determine length of a list using your own number system.
---

Ans:
```
length1([], 0).
length1([X|Rest], f(N)):-
    length1(Rest, N).
```
