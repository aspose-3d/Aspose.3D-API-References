---
title: ImageRenderOptions
second_title: Справочник API Aspose.3D для Java
description: Параметры для  и
type: docs
weight: 83
url: /ru/java/com.aspose.threed/imagerenderoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class ImageRenderOptions extends A3DObject
```

Параметры для [Scene](../../com.aspose.threed/scene) и [Scene](../../com.aspose.threed/scene)
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageRenderOptions()](#ImageRenderOptions--) | Инициализировать экземпляр [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getAssetDirectories()](#getAssetDirectories--) | Каталоги, в которых хранятся внешние ресурсы (например, текстуры) |
| [getBackgroundColor()](#getBackgroundColor--) | Цвет фона результата рендеринга. |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Получает, следует ли рендерить тени. |
| [getName()](#getName--) | Получает имя. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setAssetDirectories(ArrayList<String> value)](#setAssetDirectories-java.util.ArrayList-java.lang.String--) | Каталоги, в которых хранятся внешние ресурсы (например, текстуры) |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Цвет фона результата рендеринга. |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Устанавливает, следует ли рендерить тени. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageRenderOptions() {#ImageRenderOptions--}
```
public ImageRenderOptions()
```


Инициализировать экземпляр [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions)

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
### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Каталоги, в которых хранятся внешние ресурсы (например, текстуры)

**Returns:**
java.util.ArrayList<java.lang.String> - Каталоги, в которых хранятся внешние ресурсы (например, текстуры)
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Цвет фона результата рендеринга.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The background color of the render result.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableShadows() {#getEnableShadows--}
```
public boolean getEnableShadows()
```


Получает, следует ли рендерить тени.

**Returns:**
boolean - следует ли рендерить тени.
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
### setAssetDirectories(ArrayList<String> value) {#setAssetDirectories-java.util.ArrayList-java.lang.String--}
```
public void setAssetDirectories(ArrayList<String> value)
```


Каталоги, в которых хранятся внешние ресурсы (например, текстуры)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.ArrayList<java.lang.String> | Новое значение |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Цвет фона результата рендеринга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Устанавливает, следует ли рендерить тени.

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

