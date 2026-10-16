 # Activity 2: Logic Building Challenge Students solve progressively complex logical problems using flowcharts and pseudocode before implementing them in code.

 # Activity 2: Logic Building Challenge

## 1. Aim

To improve students' logical thinking and problem-solving skills by solving problems using flowcharts and pseudocode before implementing them in a programming language.

## 2. Requirements

- Paper and pen
- Flowchart symbols
- Computer with a programming environment (Python, C, or Java)

## 3. Procedure

1. Divide students into small teams.
2. Give each team a logical problem to solve.
3. Ask students to identify the input, processing steps, and expected output.
4. Students write the solution using pseudocode.
5. Students draw a flowchart representing the logic.
6. Students implement the solution in a programming language.
7. Test the program with different inputs and correct any errors.

## 4. Challenge 1: Check Whether a Number Is Even or Odd

Problem: Read a number and determine whether it is even or odd.

### Pseudocode

```
START
INPUT number
IF number MOD 2 = 0 THEN
    PRINT "Even"
ELSE
    PRINT "Odd"
END IF
STOP
```

### Flowchart

START

Input number

Is number MOD 2 = 0?

YES

Print "Even"

NO

Print "Odd"

STOP

### Python Implementation

```
number = int(input("Enter a number: "))if number % 2 == 0:    print("Even")else:    print("Odd")
```

Example output:

```
Enter a number: 7
Odd
```

## 5. Challenge 2: Find the Largest of Three Numbers

Problem: Read three numbers and identify the largest number.

### Pseudocode

```
START
INPUT a, b, c
IF a >= b AND a >= c THEN
    PRINT a
ELSE IF b >= a AND b >= c THEN
    PRINT b
ELSE
    PRINT c
END IF
STOP
```

### Python Implementation

```
a = int(input("Enter first number: "))b = int(input("Enter second number: "))c = int(input("Enter third number: "))if a >= b and a >= c:    print("Largest:", a)elif b >= a and b >= c:    print("Largest:", b)else:    print("Largest:", c)
```

Example output:

```
Enter first number: 10
Enter second number: 25
Enter third number: 15
Largest: 25
```

## 6. Challenge 3: Calculate the Sum of Numbers from 1 to N

Problem: Read a positive integer \\(N\\) and calculate the sum of all integers from 1 to \\(N\\).

### Pseudocode

```
START
INPUT N
sum = 0
i = 1

WHILE i <= N
    sum = sum + i
    i = i + 1
END WHILE

PRINT sum
STOP
```

### Python Implementation

```
n = int(input("Enter a positive number: "))total = 0for i in range(1, n + 1):    total += iprint("Sum:", total)
```

Example output:

```
Enter a positive number: 5
Sum: 15
```

## 7. Expected Outcome

Students will learn to:

- Break complex problems into smaller steps.
- Develop algorithms using pseudocode.
- Represent algorithms using flowcharts.
- Convert logical solutions into executable programs.
- Test their programs and identify errors.

## 8. Conclusion

The Logic Building Challenge helps students develop systematic problem-solving skills. By preparing pseudocode and flowcharts before coding, students understand the program's logic and can implement solutions more effectively.
