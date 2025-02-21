<!-- Obtained from https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2310.pdf chapter 6.4-6.10 -->
<!-- 'opt' subscript means this token is optional -->

*\<token\>* <br> &ensp;&ensp;&ensp;&ensp; *keyword* <br> &ensp;&ensp;&ensp;&ensp; *identifier* <br> &ensp;&ensp;&ensp;&ensp; *constant* <br> &ensp;&ensp;&ensp;&ensp; *string-literal* <br> &ensp;&ensp;&ensp;&ensp; *punctuator*

*\<preprocessing-token\>* <br> &ensp;&ensp;&ensp;&ensp; *header-name* <br> &ensp;&ensp;&ensp;&ensp; *identifier* <br> &ensp;&ensp;&ensp;&ensp; *pp-number* <br> &ensp;&ensp;&ensp;&ensp; *character-constant* <br> &ensp;&ensp;&ensp;&ensp; *string-literal* <br> &ensp;&ensp;&ensp;&ensp; *punctuator* <br> &ensp;&ensp;&ensp;&ensp; each non-whitespace character that isn't any of these

*\<keyword\>* <br> &ensp;&ensp;&ensp;&ensp; `auto` <br> &ensp;&ensp;&ensp;&ensp; `break` <br> &ensp;&ensp;&ensp;&ensp; `case` <br> &ensp;&ensp;&ensp;&ensp; `char` <br> &ensp;&ensp;&ensp;&ensp; `const` <br> &ensp;&ensp;&ensp;&ensp; `continue` <br> &ensp;&ensp;&ensp;&ensp; `default` <br> &ensp;&ensp;&ensp;&ensp; `do` <br> &ensp;&ensp;&ensp;&ensp; `double` <br> &ensp;&ensp;&ensp;&ensp; `else` <br> &ensp;&ensp;&ensp;&ensp; `enum` <br> &ensp;&ensp;&ensp;&ensp; `extern` <br> &ensp;&ensp;&ensp;&ensp; `float` <br> &ensp;&ensp;&ensp;&ensp; `for` <br> &ensp;&ensp;&ensp;&ensp; `goto` <br> &ensp;&ensp;&ensp;&ensp; `if` <br> &ensp;&ensp;&ensp;&ensp; `inline` <br> &ensp;&ensp;&ensp;&ensp; `int` <br> &ensp;&ensp;&ensp;&ensp; `long` <br> &ensp;&ensp;&ensp;&ensp; `register` <br> &ensp;&ensp;&ensp;&ensp; `restrict` <br> &ensp;&ensp;&ensp;&ensp; `return` <br> &ensp;&ensp;&ensp;&ensp; `short` <br> &ensp;&ensp;&ensp;&ensp; `signed` <br> &ensp;&ensp;&ensp;&ensp; `sizeof` <br> &ensp;&ensp;&ensp;&ensp; `static` <br> &ensp;&ensp;&ensp;&ensp; `struct` <br> &ensp;&ensp;&ensp;&ensp; `switch` <br> &ensp;&ensp;&ensp;&ensp; `typedef` <br> &ensp;&ensp;&ensp;&ensp; `union` <br> &ensp;&ensp;&ensp;&ensp; `unsigned` <br> &ensp;&ensp;&ensp;&ensp; `void` <br> &ensp;&ensp;&ensp;&ensp; `volatile` <br> &ensp;&ensp;&ensp;&ensp; `while` <br> &ensp;&ensp;&ensp;&ensp; `_Alignas` <br> &ensp;&ensp;&ensp;&ensp; `_Alignof` <br> &ensp;&ensp;&ensp;&ensp; `_Atomic` <br> &ensp;&ensp;&ensp;&ensp; `_Bool` <br> &ensp;&ensp;&ensp;&ensp; `_Complex` <br> &ensp;&ensp;&ensp;&ensp; `_Generic` <br> &ensp;&ensp;&ensp;&ensp; `_Imaginary` <br> &ensp;&ensp;&ensp;&ensp; `_Noreturn` <br> &ensp;&ensp;&ensp;&ensp; `_Static_assert` <br> &ensp;&ensp;&ensp;&ensp; `_Thread_local`  

*\<identifier\>* <br> &ensp;&ensp;&ensp;&ensp; *identifier-nondigit* <br> &ensp;&ensp;&ensp;&ensp; *identifier identifier-nondigit* <br> &ensp;&ensp;&ensp;&ensp; *identifier digit*

*\<identifier-nondigit\>* <br> &ensp;&ensp;&ensp;&ensp; *nondigit* <br> &ensp;&ensp;&ensp;&ensp; *universal-character-name*

