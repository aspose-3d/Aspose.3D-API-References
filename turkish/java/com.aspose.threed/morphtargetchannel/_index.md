---
title: "MorphTargetChannel"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir MorphTargetChannel, hedef geometrileri düzenlemek için  tarafından kullanılır."
type: docs
weight: 107
url: /tr/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

Bir MorphTargetChannel, hedef geometrileri düzenlemek için [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) tarafından kullanılır. FBX gibi bazı dosya formatları paralel olarak birden fazla kanal destekler. **Remarks:** Ağırlık 0 ile 1.0 arasındadır ve hedef için varsayılan ağırlık 0.0'dır;
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | Yeni bir [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) sınıfı örneği başlatır. |
| [MorphTargetChannel()](#MorphTargetChannel--) | Yeni bir [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | Morf hedefi için varsayılan ağırlık. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Belirtilen geometri için ağırlığı alır |
| [getChannelWeight()](#getChannelWeight--) | Bu kanalın deformasyon ağırlığını alır. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Adı alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getTargets()](#getTargets--) | Kanal ile ilişkili tüm hedefleri alır. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | Belirtilen hedef için ağırlığı alır, hedef bu kanala ait değilse, varsayılan değer 0 döndürülür. |
| [getWeights()](#getWeights--) | Hedef geometrilerin tam ağırlık değerlerini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Belirtilen geometri için ağırlığı ayarlar |
| [setChannelWeight(double value)](#setChannelWeight-double-) | Bu kanalın deformasyon ağırlığını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | Belirtilen hedef için ağırlığı ayarlar, varsayılan değer 1'dir, aralık 0~1 arasında olmalıdır. |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | Belirtilen hedef için ağırlığı ayarlar, varsayılan değer 1'dir, aralık 0~1 arasında olmalıdır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


Yeni bir [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


Yeni bir [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) sınıfı örneği başlatır.

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


Morf hedefi için varsayılan ağırlık.

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


Belirtilen geometri için ağırlığı alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Hedef geometri. |

**Returns:**
double - Ağırlık
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


Bu kanalın deformasyon ağırlığını alır. Ağırlık 0.0 ile 1.0 arasındadır.

**Returns:**
double - bu kanalın deformasyon ağırlığı. Ağırlık 0.0 ile 1.0 arasındadır.
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


Kanal ile ilişkili tüm hedefleri alır.

**Returns:**
java.util.List<com.aspose.threed.Shape> - kanal ile ilişkili tüm hedefler.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


Belirtilen hedef için ağırlığı alır, hedef bu kanala ait değilse, varsayılan değer 0 döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


Hedef geometrilerin tam ağırlık değerlerini alır.

**Returns:**
java.util.List<java.lang.Double> - hedef geometrilerin tam ağırlık değerleri.
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


Belirtilen geometri için ağırlığı ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Hedef geometri. |
| değer | double | Yeni değer |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


Bu kanalın deformasyon ağırlığını ayarlar. Ağırlık 0.0 ile 1.0 arasındadır.

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


Belirtilen hedef için ağırlığı ayarlar, varsayılan değer 1'dir, aralık 0~1 arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


Belirtilen hedef için ağırlığı ayarlar, varsayılan değer 1'dir, aralık 0~1 arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| ağırlık | double |  |

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

