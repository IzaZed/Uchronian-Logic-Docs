Ray (Node)
===========================================
Category: *Ray Casts*

Cast a ray from one position to another.

Inputs:
-------

Condition
    The input Condition

Origin
    Location from which to cast the ray as vector [x, y, z]

Destination
    Destination as vector [x, y, z]

Property
    Only look for objects with this Property

Distance
    Length of the ray

Outputs:
--------

Has Result
    True if the ray hit something

Picked Object
    None if the ray hit nothing, else the object it hit

Picked Point
    Hit location as vector [x, y, z]

Picked Normal
    Normal of the face the ray hit as vector [x, y, z]

Ray Direction
    Direction as vector [x, y, z]
