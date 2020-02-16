Follow Path (Node)
===========================================

Makes an object move between children of an object. Can be used to create movement patterns for NPCs.
Destination order depends on naming (name.001, name.002, name.003, etc.)

Inputs:
-------

Condition
    The input condition

Moving Object
    The object following the Path

Rotating Object
    The object to make use of the rotation. Can be used to rotate only parts of the moving entity

Path
    The parent object of the path (Not included in path destinations)

Loop
    Wether to restart the path once the last destination is reached

Optional Navmesh
    If set: use the given navmesh to get to the destination points

Move as Dynamic
    Wether to use physics to move the object, using simple translation if False

Lin Speed
    Speed with which the moving object travels to the next destination

Reach Threshold
    The distance at which the object is considered "at destination" and the next destination is set

Look at
    Wether to rotate the object to the current destination

Rot Speed
    Optional; Set the speed at which to rotate the Rotating Object

Rot Axis
    The axis on which to rotate the Rotating Object

Front
    The forward facing axis

Outputs:
--------


Execute the given Actuator (sets the actuator to active,
does not deactivate it when done)

Inputs:
-------

Condition
    The input condition

Actuator
    The Actuator to activate

Outputs:
--------

Done
    True if the node performed successfully, else False
