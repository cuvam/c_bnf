<!-- Obtained from https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2310.pdf chapter 6.4-6.10 -->
<!-- '?' postfix means this token is optional -->

token ::= *keyword* | *identifier* | *constant* | *string-literal* | *punctuator*

preprocessing-token ::= *header-name* | *identifier* | *pp-number* | *character-constant* | *string-literal* | *punctuator* | each non-whitespace character that isn't any of these

keyword ::= `auto` | `break` | `case` | `char` | `const` | `continue` | `default` | `do` | `double` | `else` | `enum` | `extern` | `float` | `for` | `goto` | `if` | `inline` | `int` | `long` | `register` | `restrict` | `return` | `short` | `signed` | `sizeof` | `static` | `struct` | `switch` | `typedef` | `union` | `unsigned` | `void` | `volatile` | `while` | `_Alignas` | `_Alignof` | `_Atomic` | `_Bool` | `_Complex` | `_Generic` | `_Imaginary` | `_Noreturn` | `_Static_assert` | `_Thread_local`  

identifier ::= *identifier-nondigit* | *identifier identifier-nondigit*| *identifier digit*

identifier-nondigit ::= *nondigit* | *universal-character-name*

nondigit ::= `_`| `a` | `b` | `c` | `d` | `e` | `f` | `g` | `h` | `i` | `j` | `k` | `l` | `m` | `n` | `o` | `p` | `q` | `r` | `s` | `t` | `u` | `v` | `w` | `x` | `y` | `z` | `A` | `B` | `C` | `D` | `E` | `F` | `G` | `H` | `I` | `J` | `K` | `L` | `M` | `N` | `O` | `P` | `Q` | `R` | `S` | `T` | `U` | `V` | `W` | `X` | `Y` | `Z`

digit ::= `0` | `1` | `2` | `3` | `4` | `5` | `6` | `7` | `8` | `9` 

universal-character-name ::= `\u` *hex-quad* | `\U` *hex-quad* *hex-quad*

hex-quad ::= *hexidecimal-digit* *hexidecimal-digit* *hexidecimal-digit* *hexidecimal-digit* 

constant ::= *integer-constant* | *floating-constant* | *enumeration-constant* | *character-constant*

integer-constant ::= *decimal-constant* *integer-suffix?* | *octal-constant* *integer-suffix?* | *hexadecimal-constant* *integer-suffix?* 

decimal-constant ::= *nonzero-digit* | *decimal-constant* *digit*

octal-constant ::= `0` | *octal-constant* *octal-digit*

hexadecimal-constant ::= *hexadecimal-prefix* *hexadecimal-digit* | *hexadecimal-constant* *hexadecimal-digit*
 
hexadecimal-prefix ::= `0x` | `0X`

nonzero-digit ::= `1` | `2` | `3` | `4` | `5` | `6` | `7` | `8` | `9`

octal-digit ::= `0` | `1` | `2` | `3` | `4` | `5` | `6` | `7`

hexadecimal-digit :== `0` | `1` | `2` | `3` | `4` | `5` | `6` | `7` | `8` | `9` | `a` | `b` | `c` | `d` | `e` | `f` | `A` | `B` | `C` | `D` | `E` | `F`

integer-suffix ::= *unsigned-suffix* *long-suffix?* | *unsigned-suffix* *long-long-suffix* | *long-suffix* *unsigned-suffix?* | *long-long-suffix* *unsigned-suffix?*

unsigned-suffix ::= `u` | `U`

long-suffix ::= `l` | `L`

long-long-suffix ::= `ll` | `LL`

floating-constant ::= *decimal-floating-constant* | *hexidecimal-floating-constant* 

decimal-floating-constant ::= *fractional-constant* *exponent-part?* *floating-suffix?* | *digit-sequence* *exponent-part* *floating-suffix?*

hexadecimal-floating-constant ::= *hexadecimal-prefix* *hexadecimal-fractional-constant* | *binary-exponent-part* *floating-suffix?* | *hexadecimal-prefix* *hexadecimal-digit-sequence* | *binary-exponent-part* *floating-suffix?*

fractional-constant ::= *digit-sequence?* `.` *digit-sequence* | *digit-sequence* `.`

exponent-part ::= `e` *sign?* *digit-sequence* | `E` *sign?* *digit-sequence*

sign ::= `+` | `-`

digit-sequence ::= *digit* | *digit-sequence* *digit*

hexadecimal-fractional-constant ::= *hexadecimal-digit-sequence?* `.` *hexadecimal-digit-sequence* | *hexadecimal-digit-sequence* `.`

