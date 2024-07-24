# kr-c-calculator

**Plan**:

```
// maybe split string by whitespace?

// check for minus sign
// after that check if it is a letter
    // check for more letters - if whitespace - then it is a variable
    // if more letters - could be function
        // if satisfies valid function name, take it as the operand
        // check in main() if the number of operands match our function
// if we have a variable, get its value from the calculator variable storage array, and return its type as NUMBER (pushed to stack in main() - and return from getop() immediately (and cleanly)
```

**TODO**:
![image](https://github.com/user-attachments/assets/34f838be-9edf-4d92-94ce-6bb5c3d544ad)