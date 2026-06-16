---
title: "BindPoint"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir nesnenin özelliği üzerinde genellikle bir BindPoint oluşturulur; bazı özellik tipleri birden fazla bileşen alanı içerir (örneğin bir Vector3 alanı) ve her bileşen alanı için bir kanal üretir ve bu alanı bir veya daha fazla anahtar kare dizisi örneğine kanallar aracılığıyla bağlar."
type: docs
weight: 19
url: /tr/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

Bir [BindPoint](../../com.aspose.threed/bindpoint) genellikle bir nesnenin özelliği üzerinde oluşturulur; bazı özellik tipleri birden fazla bileşen alanı içerir (örneğin bir Vector3 alanı), [BindPoint](../../com.aspose.threed/bindpoint) her bileşen alanı için bir kanal oluşturur ve bu alanı bir veya daha fazla anahtar kare dizisi örneğine kanallar aracılığıyla bağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | [BindPoint](../../com.aspose.threed/bindpoint) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Belirtilen kanal özelliğini ekler. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Belirtilen kanal özelliğini ekler. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Anahtar kare dizisini belirtilen kanala bağla |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Yeni bir eğri oluşturur ve bunu eğri eşlemesinin ilk kanalına bağlar |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [get(String channelName)](#get-java.lang.String-) | Verilen adla kanalı alır |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Verilen adla kanalı alır |
| [getChannelsCount()](#getChannelsCount--) | Bu animasyon eğri eşlemesinde tanımlı özellik kanallarının toplam sayısını alır. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Belirtilen kanaldaki ilk anahtar kare dizisini alır |
| [getName()](#getName--) | Adı alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty()](#getProperty--) | CurveMapping ile ilişkili özelliği alır |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [resetChannels()](#resetChannels--) | Bu animasyon eğri eşlemesinin özellik kanallarını boşaltır. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | CurveMapping ile ilişkili özelliği alır |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [toString()](#toString--) | Nesneyi dizeye dönüştürür |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


[BindPoint](../../com.aspose.threed/bindpoint) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Animasyonu içeren sahne. |
| prop | [Property](../../com.aspose.threed/property) | Özellik. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Belirtilen kanal özelliğini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |
| type | java.lang.Class<?> | Tür. |
| değer | java.lang.Object | Değer. |

**Returns:**
boolean - true, kanal eklendiyse, aksi takdirde false.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Belirtilen kanal özelliğini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |
| değer | java.lang.Object | Değer. |

**Returns:**
boolean - true, kanal eklendiyse, aksi takdirde false.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Anahtar kare dizisini belirtilen kanala bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelName | java.lang.String | Anahtar kare dizisinin bağlanacağı kanal |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Bağlanacak anahtar kare dizisi |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Yeni bir eğri oluşturur ve bunu eğri eşlemesinin ilk kanalına bağlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Yeni dizinin adı. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Verilen adla kanalı alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelName | java.lang.String | Kanal adı |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Verilen adla kanalı alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelName | java.lang.String | Bulunacak kanal adı |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Bu animasyon eğri eşlemesinde tanımlı özellik kanallarının toplam sayısını alır.

**Returns:**
int - Kanal sayısı.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


Belirtilen kanaldaki ilk anahtar kare dizisini alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelName | java.lang.String | Bulunacak kanal adı |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


CurveMapping ile ilişkili özelliği alır

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Bu animasyon eğri eşlemesinin özellik kanallarını boşaltır.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


CurveMapping ile ilişkili özelliği alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Yeni değer |

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

