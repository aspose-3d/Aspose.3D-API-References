---
title: "AnimationChannel"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir kanal, özelliğin bileşen alanını bir dizi anahtar kare sekansına eşler."
type: docs
weight: 13
url: /tr/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

Bir kanal, özelliğin bileşen alanını bir dizi anahtar kare sekansına eşler
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Belirtilen değerle yeni bir anahtar kare oluştur. |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Belirtilen değerle yeni bir anahtar kare oluştur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBindPoint()](#getBindPoint--) | Bu eğriyi sahip olan özellik bağlama noktasını alır. |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | Bileşen alanının tipini alır. |
| [getDefaultValue()](#getDefaultValue--) | Kanalın varsayılan değerini alır. |
| [getKeyFrames()](#getKeyFrames--) | Bu eğrinin anahtar karelerini alır. |
| [getKeyframeSequence()](#getKeyframeSequence--) | Bu kanal içindeki ilişkili anahtar kare sekansını alır. |
| [getName()](#getName--) | Adı alır. |
| [getPostBehavior()](#getPostBehavior--) | Post davranışını alır; bu, örneklenen değerin son anahtar kareden sonra ne olması gerektiğini gösterir. |
| [getPreBehavior()](#getPreBehavior--) | Pre davranışını alır; bu, örneklenen değerin ilk anahtardan önce ne olması gerektiğini gösterir. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Tüm anahtar kareleri dolaşmak için yineleyiciyi alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [reset()](#reset--) | Tüm anahtar kareleri kaldırır ve post/pre davranışlarını sıfırlar. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Kanalın varsayılan değerini ayarlar. |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | Bu kanal içindeki ilişkili anahtar kare sekansını alır. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Belirtilen değerle yeni bir anahtar kare oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| zaman | double | Zaman konumu (saniye cinsinden ölçülür) |
| değer | float | Bu zaman konumundaki değer |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Belirtilen değerle yeni bir anahtar kare oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| zaman | double | Zaman konumu (saniye cinsinden ölçülür) |
| değer | float | Bu zaman konumundaki değer |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | Bu anahtar karenin ara değerleme türü |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Bu eğriyi sahip olan özellik bağlama noktasını alır.

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


Bileşen alanının tipini alır.

**Returns:**
java.lang.Class<?> - bileşen alanının tipi
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


Kanalın varsayılan değerini alır. Bir kanalın bağlı anahtar kare sekansı yoksa, varsayılan değer animasyon değerlendirmesi sırasında kullanılacaktır. Gerçek bir senaryo: Animasyon yalnızca bir düğümün x koordinatını animasyon eder, y ve z değişmez, bu durumda tam çeviri değerlendirmesi sırasında varsayılan değer kullanılacaktır.

**Returns:**
java.lang.Object - kanalın varsayılan değeri. Bir kanalın bağlı anahtar kare sekansı yoksa, varsayılan değer animasyon değerlendirmesi sırasında kullanılacaktır. Gerçek bir senaryo: Animasyon yalnızca bir düğümün x koordinatını animasyon eder, y ve z değişmez, bu durumda tam çeviri değerlendirmesi sırasında varsayılan değer kullanılacaktır.
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Bu eğrinin anahtar karelerini alır.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - bu eğrinin anahtar kareleri.
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


Bu kanal içindeki ilişkili anahtar kare sekansını alır.

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Post davranışını alır; bu, örneklenen değerin son anahtar kareden sonra ne olması gerektiğini gösterir.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Pre davranışını alır; bu, örneklenen değerin ilk anahtardan önce ne olması gerektiğini gösterir.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


Tüm anahtar kareleri dolaşmak için yineleyiciyi alır.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


Tüm anahtar kareleri kaldırır ve post/pre davranışlarını sıfırlar.

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


Kanalın varsayılan değerini ayarlar. Bir kanalın bağlı anahtar kare sekansı yoksa, varsayılan değer animasyon değerlendirmesi sırasında kullanılacaktır. Gerçek bir senaryo: Animasyon yalnızca bir düğümün x koordinatını animasyon eder, y ve z değişmez, bu durumda tam çeviri değerlendirmesi sırasında varsayılan değer kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | Yeni değer |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


Bu kanal içindeki ilişkili anahtar kare sekansını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Yeni değer |

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

