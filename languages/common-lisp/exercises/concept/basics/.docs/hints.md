## Symbols and Quoting

If you are having trouble returning a symbol from a function, you might need to
add a quote (`'`)! Recall that keywords are slightly different from regular
symbols, and must be preceded by a colon (`:`).

## Truthy and Falsy Values

Recall that there is no single "true" and "false" in Common Lisp; rather, the
values: `nil` and `'()` are false and _all_ other values are true.

## S-Expressions

Common Lisp contains predicate functions for determining many things. In
particular there are two that are very relevant here. One, `atom` returns true
if the argument is an atom. The second: `consp` returns true if its argument is
a cons.

Note: in general predicate functions end with `p` or `-p`. `atom`'s naming is an
unfortunate inconsistency.

When it comes to getting the first element and the rest of an sexpr, it might be
worth looking into `car` and `cdr` (or perhaps `first` and `rest`).