---
title: BooleanOperator
second_title: Справочник API Aspose.3D для Java
description: Булевый оператор позволяет применять булеву операцию к двум экземплярам.
type: docs
weight: 23
url: /ru/java/com.aspose.threed/booleanoperator/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class BooleanOperator extends Entity implements IMeshConvertible
```

Булевый оператор позволяет выполнять булеву операцию над двумя экземплярами [IMeshConvertible](../../com.aspose.threed/imeshconvertible).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BooleanOperator()](#BooleanOperator--) | Конструктор класса [BooleanOperator](../../com.aspose.threed/booleanoperator) |
| [BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second)](#BooleanOperator-com.aspose.threed.BooleanOperation-com.aspose.threed.A3DObject-com.aspose.threed.A3DObject-) | Создаёт новый экземпляр [BooleanOperator](../../com.aspose.threed/booleanoperator) с двумя операндами |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Получает ключ рендерера сущности, зарегистрированного в рендерере. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать эту сущность при экспорте. |
| [getFirst()](#getFirst--) | Первый операнд булевого оператора |
| [getName()](#getName--) | Получает имя. |
| [getOperator()](#getOperator--) | Булевый оператор, используемый в операции для создания результирующей сетки. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getSecond()](#getSecond--) | Второй операнд булевого оператора |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setFirst(BooleanOperand value)](#setFirst-com.aspose.threed.BooleanOperand-) | Первый операнд булевого оператора |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setOperator(BooleanOperation value)](#setOperator-com.aspose.threed.BooleanOperation-) | Булевый оператор, используемый в операции для создания результирующей сетки. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setSecond(BooleanOperand value)](#setSecond-com.aspose.threed.BooleanOperand-) | Второй операнд булевого оператора |
| [toMesh()](#toMesh--) | Выполнить булеву операцию над двумя операндами |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BooleanOperator() {#BooleanOperator--}
```
public BooleanOperator()
```


Конструктор класса [BooleanOperator](../../com.aspose.threed/booleanoperator)

### BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second) {#BooleanOperator-com.aspose.threed.BooleanOperation-com.aspose.threed.A3DObject-com.aspose.threed.A3DObject-}
```
public BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second)
```


Создаёт новый экземпляр [BooleanOperator](../../com.aspose.threed/booleanoperator) с двумя операндами

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operation | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Тип булевой операции |
| first | [A3DObject](../../com.aspose.threed/a3dobject) | Экземпляр [IMeshConvertible](../../com.aspose.threed/imeshconvertible), [HalfSpace](../../com.aspose.threed/halfspace) или [Node](../../com.aspose.threed/node) |
| second | [A3DObject](../../com.aspose.threed/a3dobject) | Экземпляр [IMeshConvertible](../../com.aspose.threed/imeshconvertible), [HalfSpace](../../com.aspose.threed/halfspace) или [Node](../../com.aspose.threed/node) |

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
### getFirst() {#getFirst--}
```
public BooleanOperand getFirst()
```


Первый операнд булевого оператора

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - The first operand of the Boolean operator
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getOperator() {#getOperator--}
```
public BooleanOperation getOperator()
```


Булевый оператор, используемый в операции для создания результирующей сетки.

**Returns:**
[BooleanOperation](../../com.aspose.threed/booleanoperation) - The Boolean operator used in the operation to create the result mesh.
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Получает сцену, к которой принадлежит этот объект

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSecond() {#getSecond--}
```
public BooleanOperand getSecond()
```


Второй операнд булевого оператора

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - The second operand of the Boolean operator
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
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Устанавливает, следует ли исключать эту сущность при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setFirst(BooleanOperand value) {#setFirst-com.aspose.threed.BooleanOperand-}
```
public void setFirst(BooleanOperand value)
```


Первый операнд булевого оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BooleanOperand](../../com.aspose.threed/booleanoperand) | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setOperator(BooleanOperation value) {#setOperator-com.aspose.threed.BooleanOperation-}
```
public void setOperator(BooleanOperation value)
```


Булевый оператор, используемый в операции для создания результирующей сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Новое значение |

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

### setSecond(BooleanOperand value) {#setSecond-com.aspose.threed.BooleanOperand-}
```
public void setSecond(BooleanOperand value)
```


Второй операнд булевого оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BooleanOperand](../../com.aspose.threed/booleanoperand) | Новое значение |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Выполнить булеву операцию над двумя операндами

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

