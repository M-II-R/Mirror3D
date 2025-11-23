# Mirror3D

! This extension may work strange !

GDevelop extensions for creating and manipulating mirrors.

Расширение для GDevelop, позволяющее создавать зеркала и манипулировать ими.
Важные примечания:
(ENG) Attention!
1. Углы должны быть в радианах. Используйте выражение ToRad, чтобы преобразовать градусы в радианы.

   (ENG) Use ToRad on the target angle when rotating !!
2. GetX и тому подобные выражения могут возвращать неточное значение, если зеркало привязано к другому 3д - объекту.

   (ENG) GetX can be inaccurate if mirror is attached to another 3D object.
3. Функция Rotate mirror воспринимает поворот по Z как поворот по Y (и наоборот), если зеркало установлено вертикально, так как поворот, видимо, происходит по локальным осям.

   (ENG)"Rotate mirror" function thinks that Z angle is Y angle if the mirror is placed verticalle (local axes rotation seems to cause this).
4. Чтобы получить угол, равный углу объекта, попробуйте прибавить к последнему 90 градусов.
   (ENG) To get object's angle try to add 90 to angle returned by expression.
