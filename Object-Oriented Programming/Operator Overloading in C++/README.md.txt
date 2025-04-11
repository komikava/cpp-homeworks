# Operator Overloading in C++

This program demonstrates operator overloading in C++ with the `Variant1` class. It supports various operators like addition, subtraction, multiplication, division, and increment/decrement for two variables.

## Operations:
1. **Addition**: `ob1 + ob2`
2. **Subtraction**: `ob1 - ob2`, `ob1 - m`, `m - ob1`
3. **Multiplication/Division**: `ob1 * m`, `ob1 / m`
4. **Increment/Decrement**: `ob1++`, `ob1--`

## Methods:
- **show()**: Displays object values.
- **operator+**: Adds two `Variant1` objects.
- **operator-**: Subtracts objects or a number.
- **operator*/ operator/**: Multiplies/divides by a number.
- **operator++/ operator--**: Postfix increment/decrement.

## Sample Output:
Initial values: ob1 = 10, ob2 = 20 ob2 = 5, ob2 = 15 ob1 + ob2: ob1 = 15, ob2 = 35 ...