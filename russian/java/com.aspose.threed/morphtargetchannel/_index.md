---
title: MorphTargetChannel
second_title: Справочник API Aspose.3D для Java
description: MorphTargetChannel используется для организации целевых геометрий.
type: docs
weight: 107
url: /ru/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

MorphTargetChannel используется [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) для организации целевых геометрий. Некоторые форматы файлов, такие как FBX, поддерживают несколько каналов одновременно. **Remarks:** Вес находится в диапазоне от 0 до 1.0, а вес по умолчанию для цели равен 0.0;
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | Инициализирует новый экземпляр класса [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
| [MorphTargetChannel()](#MorphTargetChannel--) | Инициализирует новый экземпляр класса [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
## Поля

| Поле | Описание |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | Вес по умолчанию для морф-таргета. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Получает вес для указанной геометрии |
| [getChannelWeight()](#getChannelWeight--) | Получает вес деформера этого канала. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Получает имя. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getTargets()](#getTargets--) | Получает все цели, связанные с каналом. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | Получает вес для указанной цели; если цель не принадлежит этому каналу, возвращается значение по умолчанию 0. |
| [getWeights()](#getWeights--) | Получает полные значения весов целевых геометрий. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Устанавливает вес для указанной геометрии |
| [setChannelWeight(double value)](#setChannelWeight-double-) | Устанавливает вес деформера этого канала. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | Устанавливает вес для указанной цели, значение по умолчанию 1, диапазон должен быть от 0 до 1. |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | Устанавливает вес для указанной цели, значение по умолчанию 1, диапазон должен быть от 0 до 1. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


Инициализирует новый экземпляр класса [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


Инициализирует новый экземпляр класса [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


Вес по умолчанию для морф-таргета.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Получает вес для указанной геометрии

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Целевая геометрия. |

**Returns:**
double - Вес
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


Получает вес деформера этого канала. Вес находится в диапазоне от 0.0 до 1.0

**Returns:**
double - вес деформера этого канала. Вес находится в диапазоне от 0.0 до 1.0
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


Получает все цели, связанные с каналом.

**Returns:**
java.util.List<com.aspose.threed.Shape> - все цели, связанные с каналом.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


Получает вес для указанной цели; если цель не принадлежит этому каналу, возвращается значение по умолчанию 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


Получает полные значения весов целевых геометрий.

**Returns:**
java.util.List<java.lang.Double> - полные значения весов целевых геометрий.
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Устанавливает вес для указанной геометрии

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Целевая геометрия. |
| значение | double | Новое значение |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


Устанавливает вес деформера этого канала. Вес находится в диапазоне от 0.0 до 1.0

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


Устанавливает вес для указанной цели, значение по умолчанию 1, диапазон должен быть от 0 до 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


Устанавливает вес для указанной цели, значение по умолчанию 1, диапазон должен быть от 0 до 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| вес | double |  |

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

