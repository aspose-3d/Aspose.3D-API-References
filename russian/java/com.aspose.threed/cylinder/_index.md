---
title: Цилиндр
second_title: Справочник API Aspose.3D для Java
description: Параметризованный цилиндр.
type: docs
weight: 40
url: /ru/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Параметризованный цилиндр. Его также можно использовать для представления конуса, когда один из параметров radiusTop/radiusBottom равен нулю.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Cylinder()](#Cylinder--) | Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства. |
| [getCastShadows()](#getCastShadows--) | Получает, может ли эта геометрия отбрасывать тень |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Получает ключ рендерера сущности, зарегистрированного в рендерере. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать эту сущность при экспорте. |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | Получает, следует ли генерировать цилиндр в виде веера, когда ThetaLength меньше 2\*PI, иначе модель не будет разрезана. |
| [getHeight()](#getHeight--) | Получает высоту цилиндра. |
| [getHeightSegments()](#getHeightSegments--) | Получает сегменты высоты. |
| [getName()](#getName--) | Получает имя. |
| [getOffsetBottom()](#getOffsetBottom--) | Получает смещение трансформации вершин нижней стороны. |
| [getOffsetTop()](#getOffsetTop--) | Получает смещение трансформации вершин верхней стороны. |
| [getOpenEnded()](#getOpenEnded--) | Получает значение, указывающее, открытый ли этот [Cylinder](../../com.aspose.threed/cylinder) с незакрытыми концами. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getRadialSegments()](#getRadialSegments--) | Получает радиальные сегменты. |
| [getRadiusBottom()](#getRadiusBottom--) | Получает радиус нижней крышки цилиндра. |
| [getRadiusTop()](#getRadiusTop--) | Получает радиус верхней крышки цилиндра. |
| [getReceiveShadows()](#getReceiveShadows--) | Получает, может ли эта геометрия принимать тень. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getShearBottom()](#getShearBottom--) | Получает значение сдвига трансформации нижней стороны, вектор хранит (x-ось, z-ось) значение сдвига, измеренное в радианах, значение по умолчанию — (0, 0). |
| [getShearTop()](#getShearTop--) | Получает значение сдвига трансформации верхней стороны, вектор хранит (x-ось, z-ось) значение сдвига, измеренное в радианах, значение по умолчанию — (0, 0). |
| [getThetaLength()](#getThetaLength--) | Получает длину θ. |
| [getThetaStart()](#getThetaStart--) | Получает начальное значение θ. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Устанавливает, может ли эта геометрия отбрасывать тень |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | Устанавливает, генерировать ли цилиндр в виде веера, когда ThetaLength меньше 2\*PI, иначе модель не будет обрезана. |
| [setHeight(double value)](#setHeight-double-) | Устанавливает высоту цилиндра. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Устанавливает сегменты высоты. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | Устанавливает смещение трансформации вершин нижней стороны. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | Устанавливает смещение трансформации вершин верхней стороны. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | Устанавливает значение, указывающее, является ли данный [Cylinder](../../com.aspose.threed/cylinder) открытым. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Устанавливает радиальные сегменты. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | Устанавливает радиус нижней крышки цилиндра. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | Устанавливает радиус верхней крышки цилиндра. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Устанавливает, может ли эта геометрия принимать тень. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | Устанавливает значение сдвига трансформации нижней стороны, вектор хранит (x-ось, z-ось) значение сдвига, измеренное в радианах, значение по умолчанию — (0, 0). |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | Устанавливает значение сдвига трансформации верхней стороны, вектор хранит (x-ось, z-ось) значение сдвига, измеренное в радианах, значение по умолчанию — (0, 0). |
| [setThetaLength(double value)](#setThetaLength-double-) | Устанавливает длину theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Устанавливает начало theta. |
| [toMesh()](#toMesh--) | Преобразовать текущий объект в сетку |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder).

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| radius | double | Радиус верхней и нижней крышки. |
| высота | double | Высота. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| radiusTop | double | Радиус верхней части. |
| radiusBottom | double | Радиус нижней части. |
| высота | double | Высота. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| radiusTop | double | Радиус верхней крышки цилиндра. |
| radiusBottom | double | Радиус нижней крышки цилиндра. |
| высота | double | Высота цилиндра. |
| radialSegments | int | Радиальные сегменты верхних и нижних кругов.. |
| heightSegments | int | Сегменты высоты. |
| openEnded | boolean | Если установить в  true  цилиндр не будет иметь нижних/верхних крышек.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Инициализирует новый экземпляр класса [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя этого объекта |
| radiusTop | double | Радиус верхней крышки цилиндра. |
| radiusBottom | double | Радиус нижней крышки цилиндра. |
| высота | double | Высота цилиндра. |
| radialSegments | int | Радиальные сегменты верхних и нижних кругов.. |
| heightSegments | int | Сегменты высоты. |
| openEnded | boolean | Если установить в  true  цилиндр не будет иметь нижних/верхних крышек.. |
| thetaStart | double | Начало Theta. |
| thetaLength | double | Длина Theta. |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Получает, может ли эта геометрия отбрасывать тень

**Returns:**
boolean - может ли эта геометрия отбрасывать тень
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Получает ключ рендерера сущности, зарегистрированного в рендерере.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Получает, следует ли исключать эту сущность при экспорте.

**Returns:**
boolean — следует ли исключать эту сущность при экспорте.
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


Получает, следует ли генерировать цилиндр в виде веера, когда ThetaLength меньше 2\*PI, иначе модель не будет разрезана.

**Returns:**
boolean - генерировать цилиндр в виде вентилятора, когда ThetaLength меньше 2\*PI, иначе модель не будет обрезана.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получает высоту цилиндра.

**Returns:**
double - высота цилиндра.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Получает сегменты высоты.

**Returns:**
int - сегменты высоты.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Получает смещение трансформации вершин нижней стороны.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Получает смещение трансформации вершин верхней стороны.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


Получает значение, указывающее, является ли этот [Cylinder](../../com.aspose.threed/cylinder) открытым. Значение по умолчанию — false.

**Returns:**
boolean - значение, указывающее, является ли этот [Cylinder](../../com.aspose.threed/cylinder) открытым. Значение по умолчанию — false.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Получает радиальные сегменты.

**Returns:**
int - радиальные сегменты.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Получает радиус нижней крышки цилиндра.

**Returns:**
double - радиус нижней крышки цилиндра.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


Получает радиус верхней крышки цилиндра.

**Returns:**
double - радиус верхней крышки цилиндра.
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Получает, может ли эта геометрия принимать тень.

**Returns:**
boolean - может ли эта геометрия принимать тень.
### getScene() {#getScene--}
```
public Scene getScene()
```


Получает сцену, к которой принадлежит этот объект

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


Получает значение сдвига трансформации нижней стороны, вектор хранит (x-ось, z-ось) значение сдвига, измеренное в радианах, значение по умолчанию — (0, 0).

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


Получает значение сдвига трансформации верхней стороны, вектор хранит (x-ось, z-ось) значение сдвига, измеренное в радианах, значение по умолчанию — (0, 0).

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Получает длину теты. Значение по умолчанию — 2\\u03c0.

**Returns:**
double - длина теты. Значение по умолчанию — 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Получает начальное значение теты. Значение по умолчанию — 0.

**Returns:**
double - начальное значение теты. Значение по умолчанию — 0.
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Устанавливает, может ли эта геометрия отбрасывать тень

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Устанавливает, следует ли исключать эту сущность при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


Устанавливает, генерировать ли цилиндр в виде веера, когда ThetaLength меньше 2\*PI, иначе модель не будет обрезана.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Устанавливает высоту цилиндра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Устанавливает сегменты высоты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


Устанавливает смещение трансформации вершин нижней стороны.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


Устанавливает смещение трансформации вершин верхней стороны.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


Устанавливает значение, указывающее, является ли этот [Cylinder](../../com.aspose.threed/cylinder) открытым. Значение по умолчанию — false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Устанавливает радиальные сегменты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


Устанавливает радиус нижней крышки цилиндра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


Устанавливает радиус верхней крышки цилиндра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Устанавливает, может ли эта геометрия принимать тень.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


Устанавливает значение сдвига трансформации нижней стороны, вектор хранит (x-ось, z-ось) значение сдвига, измеренное в радианах, значение по умолчанию — (0, 0).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


Устанавливает значение сдвига трансформации верхней стороны, вектор хранит (x-ось, z-ось) значение сдвига, измеренное в радианах, значение по умолчанию — (0, 0).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Устанавливает длину теты. Значение по умолчанию — 2\\u03c0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Устанавливает начальное значение теты. Значение по умолчанию — 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Преобразовать текущий объект в сетку

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