binary-exponent-part ::= `p` *sign?* *digit-sequence* | `P` *sign?* *digit-sequence*

hexadecimal-digit-sequence ::= *hexadecimal-digit* | *hexadecimal-digit-sequence* *hexadecimal-digit*

floating-suffix ::= `f` | `l` | `F` | `L`

enumeration-constant :== *identifier*

character-constant :== `'` *c-char-sequence* `'` | `L'` *c-char-sequence* `'` | `u'` *c-char-sequence* `'` | `U'` *c-char-sequence* `'`

c-char-sequence ::= *c-char* | *c-char-sequence* *c-char*

c-char ::= any character except `'`, `\`, or `\n` | *escape-sequence*

escape-sequence ::= *simple-escape-sequence* | *octal-escape-sequence* | *hexadecimal-escape-sequence* | *universal-escape-sequence*

simple-escape-sequence ::= `\'` | `\"` | `\?` | `\\` | `\a` | `\b` | `\f` | `\n` | `\r`| `\t` | `\v`

octal-escape-sequence ::= `\` *octal-digit* | `\` *octal-digit* *octal-digit* | `\` *octal-digit* *octal-digit* *octal-digit*

hexadecimal-escape-sequence ::= `\x` *hexadecimal-digit* | *hexadecimal-escape-sequence* *hexadecimal-digit*

punctuator ::= `[` | `]` | `(` | `)` | `{` | `}` | `.` | `->` | `++` | `--` | `&` | `*` | `+` | `-` | `~` | `!` |
`/` | `%` | `<<` | `>>` | `<` | `>` | `<=` | `>=` | `==` | `!=` | `^` | `|` | `&&` | `||` |
`?` | `:` | `;` | `...` |
`=` | `*=` | `/=` | `%=` | `+=` | `-=` | `<<=` | `>>=` | `&=` | `^=` | `|=` |
`,` | `#` | `##` |
`<:` | `:>` | `<%` | `%>` | `%:` | `%:%:`

header-name ::= `<` *h-char-sequence* `>` | `"` *q-char-sequence* `"`

h-char-sequence ::= *h-char* | *h-char-sequence* *h-char*

h-char ::= any character except `\n` and `>`

q-char-sequence ::= *q-char* | *q-char-sequence* *q-char* 

q-char ::= any character except `\n` and `"`

pp-number ::= *digit* | `.` *digit* | *pp-number* *digit* | *pp-number* *identifier-nondigit* | *pp-number* `e` *sign* | *pp-number* `E` *sign* | *pp-number* `p` *sign* | *pp-number* `P` *sign* | *pp-number* `.`

primary-expression ::= *identifier* | *constant* | *string-literal* | `(` *expression* `)` | *generic-selection*

generic-selection ::= `_Generic` `(` *assignment-expression* `,` *generic-assoc-list* `)`

generic-assoc-list ::= *generic-association* | *generic-assoc-list* `,` *generic-association*

generic-association ::= *type-name* `:` *assignment-expression* | `default` `:` *assignment-expression*

postfix-expression ::= *primary-expression* | *postfix-expression* `[` *expression* `]` | *postfix-expression* `(` *argument-expression-list?* `)` | *postfix-expression* `.` *identifier* | *postfix-expression* `->` *identifier* | *postfix-expression* `++` | *postfix-expression* `-` | `(` *type-name* `)` `{` *initializer-list* `}` | `(` *type-name* `)` `{` *initializer-list* `,` `}`

argument-expression-list ::= *assignment-expression* | *argument-expression-list* `,` *assignment-expression*

unary-expression ::= *postfix-expression* | `++` *unary-expression* | `-` *unary-expression* | *unary-operator* *cast-expression* | `sizeof` *unary-expression* | `sizeof` `(` *type-name* `)` | `_Alignof` `(` *type-name* `)`

unary-operator :== `&` | `*` | `+` | `-` | `~` | `!`

cast-expression :== *unary-expression* | `(` *type-name* `)` *cast-expression*

multiplicative-expression ::= *cast-expression* | *multiplicative-expression* `*` *cast-expression* | *multiplicative-expression* `/` *cast-expression* | *multiplicative-expression* `%` *cast-expression*

additive-expression ::= *multiplicative-expression* | *additive-expression* `+` *multiplicative-expression* | *additive-expression* `-` *multiplicative-expression*

shift-expression ::= *additive-expression* | *shift-expression* `<<` *additive-expression* | *shift-expression* `>>` *additive-expression*

relational-expression ::= *shift-expression* | *relational-expression* `<` *shift-expression* | *relational-expression* `>` *shift-expression* | *relational-expression* `<=` *shift-expression* | *relational-expression* `>=` *shift-expression*

