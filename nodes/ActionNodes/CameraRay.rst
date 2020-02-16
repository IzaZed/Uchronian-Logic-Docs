Camera Ray (Node)
===========================================
Category: *Ray Casts*

Casts a ray from the camera into the scene.

Inputs:
-------

Condition
    The input Condition

Camera
    The camera object from which to cast a ray

Aim
    Screen coordinates where to cast the ray as Vector [X, Y]

Property
    Only look for objects with this property (Optional)

Distance
    Distance of the raycast

Outputs:
--------

Has Result
    True if the ray hit anything, else False

Picked Object
    The Object at which the ray hit

Picked Point
    The point at which the ray hit as Vector [X, Y, Z]

Picked Normal
    The normal of the hit face as Vector [X, Y, Z]
