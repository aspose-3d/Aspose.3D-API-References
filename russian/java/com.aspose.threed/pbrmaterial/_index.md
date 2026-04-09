---
title: PbrMaterial
second_title: Справочник API Aspose.3D для Java
description: Материал для физически основанного рендеринга, основанный на альбедо‑цвете/металличности/шероховатости
type: docs
weight: 121
url: /ru/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Материал для физически основанного рендеринга, основанный на альбедо‑цвете/металличности/шероховатости
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Создать экземпляр материала PBR по умолчанию |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Создать материал PBR по умолчанию с указанным значением цвета альбедо. |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Разрешить преобразовать другой материал в PbrMaterial **Example:** |
| [getAlbedo()](#getAlbedo--) | Получает базовый цвет материала |
| [getAlbedoTexture()](#getAlbedoTexture--) | Получает текстуру альбедо |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Получает излучающий цвет |
| [getEmissiveTexture()](#getEmissiveTexture--) | Получает текстуру для эмиссивного цвета |
| [getMetallicFactor()](#getMetallicFactor--) | Получает степень металлическости материала, значение 1 означает, что материал является металлом, а значение 0 — диэлектриком. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Получает текстуру металлическости (в канале R) и шероховатости (в канале G) |
| [getName()](#getName--) | Получает имя. |
| [getNormalTexture()](#getNormalTexture--) | Получает текстуру нормального отображения |
| [getOcclusionFactor()](#getOcclusionFactor--) | Получает коэффициент окклюзии окружающей среды |
| [getOcclusionTexture()](#getOcclusionTexture--) | Получает текстуру окклюзии окружающей среды |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getRoughnessFactor()](#getRoughnessFactor--) | Получает степень шероховатости материала, значение 1 означает, что материал полностью шероховат, а значение 0 — полностью гладок. |
| [getSpecularTexture()](#getSpecularTexture--) | Получает текстуру спекулярного цвета |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Получает текстуру из указанного слота, это может быть имя свойства материала или имя параметра шейдера |
| [getTransparency()](#getTransparency--) | Получает коэффициент прозрачности. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Получает перечислитель для перебора внутренних слотов текстур. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Устанавливает базовый цвет материала |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру для альбедо |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Устанавливает излучающий цвет |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру для эмиссии |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Устанавливает металлическость материала, значение 1 означает, что материал является металлом, а значение 0 означает, что материал является диэлектриком. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Устанавливает текстуру для metallic (в канале R) и roughness (в канале G) |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру нормального отображения |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Устанавливает коэффициент ambient occlusion |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру для ambient occlusion |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Устанавливает шероховатость материала, значение 1 означает, что материал полностью шероховат, а значение 0 означает, что материал полностью гладок. |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Устанавливает текстуру для specular color |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Устанавливает текстуру в указанный слот |
| [setTransparency(double value)](#setTransparency-double-) | Устанавливает коэффициент прозрачности. |
| [toString()](#toString--) | Форматирует объект в строку |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Создать экземпляр материала PBR по умолчанию

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Создать материал PBR по умолчанию с указанным значением цвета альбедо.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | Значение цвета альбедо по умолчанию |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Разрешить преобразовать другой материал в PbrMaterial **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Получает базовый цвет материала

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Получает текстуру альбедо

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for albedo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Получает излучающий цвет

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Получает текстуру для эмиссивного цвета

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Получает степень металлическости материала, значение 1 означает, что материал является металлом, а значение 0 — диэлектриком.

**Returns:**
double — металлическость материала, значение 1 означает, что материал является металлом, а значение 0 означает, что материал является диэлектриком.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Получает текстуру металлическости (в канале R) и шероховатости (в канале G)

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Получает коэффициент окклюзии окружающей среды

**Returns:**
double — коэффициент ambient occlusion
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Получает текстуру окклюзии окружающей среды

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Получает степень шероховатости материала, значение 1 означает, что материал полностью шероховат, а значение 0 — полностью гладок.

**Returns:**
double — шероховатость материала, значение 1 означает, что материал полностью шероховат, а значение 0 означает, что материал полностью гладок.
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Получает текстуру спекулярного цвета

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Устанавливает базовый цвет материала

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Устанавливает текстуру для альбедо

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Новое значение |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Устанавливает излучающий цвет

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Устанавливает металлическость материала, значение 1 означает, что материал является металлом, а значение 0 означает, что материал является диэлектриком.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Устанавливает текстуру для metallic (в канале R) и roughness (в канале G)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Новое значение |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Устанавливает коэффициент ambient occlusion

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Устанавливает текстуру для ambient occlusion

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Устанавливает шероховатость материала, значение 1 означает, что материал полностью шероховат, а значение 0 означает, что материал полностью гладок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Устанавливает текстуру для specular color

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

