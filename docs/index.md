---
title: Java Operators Cheatsheet
---

[Issues]: https://github.com/Andre601/java-operators-cheatsheet/issues
[PRs]: https://github.com/Andre601/java-operators-cheatsheet/pulls
[Cafeaulait]: http://www.cafeaulait.org/course/week2/03.html

Site containing most, if not all known Java operators.  
If you find invalid information, or want to add missing one, feel free to [open an issue][Issues] or [open a PR][PRs] on the GitHub Repo (and source) of this site.

## Credits
This site is based on the one of [Cafeaulait.org][Cafeaulait] with some minor changes being made. All original credit goes to the people of that site.

## Operators

<!-- NOTE                                                                                     -->
<!-- The table(s) below may look broken, but are perfectly find on the actual website itself. -->
<!-- This seems to be a bug/issue with GitHub's markdown rendering system.                    -->

### Number Operators
Can be used to manipulate numbers.

| Operator: | Function:                    | Example:     |
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

| Operator: | Fuction:                            | Example:   |
| --------- | ----------------------------------- | ---------- |
| `>`       | Greater than.                       | [2.1](#21) |
| `>=`      | Greater than or equal to.           | [2.2](#22) |
| `<`       | Less than.                          | [2.3](#23) |
| `<=`      | Less than or equal to.              | [2.4](#24) |
| `==`      | Is equal to.                        | [2.5](#25) |
| `!=`      | Is NOT equal to.                    | [2.6](#26) |
|           |                                     |            |
| `&&`      | Operator AND.                       | [2.7](#27) |
| `||`      | Operator OR                         | [2.8](#28) |
|           |                                     |            |
| `!`       | Operator NOT.                       | [2.9](#29) |

### String Operators
Can be used to manipulate Strings.

| Operator: | Function:                     | Example:   |
| --------- | ----------------------------- | ---------- |
| `+`       | Concatate two Strings.        | [3.1](#31) |
| `+=`      | Concatate and assign Strings. | [3.2](#32) |

### Bit Operators

| Operator: | Function:                                 | Example:     |
| --------- | ----------------------------------------- | ------------ |
| `~`       | Bitwise NOT.                              | [4.1](#41)   |
| `|`       | Bitwise OR.                               | [4.2](#42)   |
| `|=`      | Bitwise OR and assign.                    | [4.3](#43)   |
| `^`       | Bitwise XOR.                              | [4.4](#44)   |
| `^=`      | Bitwise XOR and assign.                   | [4.5](#45)   |
| `&`       | Bitwise AND.                              | [4.6](#46)   |
| `&=`      | Bitwise AND and assign.                   | [4.7](#47)   |
| `>>`      | Signed bits shifting right.               | [4.8](#48)   |
| `>>=`     | Signed bits shifting right and assigning. | [4.9](#49)   |
| `<<`      | Shift bits left.                          | [4.10](#410) |
| `<<=`     | Shift bits left and assigning.            | [4.11](#411) |
| `>>>`     | Unsigned bit shifting right.              | [4.12](#412) |
| `>>>=`    | Unsigned bit shifting right and assign.   | [4.13](#413) |


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

### 2.1
```java
// Gets a random value between 0 and 10.
int a = new Random().nextInt(10);
int b = 9;

// Will be true when a is more than 9.
if(a > b)
    System.out.prntln("A is larger than B");
```

### 2.2
```java
// Gets a random value between 0 and 10.
int a = new Random().nextInt(10);
int b = 9;

// Will be true when a is more than or exactly 9.
if(a >= b)
    System.out.prntln("A is greater or equal to B");
```

### 2.3
```java
// Gets a random value between 0 and 10.
int a = new Random().nextInt(10);
int b = 1;

// Will be true when a is less than 1;
if(a < b)
    System.out.prntln("A is less than B");
```

### 2.4
```java
// Gets a random value between 0 and 10.
int a = new Random().nextInt(10);
int b = 9;

// Will be true when a is less or equal to 1.
if(a <= b)
    System.out.prntln("A is less than or equal to B");
```

### 2.5
```java
// Gets a random value between 0 and 10.
int a = new Random().nextInt(10);
int b = 10;

// Will be true when a is equal to 10.
if(a == b)
    System.out.prntln("A is equal to B");
```

### 2.6
```java
// Gets a random value between 0 and 10.
int a = new Random().nextInt(10);
int b = 10;

// Will be true when a is between 0 and 9.
if(a != b)
    System.out.prntln("A is not equal to B");
```

### 2.7
```java
// Gets a random value between 0 and 10.
int a = new Random().nextInt(10);
int b = 5;
int c = 10;

// Will be true when a is more than 5 AND less than 10.
if((a > b) && (a < c))
    System.out.prntln("A is greater than B and less than C.")
```

### 2.8
```java
// Gets a random value between 0 and 10.
int a = new Random().nextInt(10);
int b = 0;
int c = 10;

// Will be true when a is equal to 10 OR equal to 0.
if((a == b) || (a == c))
    System.out.prntln("A is equal to B or C);
```

### 2.9
```java
// Getting a basic true/false with the Random function
int i = new Random().nextInt(1);

String text = "FooBar";
if(i == 1)
    text = "Hello World!";

// Will be true if the String text is not equal to "Hello World!".
if(!text.equals("Hello World!"))
    System.out.prntln("Not Hello world!");
```

### 3.1
```java
String text = "Foo";

// Concatate the extra text.
text = text + "Bar";

// Will print "FooBar".
System.out.prntln(text);
```

### 3.2
```java
String text = "Foo";

// Concatate and directly assign the extra text.
text += "Bar";

// Will print "FooBar".
System.out.prntln(text);
```

### 4.1
```java

```

### 4.2
```java
/*
 * Bitwise OR is useful for try-catch where multiple
 * Exceptions can be thrown by one or multiple methods.
 *
 * Reduces the amount of catch-blocks significantly.
 */
public void performStuff(){
    try{
        MyClass.doStuff();
    }catch(IOException | NullPointerException ex){
        ex.printStackTrace();
    }
}
```

### 4.3
```java

```

### 4.4
```java

```

### 4.5
```java

```

### 4.6
```java

```

### 4.7
```java

```

### 4.8
```java
// We first get the currently used RAM and max allocated RAM.
long used = ManagementFactory.getMemoryMXBeam().getHeapMemoryUsage().getUsed();
long max  = ManagementFactory.getMemoryMXBeam().getHeapMemoryUsage().getMax();

// We shift both values by 20, turning them info MB value.
used = used >> 20;
max  = max >> 20;

System.out.prntln("RAM usage: " + used + "/" + max + "MB");
```

### 4.9
```java
// We first get the currently used RAM and max allocated RAM.
long used = ManagementFactory.getMemoryMXBeam().getHeapMemoryUsage().getUsed();
long max  = ManagementFactory.getMemoryMXBeam().getHeapMemoryUsage().getMax();

// We shift both values by 20, turning them info MB value.
used >>= 20;
max  >>= 20;

System.out.prntln("RAM usage: " + used + "/" + max + "MB");
```

### 4.10
```java

```

### 4.11
```java

```

### 4.12
```java

```

### 4.13
```java

```
