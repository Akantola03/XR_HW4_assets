# XR_HW3
My XR homework 3 assets and instructions:


Hand animations:

Add hands to controllers (LeftHand Controller)

moving pivot point:

go to pivot mode -> lock hand model(LeftHand) -> LeftHand Controller -> 
line the pivot point with palm (move the hand model).
(0.03, 0.01, 0.0)?

Copy component to RightHand


Animation:

LeftHand -> Add Component (animator)

Add avatar: assets -> LeftHand model -> inspector -> Rig -> Avatar def -> create from this model.

back to LeftHand -> select avatar (same for right hand)


Add controller: assets -> create animator controller -> double click


Got to LeftHand -> animation tab (window -> animation -> animation)


In animation tab:
Add property -> world

or go to the last frame -> record -> change the fingers rotation

________________________________________________________________________
________________________________________________________________________

Adding colliders to hands:

(edit time in project settings -> fixed timestamp 1/90)

Create an empty gameobject (same level with fingers) and add a box collider to it.

Add more colliders the same way.


Copy colliders to other hand:
Flip RightHand back.
Paste the colliders in the same level with fingers.
Line them up.
Flip RightHanf back and parent the colliders to right places.

Add rigidbody to both hands:
interpolate: interpolate
Collision Detec: Continious
Mass: 10 or 20


If you don't, add spehere colliders to controllers
