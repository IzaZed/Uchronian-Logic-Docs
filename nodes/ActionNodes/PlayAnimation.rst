Play Animation (Node)
===========================================
Category: *Animation*

Play selected animation using given parameters

Inputs:
-------

Condition
    The input Condition

Armature
    Armature Object which contains the action

Action Name
    Name of the action to play

Stop When Done
    Wether to loop the action or stop playback when maximum frame is reached

Start Frame
    Frame at which to start the animation

End Frame
    Frame at which to end the animation

Layer
    Play the animation on this layer

Priority
    Play animations with a lower number over animations with a higher number

Play Mode
    Play animation using this method

Layer Weight
    Influence of the layer animation is played on

Speed
    Playback speed

Blendin
    Frames to interpolate animations

Outputs:
--------

Started
    True if the animation has just Started

Running
    True as long as the animation is running

Finished
    True when the last frame is reached and animation stopped

Current Frame
    Returns the active frame of the animation