*\<nondigit\>* <br> &ensp;&ensp;&ensp;&ensp; `_`<br> &ensp;&ensp;&ensp;&ensp; `a` <br> &ensp;&ensp;&ensp;&ensp; `b` <br> &ensp;&ensp;&ensp;&ensp; `c` <br> &ensp;&ensp;&ensp;&ensp; `d` <br> &ensp;&ensp;&ensp;&ensp; `e` <br> &ensp;&ensp;&ensp;&ensp; `f` <br> &ensp;&ensp;&ensp;&ensp; `g` <br> &ensp;&ensp;&ensp;&ensp; `h` <br> &ensp;&ensp;&ensp;&ensp; `i` <br> &ensp;&ensp;&ensp;&ensp; `j` <br> &ensp;&ensp;&ensp;&ensp; `k` <br> &ensp;&ensp;&ensp;&ensp; `l` <br> &ensp;&ensp;&ensp;&ensp; `m` <br> &ensp;&ensp;&ensp;&ensp; `n` <br> &ensp;&ensp;&ensp;&ensp; `o` <br> &ensp;&ensp;&ensp;&ensp; `p` <br> &ensp;&ensp;&ensp;&ensp; `q` <br> &ensp;&ensp;&ensp;&ensp; `r` <br> &ensp;&ensp;&ensp;&ensp; `s` <br> &ensp;&ensp;&ensp;&ensp; `t` <br> &ensp;&ensp;&ensp;&ensp; `u` <br> &ensp;&ensp;&ensp;&ensp; `v` <br> &ensp;&ensp;&ensp;&ensp; `w` <br> &ensp;&ensp;&ensp;&ensp; `x` <br> &ensp;&ensp;&ensp;&ensp; `y` <br> &ensp;&ensp;&ensp;&ensp; `z` <br> &ensp;&ensp;&ensp;&ensp; `A` <br> &ensp;&ensp;&ensp;&ensp; `B` <br> &ensp;&ensp;&ensp;&ensp; `C` <br> &ensp;&ensp;&ensp;&ensp; `D` <br> &ensp;&ensp;&ensp;&ensp; `E` <br> &ensp;&ensp;&ensp;&ensp; `F` <br> &ensp;&ensp;&ensp;&ensp; `G` <br> &ensp;&ensp;&ensp;&ensp; `H` <br> &ensp;&ensp;&ensp;&ensp; `I` <br> &ensp;&ensp;&ensp;&ensp; `J` <br> &ensp;&ensp;&ensp;&ensp; `K` <br> &ensp;&ensp;&ensp;&ensp; `L` <br> &ensp;&ensp;&ensp;&ensp; `M` <br> &ensp;&ensp;&ensp;&ensp; `N` <br> &ensp;&ensp;&ensp;&ensp; `O` <br> &ensp;&ensp;&ensp;&ensp; `P` <br> &ensp;&ensp;&ensp;&ensp; `Q` <br> &ensp;&ensp;&ensp;&ensp; `R` <br> &ensp;&ensp;&ensp;&ensp; `S` <br> &ensp;&ensp;&ensp;&ensp; `T` <br> &ensp;&ensp;&ensp;&ensp; `U` <br> &ensp;&ensp;&ensp;&ensp; `V` <br> &ensp;&ensp;&ensp;&ensp; `W` <br> &ensp;&ensp;&ensp;&ensp; `X` <br> &ensp;&ensp;&ensp;&ensp; `Y` <br> &ensp;&ensp;&ensp;&ensp; `Z`

*\<digit\>* <br> &ensp;&ensp;&ensp;&ensp; `0` <br> &ensp;&ensp;&ensp;&ensp; `1` <br> &ensp;&ensp;&ensp;&ensp; `2` <br> &ensp;&ensp;&ensp;&ensp; `3` <br> &ensp;&ensp;&ensp;&ensp; `4` <br> &ensp;&ensp;&ensp;&ensp; `5` <br> &ensp;&ensp;&ensp;&ensp; `6` <br> &ensp;&ensp;&ensp;&ensp; `7` <br> &ensp;&ensp;&ensp;&ensp; `8` <br> &ensp;&ensp;&ensp;&ensp; `9` 

*\<universal-character-name\>* <br> &ensp;&ensp;&ensp;&ensp; `\u` *hex-quad* <br> &ensp;&ensp;&ensp;&ensp; `\U` *hex-quad* *hex-quad*

*\<hex-quad\>* <br> &ensp;&ensp;&ensp;&ensp; *hexidecimal-digit* *hexidecimal-digit* *hexidecimal-digit* *hexidecimal-digit* 

*\<constant\>* <br> &ensp;&ensp;&ensp;&ensp; *integer-constant* <br> &ensp;&ensp;&ensp;&ensp; *floating-constant* <br> &ensp;&ensp;&ensp;&ensp; *enumeration-constant* <br> &ensp;&ensp;&ensp;&ensp; *character-constant*

*\<integer-constant\>* <br> &ensp;&ensp;&ensp;&ensp; *decimal-constant* *integer-suffix<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *octal-constant* *integer-suffix<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-constant* *integer-suffix<sub>opt</sub>* 

*\<decimal-constant\>* <br> &ensp;&ensp;&ensp;&ensp; *nonzero-digit* <br> &ensp;&ensp;&ensp;&ensp; *decimal-constant* *digit*

*\<octal-constant\>* <br> &ensp;&ensp;&ensp;&ensp; `0` <br> &ensp;&ensp;&ensp;&ensp; *octal-constant* *octal-digit*

*\<hexadecimal-constant\>* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-prefix* *hexadecimal-digit* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-constant* *hexadecimal-digit*
 
*\<hexadecimal-prefix\>* <br> &ensp;&ensp;&ensp;&ensp; `0x` <br> &ensp;&ensp;&ensp;&ensp; `0X`

*\<nonzero-digit\>* <br> &ensp;&ensp;&ensp;&ensp; `1` <br> &ensp;&ensp;&ensp;&ensp; `2` <br> &ensp;&ensp;&ensp;&ensp; `3` <br> &ensp;&ensp;&ensp;&ensp; `4` <br> &ensp;&ensp;&ensp;&ensp; `5` <br> &ensp;&ensp;&ensp;&ensp; `6` <br> &ensp;&ensp;&ensp;&ensp; `7` <br> &ensp;&ensp;&ensp;&ensp; `8` <br> &ensp;&ensp;&ensp;&ensp; `9`

*\<octal-digit\>* <br> &ensp;&ensp;&ensp;&ensp; `0` <br> &ensp;&ensp;&ensp;&ensp; `1` <br> &ensp;&ensp;&ensp;&ensp; `2` <br> &ensp;&ensp;&ensp;&ensp; `3` <br> &ensp;&ensp;&ensp;&ensp; `4` <br> &ensp;&ensp;&ensp;&ensp; `5` <br> &ensp;&ensp;&ensp;&ensp; `6` <br> &ensp;&ensp;&ensp;&ensp; `7`

*\<hexadecimal-digit\>* :== `0` <br> &ensp;&ensp;&ensp;&ensp; `1` <br> &ensp;&ensp;&ensp;&ensp; `2` <br> &ensp;&ensp;&ensp;&ensp; `3` <br> &ensp;&ensp;&ensp;&ensp; `4` <br> &ensp;&ensp;&ensp;&ensp; `5` <br> &ensp;&ensp;&ensp;&ensp; `6` <br> &ensp;&ensp;&ensp;&ensp; `7` <br> &ensp;&ensp;&ensp;&ensp; `8` <br> &ensp;&ensp;&ensp;&ensp; `9` <br> &ensp;&ensp;&ensp;&ensp; `a` <br> &ensp;&ensp;&ensp;&ensp; `b` <br> &ensp;&ensp;&ensp;&ensp; `c` <br> &ensp;&ensp;&ensp;&ensp; `d` <br> &ensp;&ensp;&ensp;&ensp; `e` <br> &ensp;&ensp;&ensp;&ensp; `f` <br> &ensp;&ensp;&ensp;&ensp; `A` <br> &ensp;&ensp;&ensp;&ensp; `B` <br> &ensp;&ensp;&ensp;&ensp; `C` <br> &ensp;&ensp;&ensp;&ensp; `D` <br> &ensp;&ensp;&ensp;&ensp; `E` <br> &ensp;&ensp;&ensp;&ensp; `F`

