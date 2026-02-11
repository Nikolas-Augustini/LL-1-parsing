# LL-1-parsing
Developing a postfix arithmetic parser with LL(1) compliant grammar. I was provided with the following grammar below:
| Non-Terminals | Terminals/Non-Terminals |
| ------------- | ------------- |
| expr	::=	  | num / lvalue / incrop expr / expr incrop / expr binop expr / (expr)  |
| lvalue	::=  | $expr |
| incrop	::=  | ++ / -- |
| binop	::=  | + / - / |
| num	::=  | 0 / 1 / 2 / 3 / 4 / 5 / 6 / 7 / 8 / 9 |

The goal of this project is to evolve the grammar into an LL(1) compliant grammar. This includes providing the necessary evidence that the grammar is LL(1) through first and follow sets, as well as a parse table. With the Grammar I create I will be developing a postfix parser.
