---
title: "Material"
second_title: "Aspose.3D for Java API Referansı"
description: "Malzeme, geometrinin görsel görünümü için gerekli parametreleri tanımlar."
type: docs
weight: 98
url: /tr/java/com.aspose.threed/material/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class Material extends A3DObject implements Iterable<TextureSlot>
```

Material, geometrinin görsel görünümü için gerekli parametreleri tanımlar. Aspose.3D, [LambertMaterial](../../com.aspose.threed/lambertmaterial), [PhongMaterial](../../com.aspose.threed/phongmaterial) ve [ShaderMaterial](../../com.aspose.threed/shadermaterial) **Örnek:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     for(var slot : mat)
     {
         System.out.printf("Texture slot %s = %s", slot.getSlotName(), slot.getTexture());
     }
```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Ortam doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Difüz doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Emisyon doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_NORMAL](#MAP-NORMAL) | Normal doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Yansıtıcı doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Adı alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Belirtilen yuvasından dokuyu alır, bu materyalin özellik adı veya gölgelendiricinin parametre adı olabilir |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Dahili doku yuvalarını yinelemek için enumeratörü alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Dokuyu belirtilen yuvaya ayarlar |
| [toString()](#toString--) | Nesneyi dizeye dönüştürür |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Ortam doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Difüz doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Emisyon doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Normal doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Yansıtıcı doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty) veya native property(Identified by its name) olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyName | java.lang.String | Özellik adı. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
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


Adı alır.

**Returns:**
java.lang.String - ad.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Tüm özelliklerin koleksiyonunu alır.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Belirtilen özelliğin değerini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |

**Returns:**
java.lang.Object - Bulunan özelliğin değeri
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Belirtilen yuvasından dokuyu alır, bu materyalin özellik adı veya gölgelendiricinin parametre adı olabilir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slotName | java.lang.String | Slot adı. |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
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


Dahili doku yuvalarını yinelemek için enumeratörü alır.

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


Dinamik bir özelliği kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


İsimle tanımlanan belirtilen özelliği kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Belirtilen özelliğin değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |
| değer | java.lang.Object | Özelliğin değeri |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Dokuyu belirtilen yuvaya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slotName | java.lang.String | Slot adı. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Doku. **Örnek:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### toString() {#toString--}
```
public String toString()
```


Nesneyi dizeye dönüştürür

**Returns:**
java.lang.String - Nesne dizesi
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

