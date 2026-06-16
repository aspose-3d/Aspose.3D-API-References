---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D for Java API Referansı"
description: "Diffuse renk/specular/glossiness temelinde fiziksel tabanlı render için malzeme."
type: docs
weight: 122
url: /tr/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Diffuse renk/specular/glossiness temelinde fiziksel tabanlı render için malzeme.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Ortam doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Difüz doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Emisyon doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_NORMAL](#MAP-NORMAL) | Normal doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Yansıtıcı doku eşlemesi atamak için [setTexture](../../com.aspose.threed/material\#setTexture) içinde kullanılır. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | Speküler parlaklık için doku haritası |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Malzemenin difüz rengini alır, varsayılan değer (1, 1, 1)'dir |
| [getDiffuseTexture()](#getDiffuseTexture--) | Difüz için dokuyu alır |
| [getEmissiveColor()](#getEmissiveColor--) | Emisyon rengini alır, varsayılan değer (0, 0, 0)'dır |
| [getEmissiveTexture()](#getEmissiveTexture--) | Emisyon için dokuyu alır |
| [getGlossinessFactor()](#getGlossinessFactor--) | Malzemenin parlaklığını (pürüzsüzlüğünü) alır, 1 tamamen pürüzsüz, 0 tamamen pürüzlü anlamına gelir, varsayılan değer 1, aralık [0, 1]'dir |
| [getName()](#getName--) | Adı alır. |
| [getNormalTexture()](#getNormalTexture--) | Normal haritalama dokusunu alır |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getSpecular()](#getSpecular--) | Malzemenin speküler rengini alır, varsayılan değer (1, 1, 1)'dir. |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Speküler renk için dokuyu alır, RGB kanalı speküler rengi, A kanalı ise parlaklığı depolar. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Belirtilen yuvasından dokuyu alır, bu materyalin özellik adı veya gölgelendiricinin parametre adı olabilir |
| [getTransparency()](#getTransparency--) | Şeffaflık faktörünü alır. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Dahili doku yuvalarını yinelemek için enumeratörü alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Malzemenin difüz rengini ayarlar, varsayılan değer (1, 1, 1)'dir |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Difüz için dokuyu ayarlar |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Emisyon rengini ayarlar, varsayılan değer (0, 0, 0)'dır |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Emissive için dokuyu ayarlar |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Malzemenin parlaklığını (pürüzsüzlüğünü) ayarlar, 1 tamamen pürüzsüz, 0 tamamen pürüzlü anlamına gelir, varsayılan değer 1'dir, aralık [0, 1]'dir |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Normal haritalamanın dokusunu ayarlar |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Malzemenin spekülatif rengini ayarlar, varsayılan değer (1, 1, 1)'dir. |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Spekülatif renk için dokuyu ayarlar, RGB kanalı spekülatif rengi, A kanalı ise parlaklığı depolar. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Dokuyu belirtilen yuvaya ayarlar |
| [setTransparency(double value)](#setTransparency-double-) | Şeffaflık faktörünü ayarlar. |
| [toString()](#toString--) | Nesneyi dizeye dönüştürür |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


[PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) yapıcısı

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


Speküler parlaklık için doku haritası

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
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


Malzemenin difüz rengini alır, varsayılan değer (1, 1, 1)'dir

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Difüz için dokuyu alır

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Emisyon rengini alır, varsayılan değer (0, 0, 0)'dır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Emisyon için dokuyu alır

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Malzemenin parlaklığını (pürüzsüzlüğünü) alır, 1 tamamen pürüzsüz, 0 tamamen pürüzlü anlamına gelir, varsayılan değer 1, aralık [0, 1]'dir

**Returns:**
double - malzemenin parlaklığı (pürüzsüzlüğü), 1 tamamen pürüzsüz, 0 tamamen pürüzlü anlamına gelir, varsayılan değer 1, aralık [0, 1]
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Normal haritalama dokusunu alır

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Malzemenin speküler rengini alır, varsayılan değer (1, 1, 1)'dir.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Speküler renk için dokuyu alır, RGB kanalı speküler rengi, A kanalı ise parlaklığı depolar.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Malzemenin difüz rengini ayarlar, varsayılan değer (1, 1, 1)'dir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Difüz için dokuyu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Yeni değer |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Emisyon rengini ayarlar, varsayılan değer (0, 0, 0)'dır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Emissive için dokuyu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Yeni değer |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Malzemenin parlaklığını (pürüzsüzlüğünü) ayarlar, 1 tamamen pürüzsüz, 0 tamamen pürüzlü anlamına gelir, varsayılan değer 1'dir, aralık [0, 1]'dir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Normal haritalamanın dokusunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Yeni değer |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Malzemenin spekülatif rengini ayarlar, varsayılan değer (1, 1, 1)'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Spekülatif renk için dokuyu ayarlar, RGB kanalı spekülatif rengi, A kanalı ise parlaklığı depolar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Yeni değer |

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

