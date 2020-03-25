Set Object Dynamics (Node)
===========================================
Category: *Objects*

Enable / Disable an objects physics calculation.

Inputs:
-------

Condition
    The input Condition

Object
    The object to enable/disable physics of

Suspend
    Wether to disable the objects physics or enable them

Ghost
    Wether the object should be set to ghost (collisions will be ignored).
    Will only take effect if object is suspended

Outputs:
--------

Done
    True if the node performed successfully, else False