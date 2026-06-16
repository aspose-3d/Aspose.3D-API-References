---
title: "AnimationNode"
second_title: "Aspose.3D for Java API Referansı"
description: "Aspose.3Ds animasyon hiyerarşisini destekler; her animasyon birkaç animasyon ve animasyonun anahtar çerçeve tanımıyla oluşturulabilir."
type: docs
weight: 15
url: /tr/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D animasyon hiyerarşisini destekler, her animasyon birkaç animasyon ve animasyonun anahtar çerçeve tanımıyla oluşturulabilir. [AnimationNode](../../com.aspose.threed/animationnode) bir özellik değerinin zaman içindeki dönüşümünü tanımlar; örneğin, animasyon düğümü bir düğümün dönüşümünü veya diğer [A3DObject](../../com.aspose.threed/a3dobject) nesnesinin sayısal özelliklerini kontrol etmek için kullanılabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Yeni bir [AnimationNode](../../com.aspose.threed/animationnode) sınıfı örneği başlatır. |
| [AnimationNode()](#AnimationNode--) | Yeni bir [AnimationNode](../../com.aspose.threed/animationnode) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Özellik veri tipine göre bir BindPoint oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Hedef ve ada göre bağ noktasını bulur. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Verilen özellik üzerindeki animasyon bağ noktasını alır. |
| [getBindPoints()](#getBindPoints--) | Mevcut özellik bağ noktalarını alır |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Verilen özellik üzerindeki anahtar çerçeve dizisini alır |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Belirtilen özellik ve kanal üzerindeki anahtar kare dizisini alır. |
| [getName()](#getName--) | Adı alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getSubAnimations()](#getSubAnimations--) | Mevcut animasyonların altındaki alt animasyon düğümlerini alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Yeni bir [AnimationNode](../../com.aspose.threed/animationnode) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Yeni bir [AnimationNode](../../com.aspose.threed/animationnode) sınıfı örneği başlatır.

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Özellik veri tipine göre bir BindPoint oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Nesne. |
| propName | java.lang.String | Özellik adı. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Hedef ve ada göre bağ noktasını bulur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Bulunacak bağ noktasının hedefi. |
| ad | java.lang.String | Bulunacak bağ noktasının adı. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Verilen özellik üzerindeki animasyon bağ noktasını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Bağ noktasının oluşturulacağı nesne. |
| propName | java.lang.String | Özelliğin adı. |
| oluştur | boolean | Eğer  true  olarak ayarlanırsa, bağ noktası mevcut değilse oluştur. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Mevcut özellik bağ noktalarını alır

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - mevcut özellik bağ noktaları
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


Verilen özellik üzerindeki anahtar çerçeve dizisini alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Anahtar kare dizisinin oluşturulacağı örnek. |
| propName | java.lang.String | Özelliğin adı. |
| oluştur | boolean | Eğer  true  olarak ayarlanırsa, dizi mevcut değilse oluştur. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Belirtilen özellik ve kanal üzerindeki anahtar kare dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Anahtar kare dizisinin oluşturulacağı örnek. |
| propName | java.lang.String | Özelliğin adı. |
| channelName | java.lang.String | Kanal adı. |
| oluştur | boolean | Eğer  true  olarak ayarlanırsa, animasyon dizisi mevcut değilse oluştur. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Mevcut animasyonların altındaki alt animasyon düğümlerini alır

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - mevcut animasyonların altındaki alt animasyon düğümleri
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

