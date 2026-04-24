---
title: NurbsCurve
second_title: Справочник API Aspose.3D для Java
description: Кривая NURBS — это кривая, представленная NURBS Non-uniform rational basis spline. Кривая NURBS определяется её набором взвешенных контрольных точек и ... Компонент w в контрольной точке используется как вес контрольной точки, независимо от того, что это за ...
type: docs
weight: 112
url: /ru/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Инициализирует новый экземпляр класса [NurbsCurve](../../com.aspose.threed/nurbscurve). |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Инициализирует новый экземпляр класса [NurbsCurve](../../com.aspose.threed/nurbscurve). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | Вычислить NURBS-кривую |
| [evaluate(int steps)](#evaluate-int-) | Вычислить NURBS-кривую |
| [evaluateAt(double u)](#evaluateAt-double-) | Вычислить точку кривой в указанной позиции |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает цвет линии, значение по умолчанию — белый (1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Получает все контрольные точки |
| [getCurveType()](#getCurveType--) | Получает тип кривой. |
| [getDegree()](#getDegree--) | Получает степень NURBS-кривой, степень определяется как Order - 1 |
| [getDimension()](#getDimension--) | Получает размерность кривой. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Получает ключ рендерера сущности, зарегистрированного в рендерере. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать эту сущность при экспорте. |
| [getKnotVectors()](#getKnotVectors--) | Получает вектор узлов; это последовательность параметрических значений, определяющих, где и как контрольные точки влияют на NURBS-кривую. |
| [getMultiplicity()](#getMultiplicity--) | Получает мультипликативность. |
| [getName()](#getName--) | Получает имя. |
| [getOrder()](#getOrder--) | Получает порядок NURBS-кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getRational()](#getRational--) | Получает, является ли она рациональной; это значение указывает, является ли [NurbsCurve](../../com.aspose.threed/nurbscurve) рациональным сплайном или нерациональным сплайном. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Устанавливает цвет линии, значение по умолчанию — белый (1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Устанавливает тип кривой. |
| [setDegree(int value)](#setDegree-int-) | Устанавливает степень NURBS-кривой, степень определяется как Order - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Устанавливает размерность кривой. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setOrder(int value)](#setOrder-int-) | Устанавливает порядок NURBS-кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setRational(boolean value)](#setRational-boolean-) | Устанавливает, является ли она рациональной; это значение указывает, является ли [NurbsCurve](../../com.aspose.threed/nurbscurve) рациональным сплайном или нерациональным сплайном. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Инициализирует новый экземпляр класса [NurbsCurve](../../com.aspose.threed/nurbscurve).

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Инициализирует новый экземпляр класса [NurbsCurve](../../com.aspose.threed/nurbscurve).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


Вычислить NURBS-кривую

**Returns:**
com.aspose.threed.Vector4[] — точки на кривой
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


Вычислить NURBS-кривую

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| шаги | int | Частота вычисления между двумя соседними узлами, значение по умолчанию — 20 |

**Returns:**
com.aspose.threed.Vector4[] — точки на кривой
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Вычислить точку кривой в указанной позиции

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| u | double | Позиция на кривой, от 0 до 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Находит свойство. Оно может быть динамическим свойством (созданным с помощью CreateDynamicProperty/SetProperty) или нативным свойством (определяемым по его имени)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | java.lang.String | Имя свойства. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Получает цвет линии, значение по умолчанию — белый (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Получает все контрольные точки

**Returns:**
java.util.List<com.aspose.threed.Vector4> - все контрольные точки
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Получает тип кривой.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Получает степень NURBS-кривой, степень определяется как Order - 1

**Returns:**
int — степень NURBS-кривой, степень определяется как Order - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Получает размерность кривой.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Получает ключ рендерера сущности, зарегистрированного в рендерере.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Получает, следует ли исключать эту сущность при экспорте.

**Returns:**
boolean — следует ли исключать эту сущность при экспорте.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Получает вектор узлов; это последовательность параметрических значений, определяющих, где и как контрольные точки влияют на NURBS-кривую.

**Returns:**
java.util.List<java.lang.Double> — вектор узлов; это последовательность параметрических значений, определяющих, где и как контрольные точки влияют на NURBS-кривую.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Получает мультипликативность.

**Returns:**
java.util.List<java.lang.Integer> - кратность.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Получает порядок NURBS-кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой.

**Returns:**
int - порядок NURBS‑кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - все родительские узлы, объект может быть привязан к нескольким родительским узлам для инстанцирования геометрии
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Получает коллекцию всех свойств.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Получить значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |

**Returns:**
java.lang.Object - Значение найденного свойства
### getRational() {#getRational--}
```
public boolean getRational()
```


Получает, является ли она рациональной; это значение указывает, является ли данный [NurbsCurve](../../com.aspose.threed/nurbscurve) рациональным сплайном или нерациональным сплайном. Не‑рациональный B‑spline — частный случай рациональных B‑splines.

**Returns:**
boolean - указывает, является ли она рациональной; это значение показывает, является ли данный [NurbsCurve](../../com.aspose.threed/nurbscurve) рациональным сплайном или нерациональным сплайном. Не‑рациональный B‑spline — частный случай рациональных B‑splines.
### getScene() {#getScene--}
```
public Scene getScene()
```


Получает сцену, к которой принадлежит этот объект

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Удаляет динамическое свойство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Удалить указанное свойство, определяемое по имени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Устанавливает цвет линии, значение по умолчанию — белый (1, 1, 1)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Устанавливает тип кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Новое значение |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Устанавливает степень NURBS-кривой, степень определяется как Order - 1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Устанавливает размерность кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Новое значение **Примечание:** Для кривой [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) компонент z в контрольной точке не используется. |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Устанавливает, следует ли исключать эту сущность при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Устанавливает порядок NURBS-кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Новое значение |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Устанавливает значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |
| значение | java.lang.Object | Значение свойства |

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Устанавливает, является ли она рациональной; это значение указывает, является ли данный [NurbsCurve](../../com.aspose.threed/nurbscurve) рациональным сплайном или нерациональным сплайном. Не‑рациональный B‑spline — частный случай рациональных B‑splines.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

