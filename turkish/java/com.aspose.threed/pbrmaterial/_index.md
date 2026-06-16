---
title: "PbrMaterial"
second_title: "Aspose.3D for Java API Referansı"
description: "Albedo rengi/metallic/roughness temelinde fiziksel tabanlı render için malzeme."
type: docs
weight: 121
url: /tr/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Albedo rengi/metallic/roughness temelinde fiziksel tabanlı render için malzeme.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Varsayılan bir PBR malzeme örneği oluştur |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Belirtilen albedo renk değeriyle varsayılan bir PBR malzeme oluştur. |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Diğer malzemeyi PbrMaterial'e dönüştürmeye izin ver **Example:** |
| [getAlbedo()](#getAlbedo--) | Malzemenin temel rengini alır |
| [getAlbedoTexture()](#getAlbedoTexture--) | Albedo için dokuyu alır |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Emisyon rengini alır |
| [getEmissiveTexture()](#getEmissiveTexture--) | Emisyon için dokuyu alır |
| [getMetallicFactor()](#getMetallicFactor--) | Malzemenin metalikliğini alır, 1 değeri malzemenin metal olduğunu, 0 değeri ise dielektrik olduğunu gösterir. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Metallic (R kanalında) ve roughness (G kanalında) için dokuyu alır |
| [getName()](#getName--) | Adı alır. |
| [getNormalTexture()](#getNormalTexture--) | Normal haritalama dokusunu alır |
| [getOcclusionFactor()](#getOcclusionFactor--) | Ambient occlusion faktörünü alır |
| [getOcclusionTexture()](#getOcclusionTexture--) | Ambient occlusion için dokuyu alır |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRoughnessFactor()](#getRoughnessFactor--) | Malzemenin pürüzlülüğünü alır, 1 değeri malzemenin tamamen pürüzlü olduğunu, 0 değeri ise tamamen pürüzsüz olduğunu gösterir. |
| [getSpecularTexture()](#getSpecularTexture--) | Speküler renk için dokuyu alır |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Belirtilen yuvasından dokuyu alır, bu materyalin özellik adı veya gölgelendiricinin parametre adı olabilir |
| [getTransparency()](#getTransparency--) | Şeffaflık faktörünü alır. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Dahili doku yuvalarını yinelemek için enumeratörü alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Malzemenin temel rengini ayarlar |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Albedo için dokuyu ayarlar |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Emisyon rengini ayarlar |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Emissive için dokuyu ayarlar |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Malzemenin metalikliğini ayarlar, 1 değeri malzemenin metal olduğunu, 0 değeri ise malzemenin dielektrik olduğunu gösterir. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Metalik (R kanalında) ve pürüzlülük (G kanalında) için dokuyu ayarlar |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Normal haritalamanın dokusunu ayarlar |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Ambient occlusion faktörünü ayarlar |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Ambient occlusion için dokuyu ayarlar |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Malzemenin pürüzlülüğünü ayarlar, 1 değeri malzemenin tamamen pürüzlü olduğunu, 0 değeri ise tamamen pürüzsüz olduğunu gösterir. |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Speküler renk için dokuyu ayarlar |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Dokuyu belirtilen yuvaya ayarlar |
| [setTransparency(double value)](#setTransparency-double-) | Şeffaflık faktörünü ayarlar. |
| [toString()](#toString--) | Nesneyi dizeye dönüştürür |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Varsayılan bir PBR malzeme örneği oluştur

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Belirtilen albedo renk değeriyle varsayılan bir PBR malzeme oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | Varsayılan albedo renk değeri |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Diğer malzemeyi PbrMaterial'e dönüştürmeye izin ver **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Malzemenin temel rengini alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Albedo için dokuyu alır

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


Emisyon rengini alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Emisyon için dokuyu alır

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Malzemenin metalikliğini alır, 1 değeri malzemenin metal olduğunu, 0 değeri ise dielektrik olduğunu gösterir.

**Returns:**
double - malzemenin metalikliğini, 1 değeri malzemenin metal olduğunu, 0 değeri ise malzemenin dielektrik olduğunu gösterir.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Metallic (R kanalında) ve roughness (G kanalında) için dokuyu alır

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Ambient occlusion faktörünü alır

**Returns:**
double - ambient occlusion faktörü
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Ambient occlusion için dokuyu alır

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Malzemenin pürüzlülüğünü alır, 1 değeri malzemenin tamamen pürüzlü olduğunu, 0 değeri ise tamamen pürüzsüz olduğunu gösterir.

**Returns:**
double - malzemenin pürüzlülüğü, 1 değeri malzemenin tamamen pürüzlü olduğunu, 0 değeri ise tamamen pürüzsüz olduğunu gösterir.
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Speküler renk için dokuyu alır

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Malzemenin temel rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Albedo için dokuyu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Yeni değer |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Emisyon rengini ayarlar

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Malzemenin metalikliğini ayarlar, 1 değeri malzemenin metal olduğunu, 0 değeri ise malzemenin dielektrik olduğunu gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Metalik (R kanalında) ve pürüzlülük (G kanalında) için dokuyu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Yeni değer |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Ambient occlusion faktörünü ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Ambient occlusion için dokuyu ayarlar

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Malzemenin pürüzlülüğünü ayarlar, 1 değeri malzemenin tamamen pürüzlü olduğunu, 0 değeri ise tamamen pürüzsüz olduğunu gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Speküler renk için dokuyu ayarlar

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

