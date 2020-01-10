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

| Operator: | Fuction:                     | Example: |
| --------- | ---------------------------- | -------- |
| `+`       | Addition.                    | 1.1      |
| `+=`      | Add and assign numbers.      | 1.2      |
| `-`       | Substraction.                | 1.3      |
| `-=`      | Substract and assign number. | 1.4      |
| `*`       | Multiplication.              | 1.5      |
| `*=`      | Multiply and assign number.  | 1.6      |
| `/`       | Division.                    | 1.7      |
| `/=`      | Divide and assign number.    | 1.8      |
| `%`       | Take remainder               | 1.9      |
| `%=`      | Take and assign remainder.   | 1.10     |
| `++`      | Increase by 1.               | 1.11     |
| `--`      | Decrease by 1.               | 1.12     |

### Boolean Operators
May be used in if statements.

| Operator: | Fuction:                     | Example: |
| --------- | ---------------------------- | -------- |
| `>`       | Greater than.                | 2.1      |
| `>=`      | Greater than or equal to.    | 2.2      |
| `<`       | Less than.                   | 2.3      |
| `<=`      | Less than or equal to.       | 2.4      |
| `==`      | Is equal to.                 | 2.5      |
| `!=`      | Is NOT equal to.             | 2.6      |


## Examples

### 1.1
We create an Integer with value 0, print this in the terminal, add 1 and print again.

```java
int i = 0;

// Will print 0.
System.out.prntln(i);

// Add 1 to i.
i = i + 1;

// Will print 1.
System.out.prntln(i);
```
