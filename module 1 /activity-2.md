#Activity 2: Logic Building Challenge Students solve progressively complex logical problems using flowcharts and pseudocode before implementing them in code.give me the solutions
#Solutions

Aim: To develop logical thinking by solving problems using flowcharts, pseudocode, and Python programs, starting from simple problems and progressing to more complex ones.

## Problem 1: Check whether a number is even or odd

### Flowchart

Start

Input number N

Is N % 2 = 0?

Yes

Print Even

No

Print Odd

Stop

Pseudocode

```
START
INPUT N
IF N MOD 2 = 0
    PRINT "Even"
ELSE
    PRINT "Odd"
END IF
STOP
```

Python code

```
n = int(input("Enter a number: "))if n % 2 == 0:    print("Even number")else:    print("Odd number")
```

Example output: `Enter a number: 8` → `Even number`

## Problem 2: Find the largest of three numbers

### Flowchart

Start

Input A, B, C

Is A ≥ B and A ≥ C?

Yes

Largest = A

No

Is B ≥ A and B ≥ C?

Yes

Largest = B

No

Largest = C

Stop

Pseudocode

```
START
INPUT A, B, C

IF A >= B AND A >= C
    PRINT A
ELSE IF B >= A AND B >= C
    PRINT B
ELSE
    PRINT C
END IF

STOP
```

Python code

```
a = int(input("Enter first number: "))b = int(input("Enter second number: "))c = int(input("Enter third number: "))if a >= b and a >= c:    print("Largest:", a)elif b >= a and b >= c:    print("Largest:", b)else:    print("Largest:", c)
```

Example: Inputs `10, 25, 15` → `Largest: 25`

## Problem 3: Calculate the factorial of a number

The factorial of a positive integer is the product of all integers from 1 to that number. For example, \\(5! = 5 \times 4 \times 3 \times 2 \times 1 = 120\\). Also, \\(0! = 1\\).

### Flowchart

Start

Input N (N ≥ 0)

Set fact = 1, i = 1

Is i ≤ N?

Yes

fact = fact × i

i = i + 1

Repeat the condition

No

Print fact

Stop

Pseudocode

```
START
INPUT N
fact = 1
i = 1

WHILE i <= N
    fact = fact * i
    i = i + 1
END WHILE

PRINT fact
STOP
```

Python code

```
n = int(input("Enter a non-negative integer: "))if n < 0:    print("Enter a non-negative integer")else:    fact = 1    for i in range(1, n + 1):        fact = fact * i    print("Factorial:", fact)
```

Example: Input `5` → `Factorial: 120`

## Problem 4: Check whether a number is prime

A prime number is a number greater than 1 that has exactly two positive factors: 1 and itself.

### Flowchart

Start

Input N

Is N ≤ 1?

Yes

Not prime

No

Check divisors from 2 to √N

Any divisor divides N exactly?

Yes

Not prime

No

Prime

Stop

Pseudocode

```
START
INPUT N

IF N <= 1
    PRINT "Not Prime"
ELSE
    prime = TRUE
    FOR i = 2 TO √N
        IF N MOD i = 0
            prime = FALSE
            BREAK
        END IF
    END FOR

    IF prime = TRUE
        PRINT "Prime"
    ELSE
        PRINT "Not Prime"
    END IF
END IF

STOP
```

Python code

```
n = int(input("Enter a number: "))if n <= 1:    print("Not a prime number")else:    prime = True    for i in range(2, int(n ** 0.5) + 1):        if n % i == 0:            prime = False            break    if prime:        print("Prime number")    else:        print("Not a prime number")
```

Example: Input `7` → `Prime number`

## Problem 5: Find the sum of digits of a number

Example: If the input is `1234`, the sum is \\(1 + 2 + 3 + 4 = 10\\).

### Flowchart

Start

Input N

sum = 0, N = absolute value of N

Is N greater than 0?

Yes

digit = N % 10

sum += digit

N = N // 10

Repeat the condition

No

Print sum

Stop

Pseudocode

```
START
INPUT N
N = ABS(N)
sum = 0

WHILE N > 0
    digit = N MOD 10
    sum = sum + digit
    N = N DIV 10
END WHILE

PRINT sum
STOP
```

Python code

```
n = abs(int(input("Enter a number: ")))total = 0while n > 0:    digit = n % 10    total += digit    n //= 10print("Sum of digits:", total)
```

Example: Input `1234` → `Sum of digits: 10`

## Summary of solutions

| Level      | Problem                  | Main concept                       |
| ---------- | ------------------------ | ---------------------------------- |
| 1 — Easy   | Even or odd              | `if-else`, modulus                 |
| 2 — Easy   | Largest of three numbers | Comparisons, conditions            |
| 3 — Medium | Factorial                | Loops, multiplication              |
| 4 — Medium | Prime number             | Loops, divisibility                |
| 5 — Medium | Sum of digits            | `while` loop, division and modulus |

Conclusion: These five problems help students progress from basic conditional statements to loops and mathematical logic. Each problem follows the same process: understand the problem, design a flowchart, write pseudocode, implement the solution in Python, and test the output.
