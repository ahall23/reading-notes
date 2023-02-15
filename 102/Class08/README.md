# Expressions and Operations

There are two types of expressions: those that have side effects like assigning values) and those that purely evaluate. x = 8 is an example of the first type. notice that it uses an = sign to assign the value seven to the variable x.

4+4 is an expression that uses a + sign to produce the value of 8.

## Shorthand operator Meaning

1. Assignment x = f() x = f()
2. Addition assignment x += f() x = x + f()
3. Subtraction assignment x -= f() x = x - f()
4. Multiplication assignment x _= f() x = x _ f()
5. Division assignment x /= f() x = x / f()
6. Remainder assignment x %= f() x = x % f()
7. Exponentiation assignment x **= f() x = x ** f()
8. Left shift assignment x <<= f() x = x << f()
9. Right shift assignment x >>= f() x = x >> f()
10. Unsigned right shift assignment x >>>= f() x = x >>> f()
11. Bitwise AND assignment x &= f() x = x & f()
12. Bitwise XOR assignment x ^= f() x = x ^ f()
13. Bitwise OR assignment x |= f() x = x | f()
14. Logical AND assignment x &&= f() x && (x = f())
15. Logical OR assignment x ||= f() x || (x = f())
16. Nullish coalescing assignment x ??= f() x ?? (x = f())
17. Assigning to properties

### Loops and iteration

loops are a way to do something repeatedly.  
_example_ </br>
for (let step = 0; step < 5; step++) {
// Runs 5 times, with values of step 0 through 4.
console.log("Walking east one step");
}

> The statements for loops provided in JavaScript are:

1. for statement
2. do...while 3. statement
3. while statement
4. labeled statement
5. break statement
6. continue statement
7. for...in statement
8. for...of statement