equality-expression ::= *relational-expression* | *equality-expression* `==` *relational-expression* | *equality-expression* `!=` *relational-expression*

AND-expression ::= *equality-expression* | *AND-expression* `&` *equality-expression*

exclusive-OR-expression ::= *AND-expression* | *exclusive-OR-expression* `^` *AND-expression*

inclusive-OR-expression ::= *exclusive-OR-expression* | *inclusive-OR-expression* `|` *exclusive-OR-expression*

logical-AND-expression ::= *inclusive-OR-expression* | *logical-AND-expression* `&&` *inclusive-OR-expression*

logical-OR-expression ::= *logical-AND-expression* | *logical-OR-expression* `||` *logical-AND-expression*

conditional-expression ::= *logical-OR-expression* | *logical-OR-expression* `?` *expression* `:` *conditional-expression*

assignment-expression ::= *conditional-expression* | *unary-expression* *assignment-operator* *assignment-expression*

assignment-operator ::= `=` | `*=` | `/=` | `%=` | `+=` | `-=` | `<<=` | `>>=` | `&=` | `^=` | `|=`

expression ::= *assignment-expression* | *expression* `,` *assignment-expression*

constant-expression ::= *conditional-expression*

declaration ::= *declaration-specifiers* *init-declarator-list?* `;` | *static_assert-declaration*

declaration-specifiers ::= 
*storage-class-specifier* *declaration-specifiers?* | *type-specifier* *declaration-specifiers?* | *type-qualifier* *declaration-specifiers?* | *function-specifier* *declaration-specifiers?* | *alignment-specifier* *declaration-specifiers?*

init-declarator-list ::= *init-declarator* | *init-declarator-list* `,` *init-declarator*

init-declarator ::= *declarator* | *declarator* `=` *initializer*

storage-class-specifier ::= `typedef` | `extern` | `static` | `_Thread_local` | `auto` | `register`

type-specifier ::= `void` | `char` | `short` | `int` | `long` | `float` | `double` | `signed` | `unsigned` | `_Bool` | `_Complex` | *atomic-type-specifier* | *struct-or-union-specifier* | *enum-specifier* | *typedef-name*

struct-or-union-specifier ::= *struct-or-union* *identifier?* `{` *struct-declaration-list* `}` | *struct-or-union* *identifier* 

struct-or-union ::= `struct` | `union`

struct-declaration-list ::= *struct-declaration* | *struct-declaration-list* *struct-declaration*

struct-declaration ::= *specifier-qualifier-list* *struct-declarator-list?* `;` | *static_assert-declaration*

specifier-qualifier-list ::= *type-specifier* *specifier-qualifier-list?* | *type-qualifier* *specifier-qualifier-list?* | *alignment-specifier* *specifier-qualifier-list?* 

struct-declarator-list ::= *struct-declarator* | *struct-declarator-list* `,` *struct-declarator*

struct-declarator ::= *declarator* | *declarator?* `:` *constant-expression*

enum-specifier ::= `enum` *identifier?* `{` *enumerator-list* `}` | `enum` *identifier?* `{` *enumerator-list* `,` `}` | `enum` *identifier*

enumerator-list ::= *enumerator* | *enumerator-list* `,` *enumerator*

enumerator ::= *enumeration-constant* | *enumeration-constant* `=` *constant-expression*

atomic-type-specifier ::= `_Atomic` `(` *type-name* `)`

type-qualifier ::= `const` | `restrict` | `volatile` | `_Atomic`

function-specifier ::= `inline` | `_Noreturn`

alignment-specifier ::= `_Alignas` `(` *type-name* `)` | `_Alignas` `(` *constant-expression* `)`

declarator ::= *pointer?* *direct-declarator*

direct-declarator ::= *identifier* | `(` *declarator* `)` | *direct-declarator* `[` *type-qualifier-list?* *assignment-expression?* `]` | *direct-declarator* `[` `static` *type-qualifier-list?* *assignment-expression* `]` | *direct-declarator* `[` *type-qualifier-list* `static` *assignment-expression* `]` | *direct-declarator* `[` *type-qualifier-list?* `*` `]` | *direct-declarator* `(` *parameter-type-list* `)` | *direct-declarator* `(` *identifier-list?* `)`

pointer ::= `*` *type-qualifier-list?* | `*` *type-qualifier-list?* *pointer*

type-qualifier-list ::= *type-qualifier* | *type-qualifier-list* *type-qualifier*

parameter-type-list ::= *parameter-list* | *parameter-list* `,` `...`

