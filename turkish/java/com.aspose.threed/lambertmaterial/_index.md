---
title: "LambertMaterial"
second_title: "Aspose.3D for Java API Referansı"
description: "Lambert gölgelendirme modeli için malzeme"
type: docs
weight: 92
url: /tr/java/com.aspose.threed/lambertmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class LambertMaterial extends Material
```

Lambert gölgelendirme modeli için malzeme
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LambertMaterial()](#LambertMaterial--) | Yeni bir [LambertMaterial](../../com.aspose.threed/lambertmaterial) sınıfı örneğini başlatır. |
| [LambertMaterial(String name)](#LambertMaterial-java.lang.String-) | Yeni bir [LambertMaterial](../../com.aspose.threed/lambertmaterial) sınıfı örneğini başlatır. |
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
| [getAmbientColor()](#getAmbientColor--) | Ortam rengini alır |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Difüz rengini alır |
| [getEmissiveColor()](#getEmissiveColor--) | Emisyon rengini alır |
| [getName()](#getName--) | Adı alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Belirtilen yuvasından dokuyu alır, bu materyalin özellik adı veya gölgelendiricinin parametre adı olabilir |
| [getTransparency()](#getTransparency--) | Şeffaflık faktörünü alır. |
| [getTransparentColor()](#getTransparentColor--) | Şeffaf rengi alır. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Dahili doku yuvalarını yinelemek için enumeratörü alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Ortam rengini ayarlar |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Difüz rengini ayarlar |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Emisyon rengini ayarlar |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Dokuyu belirtilen yuvaya ayarlar |
| [setTransparency(double value)](#setTransparency-double-) | Şeffaflık faktörünü ayarlar. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Şeffaf rengi ayarlar. |
| [toString()](#toString--) | Nesneyi dizeye dönüştürür |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LambertMaterial() {#LambertMaterial--}
```
public LambertMaterial()
```


Yeni bir [LambertMaterial](../../com.aspose.threed/lambertmaterial) sınıfı örneğini başlatır.

### LambertMaterial(String name) {#LambertMaterial-java.lang.String-}
```
public LambertMaterial(String name)
```


Yeni bir [LambertMaterial](../../com.aspose.threed/lambertmaterial) sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad |

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Ortam rengini alır

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


Difüz rengini alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Emisyon rengini alır

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
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Şeffaflık faktörünü alır. Faktör 0 (0%, tamamen opak) ile 1 (100%, tamamen şeffaf) arasında olmalıdır. Geçersiz faktör değeri sınırlandırılacaktır.

**Returns:**
double - şeffaflık faktörü. Faktör 0 (0%, tamamen opak) ile 1 (100%, tamamen şeffaf) arasında olmalıdır. Geçersiz faktör değeri sınırlandırılacaktır.
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Şeffaf rengi alır.

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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Ortam rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Difüz rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Emisyon rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer **Örnek:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

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

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Şeffaflık faktörünü ayarlar. Faktör 0 (0%, tamamen opak) ile 1 (100%, tamamen şeffaf) arasında olmalıdır. Geçersiz faktör değeri sınırlandırılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Şeffaf rengi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

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

