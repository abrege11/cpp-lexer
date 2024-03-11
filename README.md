# senior-project-compiler
This is my senior project, I plan on creating a simple conpiler that will later be used to write another compiler. 

This is a very ambitious project that I started in December of 2023 over winter break of my junior year of university at NMU (Northern Michigan University). I completed the first version of the lexer in about a month with research factored in, and I haven't been able to work on much more up to now, Feb 16. due to a large course load. I hope to be able to expand this project little by little as the semester goes on.

<br><br><br><br><br><br><br><br><br>

# Documentation

## 1.00 - All valid inputs
<br> **Types**: `integer`, `double`, `boolean`, `string`, `character`, `array`
<br> **Operators**: `+`, `-`, `*`, `/`, `%`, `&&`, `||`, `!`, `=`, `!=`, `==`, `<`, `<=`, `>`, `>=`
<br> **Misc**: `//`, `;`
<br> **Statments/Loops**: `if`, `elif`, `else`, `while`, `for`, `return`, `print()`



## 1.01 - Declarations:
<br> `<type> <var> = <val>;`
<br><br>-  `integer i = 1;`
<br>- `double d = 1.1;`
<br>- `boolean b = True; | False;`
<br>- `string s = "this is a string";`
<br>- `character c = 'c';`
<br>- `array arr = [integer];`
<br>

## 1.02 - Token Types:
**Identifier**: `variable names`, `function names` <br><br>
**Keyword**: Keywords with special function in langauge (`for`, `if`, `while`) <br><br>
**Numeric Literal**: Numeric values (`ints`, `doubles`)<br><br>
**String Literal**: Data enclosed in quotes `" "` <br><br>
**Boolean Literal**: `True` or `False`<br><br>
**Character Literal**: Single characters (`'a'`, `'b'`, `'1'`, `'2'`)<br><br>
**Punctuation**: Commas `,` and semicolons `;`<br><br>
**Comments**: Anything on the same line and proceeding `//`<br><br>
**Whitespace**: `spaces`, `tabs`, `newlines`<br><br>
**EOF**: indication of end of source file<br><br>


### Operators:
- Arithmetic:
    - addition: +
    - subtraction: -
    - division: /
    - multiplication: *
    - modulus: %
- Rational:
    - less than: <
    - less than or equal to: <=
    - greater than: >
    - greater than or equal to: >=
    - equal to: ==
    - not equal to: != 
- Assignment:
    - assign to: = 
- Logical:
    - logical and: &&
    - logical or: ||
    - logical not: ! <br>
