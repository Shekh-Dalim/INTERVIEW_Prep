
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

Q: What is nested if-else? Give an example.
```
An `if` or `if-else` inside another `if` or `else` block.
```
Q: Which C++ concepts are used to create pattern programs?
```
Nested loops (especially for loops)
Conditional statements (e.g., if, else)
Control flow (break, continue)
Sometimes functions (for modularity)
Basic I/O (cin, cout)
```

 Can pattern programs be solved using recursion?
```
Yes, but it's uncommon. Recursion can be used to print patterns, though it's usually less efficient and harder to understand than loops.
```

What is a loop in C++?
```
A loop is a control structure used to execute a block of code repeatedly based on a condition.
```

Difference between while and do-while loop?
```
while: Condition checked before loop body.
do-while: Condition checked after, so runs at least once.
```
