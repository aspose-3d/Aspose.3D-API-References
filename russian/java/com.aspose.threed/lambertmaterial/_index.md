---
title: LambertMaterial
second_title: Справочник API Aspose.3D для Java
description: Материал для модели ламбертового затенения
type: docs
weight: 92
url: /ru/java/com.aspose.threed/lambertmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class LambertMaterial extends Material
```

Материал для модели ламбертового затенения
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LambertMaterial()](#LambertMaterial--) | Инициализирует новый экземпляр класса [LambertMaterial](../../com.aspose.threed/lambertmaterial). |
| [LambertMaterial(String name)](#LambertMaterial-java.lang.String-) | Инициализирует новый экземпляр класса [LambertMaterial](../../com.aspose.threed/lambertmaterial). |
## Поля

| Поле | Описание |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения окружающего текстурного отображения. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения диффузного текстурного отображения. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения излучающего текстурного отображения. |
| [MAP_NORMAL](#MAP-NORMAL) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения нормального текстурного отображения. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения зеркального текстурного отображения. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getAmbientColor()](#getAmbientColor--) | Получает окружающий цвет |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Получает диффузный цвет |
| [getEmissiveColor()](#getEmissiveColor--) | Получает излучающий цвет |
| [getName()](#getName--) | Получает имя. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Получает текстуру из указанного слота, это может быть имя свойства материала или имя параметра шейдера |
| [getTransparency()](#getTransparency--) | Получает коэффициент прозрачности. |
| [getTransparentColor()](#getTransparentColor--) | Получает прозрачный цвет. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Получает перечислитель для перебора внутренних слотов текстур. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Устанавливает окружающий цвет |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Устанавливает диффузный цвет |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Устанавливает излучающий цвет |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Устанавливает текстуру в указанный слот |
| [setTransparency(double value)](#setTransparency-double-) | Устанавливает коэффициент прозрачности. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Устанавливает прозрачный цвет. |
| [toString()](#toString--) | Форматирует объект в строку |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LambertMaterial() {#LambertMaterial--}
```
public LambertMaterial()
```


Инициализирует новый экземпляр класса [LambertMaterial](../../com.aspose.threed/lambertmaterial).

### LambertMaterial(String name) {#LambertMaterial-java.lang.String-}
```
public LambertMaterial(String name)
```


Инициализирует новый экземпляр класса [LambertMaterial](../../com.aspose.threed/lambertmaterial).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения окружающего текстурного отображения.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения диффузного текстурного отображения.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения излучающего текстурного отображения.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения нормального текстурного отображения.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения зеркального текстурного отображения.

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Получает окружающий цвет

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the ambient color
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuseColor() {#getDiffuseColor--}
```
public Vector3 getDiffuseColor()
```


Получает диффузный цвет

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Получает излучающий цвет

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color **Example:**

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
```
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
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Получает текстуру из указанного слота, это может быть имя свойства материала или имя параметра шейдера

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slotName | java.lang.String | Имя слота. |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Получает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачный) до 1 (100 %, полностью прозрачный). Любое недопустимое значение коэффициента будет ограничено.

**Returns:**
double — коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачный) до 1 (100 %, полностью прозрачный). Любое недопустимое значение коэффициента будет ограничено.
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Получает прозрачный цвет.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the transparent color.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


Получает перечислитель для перебора внутренних слотов текстур.

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Устанавливает окружающий цвет

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Устанавливает диффузный цвет

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Устанавливает излучающий цвет

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Новое значение **Пример:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

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

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Устанавливает текстуру в указанный слот

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slotName | java.lang.String | Имя слота. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Текстура. **Пример:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Устанавливает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачный) до 1 (100 %, полностью прозрачный). Любое недопустимое значение коэффициента будет ограничено.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Устанавливает прозрачный цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

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

