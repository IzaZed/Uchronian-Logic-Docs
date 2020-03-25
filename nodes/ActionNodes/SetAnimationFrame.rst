Set Animation Frame (Node)
===========================================
Category: *Animation*

Set the frame of an animation. Useful for animations bound to a property.

Inputs:
-------

Condition
    The input Condition

Object
    The Object which performs the action. Can be Object or Armature (or other)

Action Name
    Name of the action to modify. Must be active for selected object (Dope Sheet Editor)

Animation Layer
    The layer on which the action plays. Lower layers get overwritten by higher ones.

Animation Frame
    The frame of the animation to be set. Can be interoplated subframes too, allowing you to use Float values.

Outputs:
--------

Done
    True if the node performed successfully, else False