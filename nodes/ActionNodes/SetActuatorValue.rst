Set Actuator Value (Node)
===========================================
Category: *Logic Bricks*

Change a value within an actuator.

Inputs:
-------

Condition
    The input Condition

Actuator
    The actuator of which to change a value

Field
    Name of the value to change (e.g. layerWeight in Action Actuator)
    NOTE: Knowledge of the actuators attributes required, as each actuator type has different values, see Blender API

Value
    New value for the field, careful to use the right kind of value (String, Int, etc)!

Outputs:
--------

Done
    True if the node performed successfully, else False