*\<integer-suffix\>* <br> &ensp;&ensp;&ensp;&ensp; *unsigned-suffix* *long-suffix<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *unsigned-suffix* *long-long-suffix* <br> &ensp;&ensp;&ensp;&ensp; *long-suffix unsigned-suffix<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *long-long-suffix* *unsigned-suffix<sub>opt</sub>*

*\<unsigned-suffix\>* <br> &ensp;&ensp;&ensp;&ensp; `u` <br> &ensp;&ensp;&ensp;&ensp; `U`

*\<long-suffix\>* <br> &ensp;&ensp;&ensp;&ensp; `l` <br> &ensp;&ensp;&ensp;&ensp; `L`

*\<long-long-suffix\>* <br> &ensp;&ensp;&ensp;&ensp; `ll` <br> &ensp;&ensp;&ensp;&ensp; `LL`

*\<floating-constant\>* <br> &ensp;&ensp;&ensp;&ensp; *decimal-floating-constant* <br> &ensp;&ensp;&ensp;&ensp; *hexidecimal-floating-constant* 

*\<decimal-floating-constant\>* <br> &ensp;&ensp;&ensp;&ensp; *fractional-constant* *exponent-part<sub>opt</sub>* *floating-suffix<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *digit-sequence* *exponent-part* *floating-suffix<sub>opt</sub>*

*\<hexadecimal-floating-constant\>* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-prefix* *hexadecimal-fractional-constant* <br> &ensp;&ensp;&ensp;&ensp; *binary-exponent-part* *floating-suffix<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-prefix* *hexadecimal-digit-sequence* <br> &ensp;&ensp;&ensp;&ensp; *binary-exponent-part* *floating-suffix<sub>opt</sub>*

*\<fractional-constant\>* <br> &ensp;&ensp;&ensp;&ensp; *digit-sequence<sub>opt</sub>* `.` *digit-sequence* <br> &ensp;&ensp;&ensp;&ensp; *digit-sequence* `.`

*\<exponent-part\>* <br> &ensp;&ensp;&ensp;&ensp; `e` *sign<sub>opt</sub>* *digit-sequence* <br> &ensp;&ensp;&ensp;&ensp; `E` *sign<sub>opt</sub>* *digit-sequence*

*\<sign\>* <br> &ensp;&ensp;&ensp;&ensp; `+` <br> &ensp;&ensp;&ensp;&ensp; `-`

*\<digit-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; *digit* <br> &ensp;&ensp;&ensp;&ensp; *digit-sequence* *digit*

*\<hexadecimal-fractional-constant\>* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-digit-sequence<sub>opt</sub>* `.` *hexadecimal-digit-sequence* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-digit-sequence* `.`

*\<binary-exponent-part\>* <br> &ensp;&ensp;&ensp;&ensp; `p` *sign<sub>opt</sub>* *digit-sequence* <br> &ensp;&ensp;&ensp;&ensp; `P` *sign<sub>opt</sub>* *digit-sequence*

*\<hexadecimal-digit-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-digit* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-digit-sequence* *hexadecimal-digit*

*\<floating-suffix\>* <br> &ensp;&ensp;&ensp;&ensp; `f` <br> &ensp;&ensp;&ensp;&ensp; `l` <br> &ensp;&ensp;&ensp;&ensp; `F` <br> &ensp;&ensp;&ensp;&ensp; `L`

*\<enumeration-constant\>* :== *identifier*

*\<character-constant\>* :== `'` *c-char-sequence* `'` <br> &ensp;&ensp;&ensp;&ensp; `L'` *c-char-sequence* `'` <br> &ensp;&ensp;&ensp;&ensp; `u'` *c-char-sequence* `'` <br> &ensp;&ensp;&ensp;&ensp; `U'` *c-char-sequence* `'`

*\<c-char-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; *c-char* <br> &ensp;&ensp;&ensp;&ensp; *c-char-sequence* *c-char*

*\<c-char\>* <br> &ensp;&ensp;&ensp;&ensp; any character except `'`, `\`, or `\n` <br> &ensp;&ensp;&ensp;&ensp; *escape-sequence*

*\<escape-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; *simple-escape-sequence* <br> &ensp;&ensp;&ensp;&ensp; *octal-escape-sequence* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-escape-sequence* <br> &ensp;&ensp;&ensp;&ensp; *universal-escape-sequence*

*\<simple-escape-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; `\'` <br> &ensp;&ensp;&ensp;&ensp; `\"` <br> &ensp;&ensp;&ensp;&ensp; `\?` <br> &ensp;&ensp;&ensp;&ensp; `\\` <br> &ensp;&ensp;&ensp;&ensp; `\a` <br> &ensp;&ensp;&ensp;&ensp; `\b` <br> &ensp;&ensp;&ensp;&ensp; `\f` <br> &ensp;&ensp;&ensp;&ensp; `\n` <br> &ensp;&ensp;&ensp;&ensp; `\r`<br> &ensp;&ensp;&ensp;&ensp; `\t` <br> &ensp;&ensp;&ensp;&ensp; `\v`

