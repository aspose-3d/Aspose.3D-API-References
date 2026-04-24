---
title: PbrSpecularMaterial
second_title: Справочник API Aspose.3D для Java
description: Материал для физически основанного рендеринга, основанный на диффузном цвете/спекулярности/блеске
type: docs
weight: 122
url: /ru/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Материал для физически основанного рендеринга, основанный на диффузном цвете/спекулярности/блеске
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | Конструктор класса [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## Поля

| Поле | Описание |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения окружающего текстурного отображения. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения диффузного текстурного отображения. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения излучающего текстурного отображения. |
| [MAP_NORMAL](#MAP-NORMAL) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения нормального текстурного отображения. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Используется в [setTexture](../../com.aspose.threed/material\#setTexture) для назначения зеркального текстурного отображения. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | Текстурная карта для спекулярного блеска |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Получает диффузный цвет материала, значение по умолчанию — (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | Получает текстуру для диффузного цвета |
| [getEmissiveColor()](#getEmissiveColor--) | Получает эмиссивный цвет, значение по умолчанию — (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | Получает текстуру для эмиссивного цвета |
| [getGlossinessFactor()](#getGlossinessFactor--) | Получает степень блеска (гладкости) материала, 1 означает идеально гладкий, а 0 — идеально шероховатый, значение по умолчанию — 1, диапазон — [0, 1] |
| [getName()](#getName--) | Получает имя. |
| [getNormalTexture()](#getNormalTexture--) | Получает текстуру нормального отображения |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getSpecular()](#getSpecular--) | Получает спекулярный цвет материала, значение по умолчанию — (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Получает текстуру для спекулярного цвета, канал RGB хранит спекулярный цвет, а канал A — блеск. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Получает текстуру из указанного слота, это может быть имя свойства материала или имя параметра шейдера |
| [getTransparency()](#getTransparency--) | Получает коэффициент прозрачности. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Получает перечислитель для перебора внутренних слотов текстур. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Устанавливает диффузный цвет материала, значение по умолчанию — (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру для диффузного цвета |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Устанавливает эмиссивный цвет, значение по умолчанию — (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру для эмиссии |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Устанавливает блеск (гладкость) материала, 1 означает идеально гладкий, а 0 — идеально шероховатый, значение по умолчанию — 1, диапазон [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру нормального отображения |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Устанавливает зеркальный цвет материала, значение по умолчанию — (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру для зеркального цвета, канал RGB хранит зеркальный цвет, а канал A — блеск. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Устанавливает текстуру в указанный слот |
| [setTransparency(double value)](#setTransparency-double-) | Устанавливает коэффициент прозрачности. |
| [toString()](#toString--) | Форматирует объект в строку |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


Конструктор класса [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


Текстурная карта для спекулярного блеска

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


Получает диффузный цвет материала, значение по умолчанию — (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Получает текстуру для диффузного цвета

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Получает эмиссивный цвет, значение по умолчанию — (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Получает текстуру для эмиссивного цвета

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Получает степень блеска (гладкости) материала, 1 означает идеально гладкий, а 0 — идеально шероховатый, значение по умолчанию — 1, диапазон — [0, 1]

**Returns:**
double — блеск (гладкость) материала, 1 означает идеально гладкий, а 0 — идеально шероховатый, значение по умолчанию — 1, диапазон [0, 1]
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Получает текстуру нормального отображения

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Получает спекулярный цвет материала, значение по умолчанию — (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Получает текстуру для спекулярного цвета, канал RGB хранит спекулярный цвет, а канал A — блеск.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Устанавливает диффузный цвет материала, значение по умолчанию — (1, 1, 1)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Устанавливает текстуру для диффузного цвета

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Новое значение |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Устанавливает эмиссивный цвет, значение по умолчанию — (0, 0, 0)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Устанавливает текстуру для эмиссии

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Новое значение |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Устанавливает блеск (гладкость) материала, 1 означает идеально гладкий, а 0 — идеально шероховатый, значение по умолчанию — 1, диапазон [0, 1]

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

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Устанавливает текстуру нормального отображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Новое значение |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Устанавливает зеркальный цвет материала, значение по умолчанию — (1, 1, 1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Устанавливает текстуру для зеркального цвета, канал RGB хранит зеркальный цвет, а канал A — блеск.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Новое значение |

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

