---
title: TextureBase
second_title: Справочник API Aspose.3D для Java
description: Базовый класс для всех конкретных текстур.
type: docs
weight: 185
url: /ru/java/com.aspose.threed/texturebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureBase extends A3DObject
```

Базовый класс для всех конкретных текстур. Texture определяет внешний вид поверхности геометрии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextureBase(String name)](#TextureBase-java.lang.String-) | Инициализирует новый экземпляр класса [TextureBase](../../com.aspose.threed/texturebase). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getAlpha()](#getAlpha--) | Получает значение альфа по умолчанию для текстуры. Это применимо, когда [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) равно [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Значение по умолчанию — 1.0, допустимый диапазон — от 0 до 1. |
| [getAlphaSource()](#getAlphaSource--) | Получает, определяет ли текстура альфа‑канал. |
| [getClass()](#getClass--) |  |
| [getMagFilter()](#getMagFilter--) | Получает фильтр увеличения. |
| [getMinFilter()](#getMinFilter--) | Получает фильтр уменьшения. |
| [getMipFilter()](#getMipFilter--) | Получает фильтр выборки уровня mip. |
| [getName()](#getName--) | Получает имя. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getUVRotation()](#getUVRotation--) | Получает вращение текстуры. |
| [getUVScale()](#getUVScale--) | Получает масштаб UV. |
| [getUVTranslation()](#getUVTranslation--) | Получает трансляцию UV. |
| [getWrapModeU()](#getWrapModeU--) | Получает режимы обёртывания текстуры по оси U. |
| [getWrapModeV()](#getWrapModeV--) | Получает режимы обёртывания текстуры по оси V. |
| [getWrapModeW()](#getWrapModeW--) | Получает режимы обёртывания текстуры по оси W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setAlpha(double value)](#setAlpha-double-) | Устанавливает значение альфа по умолчанию для текстуры. Это применимо, когда [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) равно [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Значение по умолчанию — 1.0, допустимый диапазон — от 0 до 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Устанавливает, определяет ли текстура альфа‑канал. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Устанавливает фильтр для увеличения. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Устанавливает фильтр для уменьшения. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Устанавливает фильтр для выборки уровней mip. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setRotation(double u, double v)](#setRotation-double-double-) | Устанавливает вращение UV. |
| [setScale(double u, double v)](#setScale-double-double-) | Устанавливает масштаб UV. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | Устанавливает трансляцию UV. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Устанавливает вращение текстуры |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | Устанавливает масштаб UV. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | Устанавливает трансляцию UV. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | Устанавливает режимы обёртывания текстуры по U. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | Устанавливает режимы обёртывания текстуры по V. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | Устанавливает режимы обёртывания текстуры по W. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBase(String name) {#TextureBase-java.lang.String-}
```
public TextureBase(String name)
```


Инициализирует новый экземпляр класса [TextureBase](../../com.aspose.threed/texturebase).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |

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
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Получает значение альфа по умолчанию для текстуры. Это применимо, когда [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) равно [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Значение по умолчанию — 1.0, допустимый диапазон — от 0 до 1.

**Returns:**
double - значение альфа по умолчанию для текстуры. Это действительно, когда [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) равно [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Значение по умолчанию — 1.0, допустимый диапазон — от 0 до 1
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Получает, определяет ли текстура альфа‑канал. Значение по умолчанию — [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


Получает фильтр увеличения.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Получает фильтр уменьшения.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Получает фильтр выборки уровня mip.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
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
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Получает вращение текстуры.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


Получает масштаб UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


Получает трансляцию UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


Получает режимы обёртывания текстуры по оси U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


Получает режимы обёртывания текстуры по оси V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


Получает режимы обёртывания текстуры по оси W.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Устанавливает значение альфа по умолчанию для текстуры. Это применимо, когда [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) равно [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Значение по умолчанию — 1.0, допустимый диапазон — от 0 до 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Устанавливает, определяет ли текстура альфа‑канал. Значение по умолчанию — [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Новое значение |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Устанавливает фильтр для увеличения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Новое значение |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Устанавливает фильтр для уменьшения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Новое значение |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Устанавливает фильтр для выборки уровней mip.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Новое значение |

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

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


Устанавливает вращение UV.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


Устанавливает масштаб UV.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


Устанавливает трансляцию UV.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Устанавливает вращение текстуры

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


Устанавливает масштаб UV.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


Устанавливает трансляцию UV.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


Устанавливает режимы обёртывания текстуры по U.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Новое значение |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


Устанавливает режимы обёртывания текстуры по V.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Новое значение |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


Устанавливает режимы обёртывания текстуры по W.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Новое значение |

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

