---
title: AnimationNode
second_title: Справочник API Aspose.3D для Java
description: Aspose.3Ds поддерживает иерархию анимации, каждая анимация может состоять из нескольких анимаций и определения ключевых кадров анимации.
type: docs
weight: 15
url: /ru/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D поддерживает иерархию анимации, каждая анимация может состоять из нескольких анимаций и определения ключевых кадров анимации. [AnimationNode](../../com.aspose.threed/animationnode) определяет преобразование значения свойства во времени, например, узел анимации может использоваться для управления преобразованием узла или другими числовыми свойствами объекта [A3DObject](../../com.aspose.threed/a3dobject).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Инициализирует новый экземпляр класса [AnimationNode](../../com.aspose.threed/animationnode). |
| [AnimationNode()](#AnimationNode--) | Инициализирует новый экземпляр класса [AnimationNode](../../com.aspose.threed/animationnode). |
## Методы

| Метод | Описание |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Создаёт BindPoint на основе типа данных свойства. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Находит точку привязки по цели и имени. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Получает точку привязки анимации для указанного свойства. |
| [getBindPoints()](#getBindPoints--) | Получает текущие точки привязки свойства. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Получает последовательность ключевых кадров для указанного свойства. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Получает последовательность ключевых кадров для заданного свойства и канала. |
| [getName()](#getName--) | Получает имя. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getSubAnimations()](#getSubAnimations--) | Получает поданимационные узлы текущих анимаций |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Инициализирует новый экземпляр класса [AnimationNode](../../com.aspose.threed/animationnode).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Инициализирует новый экземпляр класса [AnimationNode](../../com.aspose.threed/animationnode).

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Создаёт BindPoint на основе типа данных свойства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Объект. |
| propName | java.lang.String | Имя свойства. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Находит точку привязки по цели и имени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Цель точки привязки для поиска. |
| имя | java.lang.String | Имя точки привязки для поиска. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Получает точку привязки анимации для указанного свойства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | На каком объекте создать точку привязки. |
| propName | java.lang.String | Имя свойства. |
| создать | boolean | Если установлено значение true, создать точку привязки, если она не существует. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Получает текущие точки привязки свойства.

**Returns:**
java.util.List<com.aspose.threed.BindPoint> — текущие точки привязки свойства
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


Получает последовательность ключевых кадров для указанного свойства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | На каком экземпляре создать последовательность ключевых кадров. |
| propName | java.lang.String | Имя свойства. |
| создать | boolean | Если установлено значение true, создать последовательность, если она не существует. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Получает последовательность ключевых кадров для заданного свойства и канала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | На каком экземпляре создать последовательность ключевых кадров. |
| propName | java.lang.String | Имя свойства. |
| channelName | java.lang.String | Имя канала. |
| создать | boolean | Если установлено значение true, создать анимационную последовательность, если она не существует. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Получает поданимационные узлы текущих анимаций

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> — поданимационные узлы текущих анимаций
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
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

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

