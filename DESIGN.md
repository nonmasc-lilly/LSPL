# LSPL

LSPL is a stack based programming language designed to be simple to implement while
still being useful.

```
push <imm>
pop
add
sub

mul
div
and
or
not
shl <imm>
shr <imm>

let <iden> ('from' <imm>)?

define <iden> '(' <imm> ')' 'start'
enddef
return
@extern <iden>

while <iden>?
endwhile

struct <iden> '(' <iden> (',' <iden>)?* ')'

buffer <iden> '(' <imm> ')'

enum <iden> '(' <iden> (',' <iden>)?* ')'

```