*\<octal-escape-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; `\` *octal-digit* <br> &ensp;&ensp;&ensp;&ensp; `\` *octal-digit* *octal-digit* <br> &ensp;&ensp;&ensp;&ensp; `\` *octal-digit* *octal-digit* *octal-digit*

*\<hexadecimal-escape-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; `\x` *hexadecimal-digit* <br> &ensp;&ensp;&ensp;&ensp; *hexadecimal-escape-sequence* *hexadecimal-digit*

*\<punctuator\>* <br> &ensp;&ensp;&ensp;&ensp; `[` <br> &ensp;&ensp;&ensp;&ensp; `]` <br> &ensp;&ensp;&ensp;&ensp; `(` <br> &ensp;&ensp;&ensp;&ensp; `)` <br> &ensp;&ensp;&ensp;&ensp; `{` <br> &ensp;&ensp;&ensp;&ensp; `}` <br> &ensp;&ensp;&ensp;&ensp; `.` <br> &ensp;&ensp;&ensp;&ensp; `->` <br> &ensp;&ensp;&ensp;&ensp; `++` <br> &ensp;&ensp;&ensp;&ensp; `--` <br> &ensp;&ensp;&ensp;&ensp; `&` <br> &ensp;&ensp;&ensp;&ensp; `*` <br> &ensp;&ensp;&ensp;&ensp; `+` <br> &ensp;&ensp;&ensp;&ensp; `-` <br> &ensp;&ensp;&ensp;&ensp; `~` <br> &ensp;&ensp;&ensp;&ensp; `!` <br> &ensp;&ensp;&ensp;&ensp;
`/` <br> &ensp;&ensp;&ensp;&ensp; `%` <br> &ensp;&ensp;&ensp;&ensp; `<<` <br> &ensp;&ensp;&ensp;&ensp; `>>` <br> &ensp;&ensp;&ensp;&ensp; `<` <br> &ensp;&ensp;&ensp;&ensp; `>` <br> &ensp;&ensp;&ensp;&ensp; `<=` <br> &ensp;&ensp;&ensp;&ensp; `>=` <br> &ensp;&ensp;&ensp;&ensp; `==` <br> &ensp;&ensp;&ensp;&ensp; `!=` <br> &ensp;&ensp;&ensp;&ensp; `^` <br> &ensp;&ensp;&ensp;&ensp; `<br> &ensp;&ensp;&ensp;&ensp;` <br> &ensp;&ensp;&ensp;&ensp; `&&` <br> &ensp;&ensp;&ensp;&ensp; `<br> &ensp;&ensp;&ensp;&ensp;<br> &ensp;&ensp;&ensp;&ensp;` <br> &ensp;&ensp;&ensp;&ensp;
`?` <br> &ensp;&ensp;&ensp;&ensp; `:` <br> &ensp;&ensp;&ensp;&ensp; `;` <br> &ensp;&ensp;&ensp;&ensp; `...` <br> &ensp;&ensp;&ensp;&ensp;
`=` <br> &ensp;&ensp;&ensp;&ensp; `*=` <br> &ensp;&ensp;&ensp;&ensp; `/=` <br> &ensp;&ensp;&ensp;&ensp; `%=` <br> &ensp;&ensp;&ensp;&ensp; `+=` <br> &ensp;&ensp;&ensp;&ensp; `-=` <br> &ensp;&ensp;&ensp;&ensp; `<<=` <br> &ensp;&ensp;&ensp;&ensp; `>>=` <br> &ensp;&ensp;&ensp;&ensp; `&=` <br> &ensp;&ensp;&ensp;&ensp; `^=` <br> &ensp;&ensp;&ensp;&ensp; `<br> &ensp;&ensp;&ensp;&ensp;=` <br> &ensp;&ensp;&ensp;&ensp;
`,` <br> &ensp;&ensp;&ensp;&ensp; `#` <br> &ensp;&ensp;&ensp;&ensp; `##` <br> &ensp;&ensp;&ensp;&ensp;
`<:` <br> &ensp;&ensp;&ensp;&ensp; `:>` <br> &ensp;&ensp;&ensp;&ensp; `<%` <br> &ensp;&ensp;&ensp;&ensp; `%>` <br> &ensp;&ensp;&ensp;&ensp; `%:` <br> &ensp;&ensp;&ensp;&ensp; `%:%:`

*\<header-name\>* <br> &ensp;&ensp;&ensp;&ensp; `<` *h-char-sequence* `>` <br> &ensp;&ensp;&ensp;&ensp; `"` *q-char-sequence* `"`

*\<h-char-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; *h-char* <br> &ensp;&ensp;&ensp;&ensp; *h-char-sequence* *h-char*

*\<h-char\>* <br> &ensp;&ensp;&ensp;&ensp; any character except `\n` and `>`

*\<q-char-sequence\>* <br> &ensp;&ensp;&ensp;&ensp; *q-char* <br> &ensp;&ensp;&ensp;&ensp; *q-char-sequence* *q-char* 

*\<q-char\>* <br> &ensp;&ensp;&ensp;&ensp; any character except `\n` and `"`

*\<pp-number\>* <br> &ensp;&ensp;&ensp;&ensp; *digit* <br> &ensp;&ensp;&ensp;&ensp; `.` *digit* <br> &ensp;&ensp;&ensp;&ensp; *pp-number* *digit* <br> &ensp;&ensp;&ensp;&ensp; *pp-number* *identifier-nondigit* <br> &ensp;&ensp;&ensp;&ensp; *pp-number* `e` *sign* <br> &ensp;&ensp;&ensp;&ensp; *pp-number* `E` *sign* <br> &ensp;&ensp;&ensp;&ensp; *pp-number* `p` *sign* <br> &ensp;&ensp;&ensp;&ensp; *pp-number* `P` *sign* <br> &ensp;&ensp;&ensp;&ensp; *pp-number* `.`

*\<primary-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *identifier* <br> &ensp;&ensp;&ensp;&ensp; *constant* <br> &ensp;&ensp;&ensp;&ensp; *string-literal* <br> &ensp;&ensp;&ensp;&ensp; `(` *expression* `)` <br> &ensp;&ensp;&ensp;&ensp; *generic-selection*

*\<generic-selection\>* <br> &ensp;&ensp;&ensp;&ensp; `_Generic` `(` *assignment-expression* `,` *generic-assoc-list* `)`

*\<generic-assoc-list\>* <br> &ensp;&ensp;&ensp;&ensp; *generic-association* <br> &ensp;&ensp;&ensp;&ensp; *generic-assoc-list* `,` *generic-association*

