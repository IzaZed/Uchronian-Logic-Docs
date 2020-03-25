Move To With Navmesh (Node)
===========================================
Category: *Transformation*

Move object to a location using a Navmesh.

Inputs:
-------

Condition
    The input Condition

Moving Object
    The object to be moved

Rotating Object
    The object to be rotated (can be same as moving object)

Navmesh Object
    Use this object to generate path

Destination
    Target as vector [x, y, z]

Move as Dynamic
    Wether to move the object using physics

Lin Speed
    Movement speed

Reach Threshold
    Stop moving the object when this close to Target

Look At
    Wether to look at next destination

Rot Axis
    Axis around which to rotate the object selected as Rotation Object

Front
    Axis with which to rotate to destination

Outputs:
--------

When Reached
    True if the object reached destination, else False
