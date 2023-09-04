# letandconst

1. What is the difference between var and let?
   Var is a variable that can be redeclared and let is a variable that can't be redeclared (but can be redefined)
2. What is the difference between var and const?
   Const will stay the same no matter what (usually used for arrays and objects)
3. What is the difference between let and const?
   Let can be redefined and const cannot
4. What is hoisting?
   When using var you can access the variable name and it’s undefined value before it's used later on.Function declarations are also hoisted and can be invoked “before” they are defined in a codebase.

var PI = 3.14;
PI = 42; // stop me from doing this!
