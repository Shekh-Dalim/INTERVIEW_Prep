
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
Yes, but it's uncommon. Recursion can be used to print patterns, though it's usually less
efficient and harder to understand than loops.
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

What is a switch statement in C++?
```
The switch statement allows us to select one of many code blocks to be executed, based on the value of a variable or expression.
```

4. Is break necessary in switch?
```
No, but without break, execution will continue ("fall through") into the next case, 
which may cause unexpected behavior.
```
5. Can we use float or string in switch?
```
No. switch only works with integral types like int, char, or enum.
You cannot use float or string in the switch expression.
```

What is the purpose of default in switch?
```
default runs when no matching case is found. It’s like the else part of if-else.
```

Can we use variables in case labels?
```
No. case labels must be constant expressions.
```

 Can we use enum in a switch statement?
```
Yes, enum values are constants and can be used in switch.
```

What happens if two case values are the same?
```
The compiler will throw a duplicate case label error. All case values must be unique.
```

Can switch handle ranges like case 1 ... 5?
```
No, standard C++ doesn't support range in case. You must use if-else for ranges.
(C++23 introduces case (1 ... 5):, but it's compiler-dependent.)
```
15. What are common mistakes when using switch?
```
Forgetting break
Using float/string in switch
Using variables in case label
Not handling default
Duplicate case values
```
