# CS-3210-Project3
Functional Programming Assignment 3 PPL
------------------------------
## Tools recommended by professor
- SCL Database
- Emac Text editor
- Eclipse
-----------------------------------------
# (Defun Set-member(set item))
{
    Return T if item is a member of set.
    Return NIL if item is not a member of set
    The tyhpe of set is list
## Examples:
    (set-member'(1 2) 1) => T
    (set-member ' (1 2) 3) => NIL
}
------------------------------------------
# (Defun Set-union(set-1 set-2))
{
   Return the union of set-1 and set-2
   The result should contain no duplicates
   Assume set-1 contains no duplicates and set-2 contains no duplicates.
## Examples:
    (set-union ' (1 2) '(2 4)) =>'(1 2 4)
}
------------------------------------------
# (Defun Set-intersect(set-1 set-2))
{
    Return the intersection of set-1 and set-2
    This should contain no duplicates
    Assume set-1 contains no duplicates and set-2 contains no duplicates
## Examples:
    (set-intersection '(1 2) '(2 4))=> '(2)
}
------------------------------------------
# (Defun Set-Diff(set item))
{
    Return the difference of set-1 and set-2
    the result should contain no duplicates
    Assume set-1 contains no duplicates and set-2 contains no duplicates
## Examples:
    (set-diff '(1 2) '(2 4)) => '(1)
}
------------------------------------------
# (Defun boolean-xor(a b))
{
    Return the exlusive or of a and b
## Examples:
    (boolean-xor t nil) => t
    (boolean-xor nil nil) => nil
}
------------------------------------------
# (Defun boolean-implies(a b))
{
    Return the implication of a and b
## Examples:
    (boolean-implies t nil) => nil
    (boolean-implies nil nil) => t
}
------------------------------------------
# (Defun boolean-iff(a b))
{
    Return the bi-implication (if and only if) of a and b
## Examples:
    (boolean-iff t nil) => nil
    (boolean-iff nil nil) => t
}
------------------------------------------
# (Defun boolean-eval(exp))
{
    Handles NOT, AND, OR, XOR, IMPLIES, and IFF
## Examples:
    (boolean-eval '(and t nil)) => nil
    (boolean-eval '(and t (or nil t))) => t
}