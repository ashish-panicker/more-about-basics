# More basic concepts

Here's the definition of an **Armstrong Number** in **Markdown format**:  

## Armstrong Number

An **Armstrong number** is a number that is equal to the sum of its own digits each raised to the power of the number of digits.

## Formula

For an _n_-digit number:

\[
\text{Sum of each digit}^n = \text{Original Number}
\]

## Examples

1. **153** (3-digit number)
   \[
   1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153
   \]

2. **9474** (4-digit number)
   \[
   9^4 + 4^4 + 7^4 + 4^4 = 6561 + 256 + 2401 + 256 = 9474
   \]

3. **9475** (Not an Armstrong number)
   \[
   9^4 + 4^4 + 7^4 + 5^4 = 6561 + 256 + 2401 + 625 = 9843 \neq 9475
   \]

## Steps to Check Armstrong Number

1. **Count the number of digits** in the given number.
2. **Extract each digit** one by one.
3. **Raise each digit to the power of the total digits** and compute the sum.
4. **Compare the sum** with the original number:
   - If they are equal, the number is an **Armstrong number**.
   - Otherwise, it is **not an Armstrong number**.

---
```
