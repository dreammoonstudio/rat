rat
===

Just an attempt to create another programming language

Program Syntax:
---------------
### 1. Lexical Rules

letter ::= a | b | ... | z | A | B | ... | Z
digit  ::= 0 | 1 | ... | 9
id     ::= letter \{ letter | digit | _ \}
intcon ::= digit \{digit\}
fltcon ::= \{digit\} . \{digit\} \[e\] \[ + \]