*\<generic-association\>* <br> &ensp;&ensp;&ensp;&ensp; *type-name* `:` *assignment-expression* <br> &ensp;&ensp;&ensp;&ensp; `default` `:` *assignment-expression*

*\<postfix-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *primary-expression* <br> &ensp;&ensp;&ensp;&ensp; *postfix-expression* `[` *expression* `]` <br> &ensp;&ensp;&ensp;&ensp; *postfix-expression* `(` *argument-expression-list<sub>opt</sub>* `)` <br> &ensp;&ensp;&ensp;&ensp; *postfix-expression* `.` *identifier* <br> &ensp;&ensp;&ensp;&ensp; *postfix-expression* `->` *identifier* <br> &ensp;&ensp;&ensp;&ensp; *postfix-expression* `++` <br> &ensp;&ensp;&ensp;&ensp; *postfix-expression* `-` <br> &ensp;&ensp;&ensp;&ensp; `(` *type-name* `)` `{` *initializer-list* `}` <br> &ensp;&ensp;&ensp;&ensp; `(` *type-name* `)` `{` *initializer-list* `,` `}`

*\<argument-expression-list\>* <br> &ensp;&ensp;&ensp;&ensp; *assignment-expression* <br> &ensp;&ensp;&ensp;&ensp; *argument-expression-list* `,` *assignment-expression*

*\<unary-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *postfix-expression* <br> &ensp;&ensp;&ensp;&ensp; `++` *unary-expression* <br> &ensp;&ensp;&ensp;&ensp; `-` *unary-expression* <br> &ensp;&ensp;&ensp;&ensp; *unary-operator* *cast-expression* <br> &ensp;&ensp;&ensp;&ensp; `sizeof` *unary-expression* <br> &ensp;&ensp;&ensp;&ensp; `sizeof` `(` *type-name* `)` <br> &ensp;&ensp;&ensp;&ensp; `_Alignof` `(` *type-name* `)`

*\<unary-operator\>* :== `&` <br> &ensp;&ensp;&ensp;&ensp; `*` <br> &ensp;&ensp;&ensp;&ensp; `+` <br> &ensp;&ensp;&ensp;&ensp; `-` <br> &ensp;&ensp;&ensp;&ensp; `~` <br> &ensp;&ensp;&ensp;&ensp; `!`

*\<cast-expression\>* :== *unary-expression* <br> &ensp;&ensp;&ensp;&ensp; `(` *type-name* `)` *cast-expression*

*\<multiplicative-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *cast-expression* <br> &ensp;&ensp;&ensp;&ensp; *multiplicative-expression* `*` *cast-expression* <br> &ensp;&ensp;&ensp;&ensp; *multiplicative-expression* `/` *cast-expression* <br> &ensp;&ensp;&ensp;&ensp; *multiplicative-expression* `%` *cast-expression*

*\<additive-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *multiplicative-expression* <br> &ensp;&ensp;&ensp;&ensp; *additive-expression* `+` *multiplicative-expression* <br> &ensp;&ensp;&ensp;&ensp; *additive-expression* `-` *multiplicative-expression*

*\<shift-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *additive-expression* <br> &ensp;&ensp;&ensp;&ensp; *shift-expression* `<<` *additive-expression* <br> &ensp;&ensp;&ensp;&ensp; *shift-expression* `>>` *additive-expression*

*\<relational-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *shift-expression* <br> &ensp;&ensp;&ensp;&ensp; *relational-expression* `<` *shift-expression* <br> &ensp;&ensp;&ensp;&ensp; *relational-expression* `>` *shift-expression* <br> &ensp;&ensp;&ensp;&ensp; *relational-expression* `<=` *shift-expression* <br> &ensp;&ensp;&ensp;&ensp; *relational-expression* `>=` *shift-expression*

*\<equality-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *relational-expression* <br> &ensp;&ensp;&ensp;&ensp; *equality-expression* `==` *relational-expression* <br> &ensp;&ensp;&ensp;&ensp; *equality-expression* `!=` *relational-expression*

*\<AND-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *equality-expression* <br> &ensp;&ensp;&ensp;&ensp; *AND-expression* `&` *equality-expression*

*\<exclusive-OR-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *AND-expression* <br> &ensp;&ensp;&ensp;&ensp; *exclusive-OR-expression* `^` *AND-expression*

*\<inclusive-OR-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *exclusive-OR-expression* <br> &ensp;&ensp;&ensp;&ensp; *inclusive-OR-expression* `<br> &ensp;&ensp;&ensp;&ensp;` *exclusive-OR-expression*

*\<logical-AND-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *inclusive-OR-expression* <br> &ensp;&ensp;&ensp;&ensp; *logical-AND-expression* `&&` *inclusive-OR-expression*

*\<logical-OR-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *logical-AND-expression* <br> &ensp;&ensp;&ensp;&ensp; *logical-OR-expression* `<br> &ensp;&ensp;&ensp;&ensp;<br> &ensp;&ensp;&ensp;&ensp;` *logical-AND-expression*

*\<conditional-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *logical-OR-expression* <br> &ensp;&ensp;&ensp;&ensp; *logical-OR-expression* `?` *expression* `:` *conditional-expression*

*\<assignment-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *conditional-expression* <br> &ensp;&ensp;&ensp;&ensp; *unary-expression* *assignment-operator* *assignment-expression*

*\<assignment-operator\>* <br> &ensp;&ensp;&ensp;&ensp; `=` <br> &ensp;&ensp;&ensp;&ensp; `*=` <br> &ensp;&ensp;&ensp;&ensp; `/=` <br> &ensp;&ensp;&ensp;&ensp; `%=` <br> &ensp;&ensp;&ensp;&ensp; `+=` <br> &ensp;&ensp;&ensp;&ensp; `-=` <br> &ensp;&ensp;&ensp;&ensp; `<<=` <br> &ensp;&ensp;&ensp;&ensp; `>>=` <br> &ensp;&ensp;&ensp;&ensp; `&=` <br> &ensp;&ensp;&ensp;&ensp; `^=` <br> &ensp;&ensp;&ensp;&ensp; `<br> &ensp;&ensp;&ensp;&ensp;=`

