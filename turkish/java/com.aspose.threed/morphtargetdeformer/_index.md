---
title: "MorphTargetDeformer"
second_title: "Aspose.3D for Java API Referansı"
description: "MorphTargetDeformer, köşe başına animasyon sağlar."
type: docs
weight: 108
url: /tr/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer, vertex başına animasyon sağlar. MorphTargetDeformer, tüm hedefleri [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) aracılığıyla düzenler, her kanal birden fazla hedefi düzenleyebilir. Morph hedef deformer'ının yaygın bir kullanımı, bir karaktere yüz ifadesi uygulamaktır. Daha fazla ayrıntı https://en.wikipedia.org/wiki/Morph\\_target\\_animation adresinde bulunabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | Yeni bir [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) sınıfı örneği başlatır. |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | Yeni bir [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Verilen geometri için ağırlığı alır, bu kanal erişmeden hedefin ağırlığını değiştirmek için kısa bir yoldur. |
| [getChannels()](#getChannels--) | Bu deformer içinde bulunan tüm kanalları alır |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Adı alır. |
| [getOwner()](#getOwner--) | Bu deformeri sahip olan geometriyi alır |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Verilen geometri için ağırlığı ayarlar, bu kanal erişmeden hedefin ağırlığını değiştirmek için kısa bir yoldur. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


Yeni bir [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


Yeni bir [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) sınıfı örneği başlatır.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Verilen geometri için ağırlığı alır, bu kanal erişmeden hedefin ağırlığını değiştirmek için kısa bir yoldur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Hedef geometri |

**Returns:**
double - Ağırlık
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


Bu deformer içinde bulunan tüm kanalları alır

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - bu deforme edicide bulunan tüm kanallar
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
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


Bu deformeri sahip olan geometriyi alır

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Verilen geometri için ağırlığı ayarlar, bu kanal erişmeden hedefin ağırlığını değiştirmek için kısa bir yoldur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Hedef geometri |
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

