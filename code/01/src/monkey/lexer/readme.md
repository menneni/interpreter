# Writing an interpreter in go
## Chapter 01

### lexer
Lexer does lexical analysis, converts given source code into tokens

Ex: ip:
"let x = 5 + 5;"

Op:
[
LET,
IDENTIFIER("x"),
EQUAL_SIGN,
INTEGER(5),
PLUS_SIGN,
INTEGER(5),
SEMICOLON
]