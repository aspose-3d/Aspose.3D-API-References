---
title: AnimationChannel
second_title: Справочник API Aspose.3D для Java
description: Канал сопоставляет поле компонента свойства с набором последовательностей ключевых кадров
type: docs
weight: 13
url: /ru/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

Канал сопоставляет компонентное поле свойства с набором последовательностей ключевых кадров.
## Методы

| Метод | Описание |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Создать новый ключевой кадр с указанным значением |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Создать новый ключевой кадр с указанным значением |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getBindPoint()](#getBindPoint--) | Получает точку привязки свойства, которой принадлежит эта кривая |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | Получает тип поля компонента |
| [getDefaultValue()](#getDefaultValue--) | Получает значение по умолчанию канала. |
| [getKeyFrames()](#getKeyFrames--) | Получает ключевые кадры этой кривой. |
| [getKeyframeSequence()](#getKeyframeSequence--) | Получает связанную последовательность ключевых кадров внутри этого канала |
| [getName()](#getName--) | Получает имя. |
| [getPostBehavior()](#getPostBehavior--) | Получает пост‑поведение, указывающее, каким должно быть выборочное значение после последнего ключевого кадра. |
| [getPreBehavior()](#getPreBehavior--) | Получает пре‑поведение, указывающее, каким должно быть выборочное значение перед первым ключевым кадром. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Получает перечислитель для обхода всех ключевых кадров. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [reset()](#reset--) | Удаляет все ключевые кадры и сбрасывает пост/пре‑поведения. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Устанавливает значение по умолчанию канала. |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | Получает связанную последовательность ключевых кадров внутри этого канала |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Создать новый ключевой кадр с указанным значением

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| время | double | Позиция времени (измеряется в секундах) |
| значение | float | Значение в этой позиции времени |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Создать новый ключевой кадр с указанным значением

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| время | double | Позиция времени (измеряется в секундах) |
| значение | float | Значение в этой позиции времени |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | Тип интерполяции этого ключевого кадра |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Получает точку привязки свойства, которой принадлежит эта кривая

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


Получает тип поля компонента

**Returns:**
java.lang.Class<?> - тип поля компонента
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


Получает значение по умолчанию канала. Если у канала нет подключенных последовательностей ключевых кадров, значение по умолчанию будет использоваться во время оценки анимации. Реальный пример: анимация изменяет только координату x узла, y и z не меняются, тогда значение по умолчанию будет использоваться при полной оценке трансляции.

**Returns:**
java.lang.Object - значение по умолчанию канала. Если у канала нет подключенных последовательностей ключевых кадров, значение по умолчанию будет использоваться во время оценки анимации. Реальный пример: анимация изменяет только координату x узла, y и z не меняются, тогда значение по умолчанию будет использоваться при полной оценке трансляции.
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Получает ключевые кадры этой кривой.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - ключевые кадры этой кривой.
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


Получает связанную последовательность ключевых кадров внутри этого канала

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Получает пост‑поведение, указывающее, каким должно быть выборочное значение после последнего ключевого кадра.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Получает пре‑поведение, указывающее, каким должно быть выборочное значение перед первым ключевым кадром.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


Получает перечислитель для обхода всех ключевых кадров.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


Удаляет все ключевые кадры и сбрасывает пост/пре‑поведения.

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


Устанавливает значение по умолчанию канала. Если у канала нет подключенных последовательностей ключевых кадров, значение по умолчанию будет использоваться во время оценки анимации. Реальный пример: анимация изменяет только координату x узла, y и z не меняются, тогда значение по умолчанию будет использоваться при полной оценке трансляции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object | Новое значение |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


Получает связанную последовательность ключевых кадров внутри этого канала

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Новое значение |

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

