---
title: "TextureBase"
second_title: "Aspose.3D for Java API Referansı"
description: "Tüm somut dokular için temel sınıf."
type: docs
weight: 185
url: /tr/java/com.aspose.threed/texturebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureBase extends A3DObject
```

Tüm somut dokular için temel sınıf. Texture, bir geometri yüzeyinin görünüm ve hissini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextureBase(String name)](#TextureBase-java.lang.String-) | Yeni bir [TextureBase](../../com.aspose.threed/texturebase) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getAlpha()](#getAlpha--) | Doku için varsayılan alfa değerini alır. Bu, [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) olduğunda geçerlidir. Varsayılan değer 1.0'dır, geçerli değer aralığı 0 ile 1 arasındadır. |
| [getAlphaSource()](#getAlphaSource--) | Doku alfa kanalını tanımlayıp tanımlamadığını alır. |
| [getClass()](#getClass--) |  |
| [getMagFilter()](#getMagFilter--) | Büyütme için filtreyi alır. |
| [getMinFilter()](#getMinFilter--) | Küçültme için filtreyi alır. |
| [getMipFilter()](#getMipFilter--) | Mipmap seviyesi örneklemesi için filtreyi alır. |
| [getName()](#getName--) | Adı alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getUVRotation()](#getUVRotation--) | Doku dönüşünü alır. |
| [getUVScale()](#getUVScale--) | UV ölçeğini alır. |
| [getUVTranslation()](#getUVTranslation--) | UV çevirisini alır. |
| [getWrapModeU()](#getWrapModeU--) | U eksenindeki doku sarma modlarını alır. |
| [getWrapModeV()](#getWrapModeV--) | V eksenindeki doku sarma modlarını alır. |
| [getWrapModeW()](#getWrapModeW--) | W eksenindeki doku sarma modlarını alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setAlpha(double value)](#setAlpha-double-) | Doku için varsayılan alfa değerini ayarlar. Bu, [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) olduğunda geçerlidir. Varsayılan değer 1.0'dır, geçerli değer aralığı 0 ile 1 arasındadır. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Doku'nun alfa kanalını tanımlayıp tanımlamadığını ayarlar. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Büyütme filtresini ayarlar. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Küçültme filtresini ayarlar. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Mipmap seviyesi örneklemesi için filtreyi ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRotation(double u, double v)](#setRotation-double-double-) | UV dönüşünü ayarlar. |
| [setScale(double u, double v)](#setScale-double-double-) | UV ölçeğini ayarlar. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | UV çevirimini ayarlar. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Dokunun dönüşünü ayarlar. |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | UV ölçeğini ayarlar. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | UV çevirimini ayarlar. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | U eksenindeki doku sarma modlarını ayarlar. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | V eksenindeki doku sarma modlarını ayarlar. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | W eksenindeki doku sarma modlarını ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBase(String name) {#TextureBase-java.lang.String-}
```
public TextureBase(String name)
```


Yeni bir [TextureBase](../../com.aspose.threed/texturebase) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

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
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Doku için varsayılan alfa değerini alır. Bu, [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) olduğunda geçerlidir. Varsayılan değer 1.0'dır, geçerli değer aralığı 0 ile 1 arasındadır.

**Returns:**
double - dokunun varsayılan alfa değeri. Bu, [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) olduğunda geçerlidir. Varsayılan değer 1.0, geçerli değer aralığı 0 ile 1 arasındadır.
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Dokunun alfa kanalını tanımlayıp tanımlamadığını alır. Varsayılan değer [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

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


Büyütme için filtreyi alır.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Küçültme için filtreyi alır.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Mipmap seviyesi örneklemesi için filtreyi alır.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
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
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Doku dönüşünü alır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


UV ölçeğini alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


UV çevirisini alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


U eksenindeki doku sarma modlarını alır.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


V eksenindeki doku sarma modlarını alır.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


W eksenindeki doku sarma modlarını alır.

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
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Doku için varsayılan alfa değerini ayarlar. Bu, [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) olduğunda geçerlidir. Varsayılan değer 1.0'dır, geçerli değer aralığı 0 ile 1 arasındadır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Dokunun alfa kanalını tanımlayıp tanımlamadığını ayarlar. Varsayılan değer [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Yeni değer |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Büyütme filtresini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Yeni değer |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Küçültme filtresini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Yeni değer |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Mipmap seviyesi örneklemesi için filtreyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Yeni değer |

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

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


UV dönüşünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


UV ölçeğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


UV çevirimini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Dokunun dönüşünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


UV ölçeğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


UV çevirimini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


U eksenindeki doku sarma modlarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Yeni değer |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


V eksenindeki doku sarma modlarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Yeni değer |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


W eksenindeki doku sarma modlarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Yeni değer |

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