*\<expression\>* <br> &ensp;&ensp;&ensp;&ensp; *assignment-expression* <br> &ensp;&ensp;&ensp;&ensp; *expression* `,` *assignment-expression*

*\<constant-expression\>* <br> &ensp;&ensp;&ensp;&ensp; *conditional-expression*

*\<declaration\>* <br> &ensp;&ensp;&ensp;&ensp; *declaration-specifiers* *init-declarator-list<sub>opt</sub>* `;` <br> &ensp;&ensp;&ensp;&ensp; *static_assert-declaration*

*\<declaration-specifiers\>* <br> &ensp;&ensp;&ensp;&ensp; 
*storage-class-specifier* *declaration-specifiers<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *type-specifier* *declaration-specifiers<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *type-qualifier* *declaration-specifiers<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *function-specifier* *declaration-specifiers<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *alignment-specifier* *declaration-specifiers<sub>opt</sub>*

*\<init-declarator-list\>* <br> &ensp;&ensp;&ensp;&ensp; *init-declarator* <br> &ensp;&ensp;&ensp;&ensp; *init-declarator-list* `,` *init-declarator*

*\<init-declarator\>* <br> &ensp;&ensp;&ensp;&ensp; *declarator* <br> &ensp;&ensp;&ensp;&ensp; *declarator* `=` *initializer*

*\<storage-class-specifier\>* <br> &ensp;&ensp;&ensp;&ensp; `typedef` <br> &ensp;&ensp;&ensp;&ensp; `extern` <br> &ensp;&ensp;&ensp;&ensp; `static` <br> &ensp;&ensp;&ensp;&ensp; `_Thread_local` <br> &ensp;&ensp;&ensp;&ensp; `auto` <br> &ensp;&ensp;&ensp;&ensp; `register`

*\<type-specifier\>* <br> &ensp;&ensp;&ensp;&ensp; `void` <br> &ensp;&ensp;&ensp;&ensp; `char` <br> &ensp;&ensp;&ensp;&ensp; `short` <br> &ensp;&ensp;&ensp;&ensp; `int` <br> &ensp;&ensp;&ensp;&ensp; `long` <br> &ensp;&ensp;&ensp;&ensp; `float` <br> &ensp;&ensp;&ensp;&ensp; `double` <br> &ensp;&ensp;&ensp;&ensp; `signed` <br> &ensp;&ensp;&ensp;&ensp; `unsigned` <br> &ensp;&ensp;&ensp;&ensp; `_Bool` <br> &ensp;&ensp;&ensp;&ensp; `_Complex` <br> &ensp;&ensp;&ensp;&ensp; *atomic-type-specifier* <br> &ensp;&ensp;&ensp;&ensp; *struct-or-union-specifier* <br> &ensp;&ensp;&ensp;&ensp; *enum-specifier* <br> &ensp;&ensp;&ensp;&ensp; *typedef-name*

*\<struct-or-union-specifier\>* <br> &ensp;&ensp;&ensp;&ensp; *struct-or-union* *identifier<sub>opt</sub>* `{` *struct-declaration-list* `}` <br> &ensp;&ensp;&ensp;&ensp; *struct-or-union* *identifier* 

*\<struct-or-union\>* <br> &ensp;&ensp;&ensp;&ensp; `struct` <br> &ensp;&ensp;&ensp;&ensp; `union`

*\<struct-declaration-list\>* <br> &ensp;&ensp;&ensp;&ensp; *struct-declaration* <br> &ensp;&ensp;&ensp;&ensp; *struct-declaration-list* *struct-declaration*

*\<struct-declaration\>* <br> &ensp;&ensp;&ensp;&ensp; *specifier-qualifier-list* *struct-declarator-list<sub>opt</sub>* `;` <br> &ensp;&ensp;&ensp;&ensp; *static_assert-declaration*

*\<specifier-qualifier-list\>* <br> &ensp;&ensp;&ensp;&ensp; *type-specifier* *specifier-qualifier-list<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *type-qualifier* *specifier-qualifier-list<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; *alignment-specifier* *specifier-qualifier-list<sub>opt</sub>* 

*\<struct-declarator-list\>* <br> &ensp;&ensp;&ensp;&ensp; *struct-declarator* <br> &ensp;&ensp;&ensp;&ensp; *struct-declarator-list* `,` *struct-declarator*

*\<struct-declarator\>* <br> &ensp;&ensp;&ensp;&ensp; *declarator* <br> &ensp;&ensp;&ensp;&ensp; *declarator<sub>opt</sub>* `:` *constant-expression*

*\<enum-specifier\>* <br> &ensp;&ensp;&ensp;&ensp; `enum` *identifier<sub>opt</sub>* `{` *enumerator-list* `}` <br> &ensp;&ensp;&ensp;&ensp; `enum` *identifier<sub>opt</sub>* `{` *enumerator-list* `,` `}` <br> &ensp;&ensp;&ensp;&ensp; `enum` *identifier*

*\<enumerator-list\>* <br> &ensp;&ensp;&ensp;&ensp; *enumerator* <br> &ensp;&ensp;&ensp;&ensp; *enumerator-list* `,` *enumerator*

*\<enumerator\>* <br> &ensp;&ensp;&ensp;&ensp; *enumeration-constant* <br> &ensp;&ensp;&ensp;&ensp; *enumeration-constant* `=` *constant-expression*

*\<atomic-type-specifier\>* <br> &ensp;&ensp;&ensp;&ensp; `_Atomic` `(` *type-name* `)`

*\<type-qualifier\>* <br> &ensp;&ensp;&ensp;&ensp; `const` <br> &ensp;&ensp;&ensp;&ensp; `restrict` <br> &ensp;&ensp;&ensp;&ensp; `volatile` <br> &ensp;&ensp;&ensp;&ensp; `_Atomic`

*\<function-specifier\>* <br> &ensp;&ensp;&ensp;&ensp; `inline` <br> &ensp;&ensp;&ensp;&ensp; `_Noreturn`

*\<alignment-specifier\>* <br> &ensp;&ensp;&ensp;&ensp; `_Alignas` `(` *type-name* `)` <br> &ensp;&ensp;&ensp;&ensp; `_Alignas` `(` *constant-expression* `)`

