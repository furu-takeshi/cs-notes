# Boolean Logic

## 1. Introduction

Boolean Algebra, invented by George Boole, uses only two values: True (1) and False (0). It is the basis for all digital circuit operations.

## 2. Logic Gates

Logic gates are electronic circuits that implement the Boolean logic operations.

| Gate  | Symbol      | Operation      | Truth Table                                        |
| :---- | :---------- | :------------- | :------------------------------------------------- |
| **AND**   | $A \cdot B$   | (Multiplication) | Output is 1 only if **ALL** inputs are 1.          |
| **OR**    | $A + B$     | (Addition)     | Output is 1 if **ANY** input is 1.                 |
| **NOT**   | $\bar{A}$     | (Bar)          | Inverts the input (0 becomes 1, 1 becomes 0).      |

## 3. Derived Gates

-   **NAND** (NOT AND): Output is 0 only if **ALL** inputs are 1. (Universal Gate)
-   **NOR** (NOT OR): Output is 1 only if **ALL** inputs are 0. (Universal Gate)
-   **XOR** (Exclusive OR): Output is 1 only if the inputs are **DIFFERENT**.

## 4. De Morgan's Laws (Crucial for Simplification)

These laws help simplify and convert logic expressions:

-   $\overline{A \cdot B} = \bar{A} + \bar{B}$
    -   The complement of an AND is the OR of the complements.
-   $\overline{A + B} = \bar{A} \cdot \bar{B}$
    -   The complement of an OR is the AND of the complements.
