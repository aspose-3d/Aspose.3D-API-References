---
title: BindPoint
second_title: Справочник API Aspose.3D для Java
description: Обычно BindPoint создаётся на свойстве объекта; некоторые типы свойств содержат несколько полей‑компонентов, например поле Vector3, которое создаст канал для каждого компонента и соединит поле с одной или несколькими экземплярами последовательностей ключевых кадров через каналы.
type: docs
weight: 19
url: /ru/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

Обычно [BindPoint](../../com.aspose.threed/bindpoint) создаётся на свойстве объекта; некоторые типы свойств содержат несколько полей‑компонентов (например поле Vector3), [BindPoint](../../com.aspose.threed/bindpoint) создаст канал для каждого компонента и соединит поле с одной или несколькими экземплярами последовательностей ключевых кадров через каналы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | Инициализирует новый экземпляр класса [BindPoint](../../com.aspose.threed/bindpoint). |
## Методы

| Метод | Описание |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Добавляет указанное свойство канала. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Добавляет указанное свойство канала. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Привязывает последовательность ключевых кадров к указанному каналу |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Создаёт новую кривую и соединяет её с первым каналом отображения кривой |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [get(String channelName)](#get-java.lang.String-) | Получает канал по заданному имени |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Получает канал по заданному имени |
| [getChannelsCount()](#getChannelsCount--) | Возвращает общее количество каналов свойств, определённых в этом отображении анимационной кривой. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Получает первую последовательность ключевых кадров в указанном канале |
| [getName()](#getName--) | Получает имя. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty()](#getProperty--) | Получает свойство, связанное с CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [resetChannels()](#resetChannels--) | Очищает каналы свойств этого отображения анимационной кривой. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | Получает свойство, связанное с CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [toString()](#toString--) | Форматирует объект в строку |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


Инициализирует новый экземпляр класса [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Сцена, содержащая анимацию. |
| prop | [Property](../../com.aspose.threed/property) | Свойство. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Добавляет указанное свойство канала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |
| type | java.lang.Class<?> | Тип. |
| значение | java.lang.Object | Значение. |

**Returns:**
boolean — true, если канал был добавлен, иначе false.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Добавляет указанное свойство канала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |
| значение | java.lang.Object | Значение. |

**Returns:**
boolean — true, если канал был добавлен, иначе false.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Привязывает последовательность ключевых кадров к указанному каналу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelName | java.lang.String | К какому каналу будет привязана последовательность ключевых кадров |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Последовательность ключевых кадров для привязки |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Создаёт новую кривую и соединяет её с первым каналом отображения кривой

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя новой последовательности. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Получает канал по заданному имени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelName | java.lang.String | Имя канала |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Получает канал по заданному имени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelName | java.lang.String | Имя канала для поиска |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Возвращает общее количество каналов свойств, определённых в этом отображении анимационной кривой.

**Returns:**
int - Количество каналов.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


Получает первую последовательность ключевых кадров в указанном канале

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelName | java.lang.String | Имя канала для поиска |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


Получает свойство, связанное с CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Очищает каналы свойств этого отображения анимационной кривой.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


Получает свойство, связанное с CurveMapping

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Новое значение |

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


Форматирует объект в строку

**Returns:**
java.lang.String - Строка объекта
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