*\<declarator\>* <br> &ensp;&ensp;&ensp;&ensp; *pointer<sub>opt</sub>* *direct-declarator*

*\<direct-declarator\>* <br> &ensp;&ensp;&ensp;&ensp; *identifier* <br> &ensp;&ensp;&ensp;&ensp; `(` *declarator* `)` <br> &ensp;&ensp;&ensp;&ensp; *direct-declarator* `[` *type-qualifier-list<sub>opt</sub>* *assignment-expression<sub>opt</sub>* `]` <br> &ensp;&ensp;&ensp;&ensp; *direct-declarator* `[` `static` *type-qualifier-list<sub>opt</sub>* *assignment-expression* `]` <br> &ensp;&ensp;&ensp;&ensp; *direct-declarator* `[` *type-qualifier-list* `static` *assignment-expression* `]` <br> &ensp;&ensp;&ensp;&ensp; *direct-declarator* `[` *type-qualifier-list<sub>opt</sub>* `*` `]` <br> &ensp;&ensp;&ensp;&ensp; *direct-declarator* `(` *parameter-type-list* `)` <br> &ensp;&ensp;&ensp;&ensp; *direct-declarator* `(` *identifier-list<sub>opt</sub>* `)`

*\<pointer\>* <br> &ensp;&ensp;&ensp;&ensp; `*` *type-qualifier-list<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; `*` *type-qualifier-list<sub>opt</sub>* *pointer*

*\<type-qualifier-list\>* <br> &ensp;&ensp;&ensp;&ensp; *type-qualifier* <br> &ensp;&ensp;&ensp;&ensp; *type-qualifier-list* *type-qualifier*

*\<parameter-type-list\>* <br> &ensp;&ensp;&ensp;&ensp; *parameter-list* <br> &ensp;&ensp;&ensp;&ensp; *parameter-list* `,` `...`

*\<parameter-list\>* <br> &ensp;&ensp;&ensp;&ensp; *parameter-declaration* <br> &ensp;&ensp;&ensp;&ensp; *parameter-list* `,` *parameter-declaration*

*\<parameter-declaration\>* <br> &ensp;&ensp;&ensp;&ensp; *declaration-specifiers* *declarator* <br> &ensp;&ensp;&ensp;&ensp; *declaration-specifiers* *abstract-declarator<sub>opt</sub>*

*\<identifier-list\>* <br> &ensp;&ensp;&ensp;&ensp; *identifier* <br> &ensp;&ensp;&ensp;&ensp; *identifier-list* `,` *identifier*

*\<type-name\>* <br> &ensp;&ensp;&ensp;&ensp; *specifier-qualifier-list* *abstract-declarator<sub>opt</sub>*

*\<abstract-declarator\>* <br> &ensp;&ensp;&ensp;&ensp; *pointer* <br> &ensp;&ensp;&ensp;&ensp; *pointer<sub>opt</sub>* *direct-abstract-declarator*

*\<direct-abstract-declarator\>* <br> &ensp;&ensp;&ensp;&ensp; `(` *abstract-declarator* `)` <br> &ensp;&ensp;&ensp;&ensp; *direct-abstract-declarator<sub>opt</sub>* `[` *type-qualifier-list<sub>opt</sub>* *assignment-expression<sub>opt</sub>* `]` <br> &ensp;&ensp;&ensp;&ensp; *direct-abstract-declarator<sub>opt</sub>* `[` `static` *type-qualifier-list<sub>opt</sub>* *assignment-expression* `]` <br> &ensp;&ensp;&ensp;&ensp; *direct-abstract-declarator<sub>opt</sub>* `[` *type-qualifier-list* `static` *assignment-expression* `]` <br> &ensp;&ensp;&ensp;&ensp; *direct-abstract-declarator<sub>opt</sub>* `[` `*` `]` <br> &ensp;&ensp;&ensp;&ensp; *direct-abstract-declarator<sub>opt</sub>* `(` *parameter-type-list<sub>opt</sub>* `)`

*\<typedef-name\>* <br> &ensp;&ensp;&ensp;&ensp; *identifier*

*\<initializer\>* <br> &ensp;&ensp;&ensp;&ensp; *assignment-expression* <br> &ensp;&ensp;&ensp;&ensp; `{` *initializer-list* `}` <br> &ensp;&ensp;&ensp;&ensp; `{` *initializer-list* `,` `}`

*\<initializer-list\>* <br> &ensp;&ensp;&ensp;&ensp; *designation<sub>opt</sub>* *initializer* <br> &ensp;&ensp;&ensp;&ensp; *initializer-list* `,` *designation<sub>opt</sub>* *initializer*

*\<designation\>* <br> &ensp;&ensp;&ensp;&ensp; *designator-list* `=`

*\<designator-list\>* <br> &ensp;&ensp;&ensp;&ensp; *designator* <br> &ensp;&ensp;&ensp;&ensp; *designator-list* *designator*

*\<designator\>* <br> &ensp;&ensp;&ensp;&ensp; `[` *constant-expression* `]` <br> &ensp;&ensp;&ensp;&ensp; `.` *identifier*

*\<static_assert-declaration\>* <br> &ensp;&ensp;&ensp;&ensp; `_Static_assert` `(` *constant-expression* `,` *string-literal* `)` `;` <br> &ensp;&ensp;&ensp;&ensp; `_Static_assert` `(` *constant-expression* `)` `;`

*\<statement\>* <br> &ensp;&ensp;&ensp;&ensp; *labeled-statement* <br> &ensp;&ensp;&ensp;&ensp; *compound-statement* <br> &ensp;&ensp;&ensp;&ensp; *expression-statement* <br> &ensp;&ensp;&ensp;&ensp;*selection-statement* <br> &ensp;&ensp;&ensp;&ensp;*iteration-statement* <br> &ensp;&ensp;&ensp;&ensp; *jump-statement*

*\<labeled-statement\>* <br> &ensp;&ensp;&ensp;&ensp; *identifier* `:` *statement* <br> &ensp;&ensp;&ensp;&ensp; `case` *constant-expression* `:` *statement* <br> &ensp;&ensp;&ensp;&ensp; `default` `:` *statement*

