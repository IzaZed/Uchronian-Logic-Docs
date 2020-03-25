Mouse Ray (Node)
===========================================
Category: *Ray Casts*

Casts a ray from the camera to where the mouse is pointing.

Inputs:
-------

Condition
    The input Condition

Camera
    The camera object from which to cast the ray

Property
    An optional property. If set, only count if the ray hits anything with this property

Distance
    The distance the ray travels

Outputs:
--------

Has Result
    True if the ray hit a valid target, else False

Picked object
    The Object that got hit by the ray

PickedPoint
    Vector [X, Y, Z], the point that was hit by the ray

PickedNormal
    Vactor [X, Y, Z], The normal vector of the face the ray hit
