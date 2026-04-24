---
title: Кость
second_title: Справочник API Aspose.3D для Java
description: Кость определяет подмножество контрольных точек геометрии и задает вес смешивания для каждой контрольной точки.
type: docs
weight: 20
url: /ru/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Кость определяет подмножество контрольных точек геометрии и задает вес смешивания для каждой контрольной точки. Объект [Bone](../../com.aspose.threed/bone) нельзя использовать напрямую, вместо него используется экземпляр [SkinDeformer](../../com.aspose.threed/skindeformer) для деформации геометрии, и [SkinDeformer](../../com.aspose.threed/skindeformer) поставляется с набором костей, каждая кость привязана к узлу. ПРИМЕЧАНИЕ: Контрольная точка геометрии может быть привязана к более чем одной кости.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | Инициализирует новый экземпляр класса [Bone](../../com.aspose.threed/bone). |
| [Bone()](#Bone--) | Инициализирует новый экземпляр класса [Bone](../../com.aspose.threed/bone). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [get(int index)](#get-int-) | Получает вес смешивания указанной контрольной точки |
| [getBoneTransform()](#getBoneTransform--) | Получает матрицу преобразования кости. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | Режим соединения кости определяет способ, которым кость соединяется или связывается с родительской костью в иерархической структуре. |
| [getName()](#getName--) | Получает имя. |
| [getNode()](#getNode--) | Получает узел. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getTransform()](#getTransform--) | Получает матрицу преобразования узла, содержащего кость. |
| [getWeight(int index)](#getWeight-int-) | Получает вес для контрольной точки, указанной индексом |
| [getWeightCount()](#getWeightCount--) | Получает количество весов, которое автоматически расширяется методом [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [set(int index, double value)](#set-int-double-) | Устанавливает вес смешивания указанной контрольной точки |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Устанавливает матрицу преобразования кости. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | Режим соединения кости определяет способ, которым кость соединяется или связывается с родительской костью в иерархической структуре. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Устанавливает узел. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Устанавливает матрицу преобразования узла, содержащего кость. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Устанавливает вес для контрольной точки, указанной индексом |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


Инициализирует новый экземпляр класса [Bone](../../com.aspose.threed/bone).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |

### Bone() {#Bone--}
```
public Bone()
```


Инициализирует новый экземпляр класса [Bone](../../com.aspose.threed/bone).

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Получает вес смешивания указанной контрольной точки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс веса |

**Returns:**
double — Вес
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Получает матрицу преобразования кости.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


Режим соединения кости определяет способ, которым кость соединяется или связывается с родительской костью в иерархической структуре.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getNode() {#getNode--}
```
public Node getNode()
```


Получает узел. Узел кости — это кость, к которой прикреплена кожа, [SkinDeformer](../../com.aspose.threed/skindeformer) будет использовать узел кости для влияния на смещение контрольных точек. Обычно к узлу кости прикреплен [Skeleton](../../com.aspose.threed/skeleton), но это не обязательно. Прикреплённый [Skeleton](../../com.aspose.threed/skeleton) обычно используется программным обеспечением DCC для отображения скелета пользователю.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Получает матрицу преобразования узла, содержащего кость.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Получает вес для контрольной точки, указанной индексом

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс контрольной точки |

**Returns:**
double — вес по указанному индексу или 0, если индекс недействителен
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Получает количество весов, которое автоматически расширяется методом [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int — количество весов, которое автоматически расширяется методом [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Устанавливает вес смешивания указанной контрольной точки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс веса |
| значение | double | Новое значение |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Устанавливает матрицу преобразования кости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Новое значение |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


Режим соединения кости определяет способ, которым кость соединяется или связывается с родительской костью в иерархической структуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Устанавливает узел. Узел кости — это кость, к которой прикреплена кожа, [SkinDeformer](../../com.aspose.threed/skindeformer) будет использовать узел кости для влияния на смещение контрольных точек. Обычно к узлу кости прикреплен [Skeleton](../../com.aspose.threed/skeleton), но это не обязательно. Прикреплённый [Skeleton](../../com.aspose.threed/skeleton) обычно используется программным обеспечением DCC для отображения скелета пользователю.

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Устанавливает матрицу преобразования узла, содержащего кость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Новое значение |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Устанавливает вес для контрольной точки, указанной индексом

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс контрольной точки |
| вес | double | Новый вес |

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