parameter-list ::= *parameter-declaration* | *parameter-list* `,` *parameter-declaration*

parameter-declaration ::= *declaration-specifiers* *declarator* | *declaration-specifiers* *abstract-declarator?*

identifier-list ::= *identifier* | *identifier-list* `,` *identifier*

type-name ::= *specifier-qualifier-list* *abstract-declarator?*

abstract-declarator ::= *pointer* | *pointer?* *direct-abstract-declarator*

direct-abstract-declarator ::= `(` *abstract-declarator* `)` | *direct-abstract-declarator?* `[` *type-qualifier-list?* *assignment-expression?* `]` | *direct-abstract-declarator?* `[` `static` *type-qualifier-list?* *assignment-expression* `]` | *direct-abstract-declarator?* `[` *type-qualifier-list* `static` *assignment-expression* `]` | *direct-abstract-declarator?* `[` `*` `]` | *direct-abstract-declarator?* `(` *parameter-type-list?* `)`

typedef-name ::= *identifier*

initializer ::= *assignment-expression* | `{` *initializer-list* `}` | `{` *initializer-list* `,` `}`

initializer-list ::= *designation?* *initializer* | *initializer-list* `,` *designation?* *initializer*

designation ::= *designator-list* `=`

designator-list ::= *designator* | *designator-list* *designator*

designator ::= `[` *constant-expression* `]` | `.` *identifier*

static_assert-declaration ::= `_Static_assert` `(` *constant-expression* `,` *string-literal* `)` `;` | `_Static_assert` `(` *constant-expression* `)` `;`

statement ::= *labeled-statement* | *compound-statement* | *expression-statement* |*selection-statement* |*iteration-statement* | *jump-statement*

labeled-statement ::= *identifier* `:` *statement* | `case` *constant-expression* `:` *statement* | `default` `:` *statement*

compound-statement ::= `{` *block-item-list?* `}`

block-item-list ::= *block-item* | *block-item-list* *block-item*

block-item ::= *declaration* | *statement*

expression-statement ::= *expression?* `;`

selection-statement ::= `if` `(` *expression* `)` *statement* | `if` `(` *expression* `)` *statement* `else` *statement* | `switch` `(` *expression* `)` *statement*

iteration-statement ::= `while` `(` *expression* `)` *statement* | `do` *statement* `while` `(` *expression* `)` `;` | `for` `(` *expression?* `;` *expression?* `;` *expression?* `)` *statement* | `for` `(` *declaration* *expression?* `;` *expression?* `)` *statement*

jump-statement ::= `goto` *identifier* `;` | `continue` `;` | `break` `;` | `return` *expression?* `;`

translation-unit ::= *external-declaration* | *translation-unit* *external-declaration*

external-declaration ::= *function-definition* | *declaration*

function-definition ::= *declaration-specifiers* *declarator* *declaration-list?* *compound-statement*

declaration-list ::= *declaration* | *declaration-list* *declaration*

preprocessing-file ::= *group?*

group ::= *group-part* | *group* *group-part*

group-part ::= *if-section* | *control-line* | *text-line* | `#` *non-directive*

if-section ::= *if-group* *elif-groups?* *else-group?* *endif-line*

if-group ::= `#` `if` *constant-expression* *new-line* *group?* | `#` `ifdef` *identifier* *new-line* *group?* | `#` `ifndef` *identifier* *new-line* *group?*

elif-groups ::= *elif-group* | *elif-groups* *elif-group*

elif-group ::= `#` `elif` *constant-expression* *new-line* *group?*

else-group ::= `#` `else` *new-line* *group?* 

endif-line ::= `#` `endif` *new-line*

control-line ::= `#` `include` *pp-tokens* *new-line* | `#` `define` *identifier* *replacement-list* *new-line* | `#` `define` *identifier* *lparen* *identifier-list?* `)` *replacement-list* *new-line* | `#` `define` *identifier* *lparen* `...` `)` *replacement-list* *new-line* | `#` `define` *identifier* *lparen* *identifier-list* `,` `...` `)` *replacement-list* *new-line* | `#` `undef` *identifier* *new-line* | `#` `line` *pp-tokens* *new-line* | `#` `error` *pp-tokens?* *new-line* | `#` `pragma` *pp-tokens?* *new-line* | `#` *new-line*

text-line ::= *pp-tokens?* *new-line*

non-directive ::= *pp-tokens* *new-line* 

lparen ::= a `(` character not immediately preceded by white space

replacement-list ::= *pp-tokens?* 

pp-tokens ::= *preprocessing-token* | *pp-tokens* *preprocessing-token*

new-line ::= the new-line character `\n`