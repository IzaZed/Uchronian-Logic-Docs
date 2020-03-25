Set Object Parent (Node)
===========================================
Category: *Objects*

Set the parent of an object. The child object will not perform physical calculation exept for collisions anymore.

Inputs:
-------

Condition
    The input Condition

Child Object
    The object be be parented to another

Parent Object
    The child will inherit data from this object

Compund
    Wether to use a combined collision shape for the parent object

Ghost
    Wether to have the child object be a ghost (Collisions are ignored)

Outputs:
--------

Done
    True if the node performed successfully, else False