Mouse Look (Node)
===========================================
Category: *Mouse*

Makes one or to objects move corresponding to mouse movevment.

Inputs:
-------

Condition
    The input Condition

Main Object
    The object that rotates around the Z axis (Left/Right)
    and, if no Head is set, around the Y axis (Up/Down)

Head (Optional)
    When set, the Main object does not rotate around the
    Y axis, but the Head does

Inverted
    Wether or not the Y axis (Up/Down) rotation is inverted

Sensitivity
    Sets the mouse sensitivity

Cap Left / Right
    Wether or not to cap Z axis rotation

Limits Z
    A set of two values; the first defining how far to the left
    the player can look, the second how far to the right.
    Uses degrees, can only be positive

Cap Up / Down
    Wether or not to cap Y axis rotation

Limits Y
    A set of two values; the first defining how far up
    the player can look, the second how far down.
    Uses degrees, can only be positive

Outputs:
--------

Done
    True if the node performed successfully, else False
