Run Python Code (Node)
===========================================
Category: *Python*

Execute a function from a loaded python file.

Inputs:
-------

Condition
    The input Condition

Module
    Name of the module without the '.py' ending. NOTE: File must have '.py' ending though!

Function
    Name of the callback without paranthesis

Use Argument
    Wether the function uses an argument

Argument
    The argument of the function. If packed as dict or list, multiple arguments can be given

Outputs:
--------

Done
    True if the node performed successfully, else False

Returned Value
    Return value of the function if there is one, else None 
    *This socket is optional*
