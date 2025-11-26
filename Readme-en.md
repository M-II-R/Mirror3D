# Mirror3D

! This extension may work strange !

GDevelop extensions for creating and manipulating mirrors.

Attention!
1. Use ToRad on the target angle when rotating!
2. GetX, GetY etc. can be inaccurate if mirror is attached to another 3D object.
3. "Rotate mirror" function thinks that Z angle is Y angle if the mirror is placed verticalle (local axes rotation seems to cause this).
4. To get object's angle try to add 90 to angle returned by expression.
