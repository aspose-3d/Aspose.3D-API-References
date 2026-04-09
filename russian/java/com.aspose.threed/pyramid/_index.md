---
title: Пирамида
second_title: Справочник API Aspose.3D для Java
description: Параметрическая пирамида.
type: docs
weight: 142
url: /ru/java/com.aspose.threed/pyramid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Pyramid extends Primitive
```

Параметрическая пирамида.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Pyramid()](#Pyramid--) | Создать новый экземпляр пирамиды с областью основания по умолчанию (10, 10) и высотой по умолчанию (5) |
| [Pyramid(double xbottom, double ybottom, double height)](#Pyramid-double-double-double-) | Создать новый экземпляр пирамиды с указанной областью основания |
| [Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-double-double-double-double-double-) | Создать новый экземпляр пирамиды с указанной областью основания, верхней областью и высотой. |
| [Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-java.lang.String-double-double-double-double-double-) | Создать новый экземпляр пирамиды с указанной областью основания, верхней областью и высотой. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getBottomArea()](#getBottomArea--) | Площадь нижней крышки |
| [getBottomOffset()](#getBottomOffset--) | Смещение нижних вершин |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства. |
| [getCastShadows()](#getCastShadows--) | Получает, может ли эта геометрия отбрасывать тень |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Получает ключ рендерера сущности, зарегистрированного в рендерере. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать эту сущность при экспорте. |
| [getHeight()](#getHeight--) | Высота пирамиды |
| [getName()](#getName--) | Получает имя. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getReceiveShadows()](#getReceiveShadows--) | Получает, может ли эта геометрия принимать тень. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getTopArea()](#getTopArea--) | Площадь верхней крышки |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setBottomArea(Vector2 value)](#setBottomArea-com.aspose.threed.Vector2-) | Площадь нижней крышки |
| [setBottomOffset(Vector3 value)](#setBottomOffset-com.aspose.threed.Vector3-) | Смещение нижних вершин |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Устанавливает, может ли эта геометрия отбрасывать тень |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setHeight(double value)](#setHeight-double-) | Высота пирамиды |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Устанавливает, может ли эта геометрия принимать тень. |
| [setTopArea(Vector2 value)](#setTopArea-com.aspose.threed.Vector2-) | Площадь верхней крышки |
| [toMesh()](#toMesh--) | Преобразовать текущий объект в сетку |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pyramid() {#Pyramid--}
```
public Pyramid()
```


Создать новый экземпляр пирамиды с областью основания по умолчанию (10, 10) и высотой по умолчанию (5)

### Pyramid(double xbottom, double ybottom, double height) {#Pyramid-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double height)
```


Создать новый экземпляр пирамиды с указанной областью основания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xbottom | double | Длина по оси x основания |
| ybottom | double | Длина по оси y основания |
| высота | double | Высота пирамиды |

### Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-double-double-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)
```


Создать новый экземпляр пирамиды с указанной областью основания, верхней областью и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xbottom | double | Длина по оси x области основания |
| ybottom | double | Длина по оси y области основания |
| xtop | double | Длина по оси x верхней области |
| ytop | double | Длина по оси y верхней области |
| высота | double | Высота пирамиды |

### Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-java.lang.String-double-double-double-double-double-}
```
public Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)
```


Создать новый экземпляр пирамиды с указанной областью основания, верхней областью и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя пирамиды |
| xbottom | double | Длина по оси x области основания |
| ybottom | double | Длина по оси y области основания |
| xtop | double | Длина по оси x верхней области |
| ytop | double | Длина по оси y верхней области |
| высота | double | Высота пирамиды |

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
### getBottomArea() {#getBottomArea--}
```
public Vector2 getBottomArea()
```


Площадь нижней крышки

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the bottom cap
### getBottomOffset() {#getBottomOffset--}
```
public Vector3 getBottomOffset()
```


Смещение нижних вершин

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Offset for bottom vertices
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Высота пирамиды

**Returns:**
double - Высота пирамиды
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
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
### getTopArea() {#getTopArea--}
```
public Vector2 getTopArea()
```


Площадь верхней крышки

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the top cap
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
### setBottomArea(Vector2 value) {#setBottomArea-com.aspose.threed.Vector2-}
```
public void setBottomArea(Vector2 value)
```


Площадь нижней крышки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setBottomOffset(Vector3 value) {#setBottomOffset-com.aspose.threed.Vector3-}
```
public void setBottomOffset(Vector3 value)
```


Смещение нижних вершин

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Высота пирамиды

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Устанавливает, может ли эта геометрия принимать тень.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setTopArea(Vector2 value) {#setTopArea-com.aspose.threed.Vector2-}
```
public void setTopArea(Vector2 value)
```


Площадь верхней крышки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

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

