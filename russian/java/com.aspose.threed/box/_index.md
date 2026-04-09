---
title: Box
second_title: Справочник API Aspose.3D для Java
description: Коробка.
type: docs
weight: 26
url: /ru/java/com.aspose.threed/box/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Box extends Primitive
```

Коробка.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Box()](#Box--) | Инициализирует новый экземпляр класса [Box](../../com.aspose.threed/box). |
| [Box(double length, double width, double height)](#Box-double-double-double-) | Инициализирует новый экземпляр класса [Box](../../com.aspose.threed/box). |
| [Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments)](#Box-java.lang.String-double-double-double-int-int-int-) | Инициализирует новый экземпляр класса [Box](../../com.aspose.threed/box). |
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
| [getHeight()](#getHeight--) | Возвращает высоту коробки, выровненной по оси y. |
| [getHeightSegments()](#getHeightSegments--) | Получает или задаёт сегменты высоты. |
| [getLength()](#getLength--) | Возвращает длину коробки, выровненной по оси z. |
| [getLengthSegments()](#getLengthSegments--) | Возвращает сегменты длины. |
| [getName()](#getName--) | Получает имя. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getReceiveShadows()](#getReceiveShadows--) | Получает, может ли эта геометрия принимать тень. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getWidth()](#getWidth--) | Возвращает ширину коробки, выровненной по оси x. |
| [getWidthSegments()](#getWidthSegments--) | Возвращает сегменты ширины |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Устанавливает, может ли эта геометрия отбрасывать тень |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setHeight(double value)](#setHeight-double-) | Устанавливает высоту коробки, выровненной по оси y. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Получает или задаёт сегменты высоты. |
| [setLength(double value)](#setLength-double-) | Устанавливает длину коробки, выровненной по оси z. |
| [setLengthSegments(int value)](#setLengthSegments-int-) | Устанавливает сегменты длины. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Устанавливает, может ли эта геометрия принимать тень. |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину коробки, выровненной по оси x. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | Устанавливает сегменты ширины |
| [toMesh()](#toMesh--) | Преобразовать текущий объект в сетку |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Box() {#Box--}
```
public Box()
```


Инициализирует новый экземпляр класса [Box](../../com.aspose.threed/box).

### Box(double length, double width, double height) {#Box-double-double-double-}
```
public Box(double length, double width, double height)
```


Инициализирует новый экземпляр класса [Box](../../com.aspose.threed/box).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| длина | double | Длина коробки, выровненной по оси z. |
| ширина | double | Ширина коробки, выровненной по оси x. |
| высота | double | Высота коробки, выровненной по оси y. |

### Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments) {#Box-java.lang.String-double-double-double-int-int-int-}
```
public Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments)
```


Инициализирует новый экземпляр класса [Box](../../com.aspose.threed/box).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя коробки. |
| длина | double | Длина коробки, выровненной по оси z. |
| ширина | double | Ширина коробки, выровненной по оси x. |
| высота | double | Высота коробки, выровненной по оси y. |
| lengthSegments | int | Сегменты длины. |
| widthSegments | int | Сегменты ширины. |
| heightSegments | int | Сегменты высоты. |

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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Возвращает высоту коробки, выровненной по оси y.

**Returns:**
double - высота коробки, выровненной по оси y.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Получает или задаёт сегменты высоты.

**Returns:**
int - получает или задает сегменты высоты.
### getLength() {#getLength--}
```
public double getLength()
```


Возвращает длину коробки, выровненной по оси z.

**Returns:**
double - длина коробки, выровненной по оси z.
### getLengthSegments() {#getLengthSegments--}
```
public int getLengthSegments()
```


Возвращает сегменты длины.

**Returns:**
int - сегменты длины.
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
### getWidth() {#getWidth--}
```
public double getWidth()
```


Возвращает ширину коробки, выровненной по оси x.

**Returns:**
double - ширина коробки, выровненной по оси x.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


Возвращает сегменты ширины

**Returns:**
int - сегменты ширины
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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Устанавливает высоту коробки, выровненной по оси y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Получает или задаёт сегменты высоты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setLength(double value) {#setLength-double-}
```
public void setLength(double value)
```


Устанавливает длину коробки, выровненной по оси z.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setLengthSegments(int value) {#setLengthSegments-int-}
```
public void setLengthSegments(int value)
```


Устанавливает сегменты длины.

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

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Устанавливает ширину коробки, выровненной по оси x.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


Устанавливает сегменты ширины

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

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

