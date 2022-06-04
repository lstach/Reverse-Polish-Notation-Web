# Reverse-Polish-Notation-Web
Web app that converts formulas given in infix notation and converts it into Reverse Polish Notation (RPN) before solving.

Infix notation (what is typically used for Math formulas) is hard for computers to evaluate, because you are effectively going back and forth throughout the expression to evaluate it, which computers cannot do well.  RPN is a notation schema that allows a Math expression to be evaluated from left to right.

This program converts the given infix expression into RPN using the Shunting Yard Algorithm.

Built using JavaScript and HTML.

Right now the program doesn't have a parser, necessitating that all tokens be separated with a " " (space).  There's also no code for error catching. Furthermore it's just a very plain and simple HTML page and needs to be made prettier using CSS.
