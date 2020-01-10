[Issues]: https://github.com/Andre601/java-operators-cheatsheet/issues
[PRs]: https://github.com/Andre601/java-operators-cheatsheet/pulls

## Java Operators Cheatsheet
Site containing most, if not all known Java operators.  
If you find invalid information, or want to add missing one, feel free to [open an issue][Issues] or [open a PR][PRs] on the GitHub Repo (and source) of this site.

## Credits
This site is based on the one of [Cafeaulait.org][Cafeaulait] with some minor changes being made. All original credit goes to the people of that site.

## Operators

### Number Operators
Can be used to manipulate numbers.

| Operator: | Fuction:                     | Example:     |
| --------- | ---------------------------- | ------------ |
| `+`       | Addition.                    | [1.1](#11)   |
| `+=`      | Add and assign numbers.      | [1.2](#12)   |
| `-`       | Substraction.                | [1.3](#13)   |
| `-=`      | Substract and assign number. | [1.4](#14)   |
| `*`       | Multiplication.              | [1.5](#15)   |
| `*=`      | Multiply and assign number.  | [1.6](#16)   |
| `/`       | Division.                    | [1.7](#17)   |
| `/=`      | Divide and assign number.    | [1.8](#18)   |
| `%`       | Take remainder               | [1.9](#19)   |
| `%=`      | Take and assign remainder.   | [1.10](#110) |
| `++`      | Increase by 1.               | [1.11](#111) |
| `--`      | Decrease by 1.               | [1.12](#112) |

### Boolean Operators
May be used in if statements.

| Operator: | Fuction:                           | Example:   |
| --------- | ---------------------------------- | ---------- |
| `>`       | Greater than.                      | [2.1](#21) |
| `>=`      | Greater than or equal to.          | [2.2](#22) |
| `<`       | Less than.                         | [2.3](#23) |
| `<=`      | Less than or equal to.             | [2.4](#24) |
| `==`      | Is equal to.                       | [2.5](#25) |
| `!=`      | Is NOT equal to.                   | [2.6](#26) |
|           |                                    |            |
| `&&`      | Operator AND.                      | [2.7](#27) |
| `\|\|`    | Operator OR                        | [2.8](#28) |
|           | Ignore the \\. GitHub limitation.) |            |
|           |                                    |            |
| `!`       | Operator NOT.                      | [2.9](#29) |

### String Operators
Can be used to manipulate Strings.

| Operator: | Fuction:                      | Example:   |
| --------- | ----------------------------- | ---------- |
| `+`       | Concatate two Strings.        | [3.1](#31) |
| `+=`      | Concatate and assign Strings. | [3.2](#32) |

## Examples

### 1.1
```java
int i = 0;

// Add 1 to i.
i = i + 1;

// Will print 1.
System.out.prntln(i);
```

### 1.2
```java
int i = 0;

// Add 1 to i.
i += 1;

// Will print 1.
System.out.prntln(i);
```

### 1.3
```java
int i = 5;

// Remove 2 from i.
i - 2;

// Will print 3.
System.out.prntln(i);
```

### 1.4
```java
int i = 5;

// Remove 2 from i.
i -= 2;

// Will print 3.
System.out.prntln(i);
```

### 1.5
```java
int i = 1;

// Multiply i by 5.
i = i * 5;

// Will print 5.
System.out.prntln(i);
```

### 1.6
```java
int i = 1;

// Multiply i by 5.
i *= 5;

// Will print 5.
System.out.prntln(i);
```

### 1.7
```java
int i = 10;

// Divide i by 2.
i = i / 2;

// Will print 5.
System.out.prntln(i);
```

### 1.8
```java
int i = 10;

// Divide i by 2.
i /= 2;

// Will print 5.
System.out.prntln(i);
```

### 1.9
```java
int i = 21;

// Get remainder of 21 / 4.
i = i % 4;

// Will print 1.
System.out.prntln(i);
```

### 1.10
```java
int i = 21;

// Get the remainder of 21 / 4.
i %= 4;

// Will print 1.
System.out.prntln(i);
```

### 1.11
```java
int i = 0;

// Increase by 1.
i++;

// Will print 1.
System.out.println(i);

// ====================

// Usage in a for loop.
for(int i = 0; i < 10; i++){
    System.out.prntln(i);
}
```

### 1.12
```java
int i = 10;

// Decrease by 1.
i--;

// Will print 9.
System.out.prntln(i);

// ====================

// Usage in a for loop.
for(int i = 10; i > 0; i--){
    System.out.prntln(i);
}
```