*\<compound-statement\>* <br> &ensp;&ensp;&ensp;&ensp; `{` *block-item-list<sub>opt</sub>* `}`

*\<block-item-list\>* <br> &ensp;&ensp;&ensp;&ensp; *block-item* <br> &ensp;&ensp;&ensp;&ensp; *block-item-list* *block-item*

*\<block-item\>* <br> &ensp;&ensp;&ensp;&ensp; *declaration* <br> &ensp;&ensp;&ensp;&ensp; *statement*

*\<expression-statement\>* <br> &ensp;&ensp;&ensp;&ensp; *expression<sub>opt</sub>* `;`

*\<selection-statement\>* <br> &ensp;&ensp;&ensp;&ensp; `if` `(` *expression* `)` *statement* <br> &ensp;&ensp;&ensp;&ensp; `if` `(` *expression* `)` *statement* `else` *statement* <br> &ensp;&ensp;&ensp;&ensp; `switch` `(` *expression* `)` *statement*

*\<iteration-statement\>* <br> &ensp;&ensp;&ensp;&ensp; `while` `(` *expression* `)` *statement* <br> &ensp;&ensp;&ensp;&ensp; `do` *statement* `while` `(` *expression* `)` `;` <br> &ensp;&ensp;&ensp;&ensp; `for` `(` *expression<sub>opt</sub>* `;` *expression<sub>opt</sub>* `;` *expression<sub>opt</sub>* `)` *statement* <br> &ensp;&ensp;&ensp;&ensp; `for` `(` *declaration* *expression<sub>opt</sub>* `;` *expression<sub>opt</sub>* `)` *statement*

*\<jump-statement\>* <br> &ensp;&ensp;&ensp;&ensp; `goto` *identifier* `;` <br> &ensp;&ensp;&ensp;&ensp; `continue` `;` <br> &ensp;&ensp;&ensp;&ensp; `break` `;` <br> &ensp;&ensp;&ensp;&ensp; `return` *expression<sub>opt</sub>* `;`

*\<translation-unit\>* <br> &ensp;&ensp;&ensp;&ensp; *external-declaration* <br> &ensp;&ensp;&ensp;&ensp; *translation-unit* *external-declaration*

*\<external-declaration\>* <br> &ensp;&ensp;&ensp;&ensp; *function-definition* <br> &ensp;&ensp;&ensp;&ensp; *declaration*

*\<function-definition\>* <br> &ensp;&ensp;&ensp;&ensp; *declaration-specifiers* *declarator* *declaration-list<sub>opt</sub>* *compound-statement*

*\<declaration-list\>* <br> &ensp;&ensp;&ensp;&ensp; *declaration* <br> &ensp;&ensp;&ensp;&ensp; *declaration-list* *declaration*

*\<preprocessing-file\>* <br> &ensp;&ensp;&ensp;&ensp; *group<sub>opt</sub>*

*\<group\>* <br> &ensp;&ensp;&ensp;&ensp; *group-part* <br> &ensp;&ensp;&ensp;&ensp; *group* *group-part*

*\<group-part\>* <br> &ensp;&ensp;&ensp;&ensp; *if-section* <br> &ensp;&ensp;&ensp;&ensp; *control-line* <br> &ensp;&ensp;&ensp;&ensp; *text-line* <br> &ensp;&ensp;&ensp;&ensp; `#` *non-directive*

*\<if-section\>* <br> &ensp;&ensp;&ensp;&ensp; *if-group* *elif-groups<sub>opt</sub>* *else-group<sub>opt</sub>* *endif-line*

*\<if-group\>* <br> &ensp;&ensp;&ensp;&ensp; `#` `if` *constant-expression* *new-line* *group<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; `#` `ifdef` *identifier* *new-line* *group<sub>opt</sub>* <br> &ensp;&ensp;&ensp;&ensp; `#` `ifndef` *identifier* *new-line* *group<sub>opt</sub>*

*\<elif-groups\>* <br> &ensp;&ensp;&ensp;&ensp; *elif-group* <br> &ensp;&ensp;&ensp;&ensp; *elif-groups* *elif-group*

*\<elif-group\>* <br> &ensp;&ensp;&ensp;&ensp; `#` `elif` *constant-expression* *new-line* *group<sub>opt</sub>*

*\<else-group\>* <br> &ensp;&ensp;&ensp;&ensp; `#` `else` *new-line* *group<sub>opt</sub>* 

*\<endif-line\>* <br> &ensp;&ensp;&ensp;&ensp; `#` `endif` *new-line*

*\<control-line\>* <br> &ensp;&ensp;&ensp;&ensp; `#` `include` *pp-tokens* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` `define` *identifier* *replacement-list* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` `define` *identifier* *lparen* *identifier-list<sub>opt</sub>* `)` *replacement-list* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` `define` *identifier* *lparen* `...` `)` *replacement-list* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` `define` *identifier* *lparen* *identifier-list* `,` `...` `)` *replacement-list* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` `undef` *identifier* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` `line` *pp-tokens* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` `error` *pp-tokens<sub>opt</sub>* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` `pragma` *pp-tokens<sub>opt</sub>* *new-line* <br> &ensp;&ensp;&ensp;&ensp; `#` *new-line*

*\<text-line\>* <br> &ensp;&ensp;&ensp;&ensp; *pp-tokens<sub>opt</sub>* *new-line*

*\<non-directive\>* <br> &ensp;&ensp;&ensp;&ensp; *pp-tokens* *new-line* 

*\<lparen\>* <br> &ensp;&ensp;&ensp;&ensp; a `(` character not immediately preceded by white space

*\<replacement-list\>* <br> &ensp;&ensp;&ensp;&ensp; *pp-tokens<sub>opt</sub>* 

*\<pp-tokens\>* <br> &ensp;&ensp;&ensp;&ensp; *preprocessing-token* <br> &ensp;&ensp;&ensp;&ensp; *pp-tokens* *preprocessing-token*

*\<new-line\>* <br> &ensp;&ensp;&ensp;&ensp; the new-line character `\n`