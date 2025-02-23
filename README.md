# Mirror3D
GDevelop extensions for creating and manipulating mirrors.

Расширение для GDevelop, позволяющее создавать зеркала и манипулировать ими.
Важные примечания:
1. Углы должны быть в радианах. Используйте выражение ToRad, чтобы преобразовать градусы в радианы.
2. GetX и тому подобные выражения могут возвращать неточное значение, если зеркало привязано к другому 3д - объекту.
3. Функция Rotate mirror воспринимает поворот по Z как поворот по Y (и наоборот).
4. Чтобы получить угол, равный углу объекта, попробуйте прибавить к последнему 90 градусов.
