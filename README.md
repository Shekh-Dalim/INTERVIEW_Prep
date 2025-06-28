
Q:  What is the difference between `if`, `if-else`, and `else-if`?
```
Edit
- `if`: Executes a block if a condition is true.
- `if-else`: Executes one block if true, another if false.
- `else-if`: Allows checking multiple conditions in sequence.
```
Q: Find the largest among three numbers using if-else.

```
int a, b, c;
cin >> a >> b >> c;
if (a >= b && a >= c)
    cout << "Largest is: " << a;
else if (b >= a && b >= c)
    cout << "Largest is: " << b;
else
    cout << "Largest is: " << c;
```

Q: What happens if you miss the curly braces `{}` in if-else blocks?
```
Only the next immediate statement is considered part of the block. This often leads to logical bugs.
```

Q8. What is nested if-else? Give an example.
```
An `if` or `if-else` inside another `if` or `else` block.
```
