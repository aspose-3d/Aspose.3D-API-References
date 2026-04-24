---
title: MorphTargetDeformer
second_title: Aspose.3D for Java API Reference
description: MorphTargetDeformer प्रति-शिखर एनीमेशन प्रदान करता है।
type: docs
weight: 108
url: /hi/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer प्रति-शिखर एनीमेशन प्रदान करता है। MorphTargetDeformer सभी टार्गेट को [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) के माध्यम से व्यवस्थित करता है, प्रत्येक चैनल कई टार्गेट को व्यवस्थित कर सकता है। मोर्फ़ टार्गेट डिफॉर्मर का एक सामान्य उपयोग पात्र पर चेहरे के भाव लागू करना है। अधिक विवरण https://en.wikipedia.org/wiki/Morph\\_target\\_animation पर पाया जा सकता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | नया उदाहरण प्रारंभ करता है [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) क्लास का। |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | नया उदाहरण प्रारंभ करता है [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) क्लास का। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | दिए गए ज्योमेट्री के लिए वजन प्राप्त करता है, यह चैनल तक पहुँचे बिना टार्गेट के वजन को संशोधित करने का संक्षिप्त तरीका है। |
| [getChannels()](#getChannels--) | इस डिफॉर्मर में शामिल सभी चैनल प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getOwner()](#getOwner--) | उस जियोमेट्री को प्राप्त करता है जो इस डीफ़ॉर्मर का स्वामी है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | दिए गए ज्योमेट्री के लिए वजन सेट करता है, यह चैनल तक पहुँचे बिना टार्गेट के वजन को संशोधित करने का संक्षिप्त तरीका है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


नया उदाहरण प्रारंभ करता है [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) क्लास का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


नया उदाहरण प्रारंभ करता है [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) क्लास का।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेटिव प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


दिए गए ज्योमेट्री के लिए वजन प्राप्त करता है, यह चैनल तक पहुँचे बिना टार्गेट के वजन को संशोधित करने का संक्षिप्त तरीका है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | लक्षित ज्यामिति |

**Returns:**
double - वजन
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


इस डिफॉर्मर में शामिल सभी चैनल प्राप्त करता है

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - इस डिफॉर्मर में शामिल सभी चैनल
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


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


उस जियोमेट्री को प्राप्त करता है जो इस डीफ़ॉर्मर का स्वामी है

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है।

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
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


डायनामिक प्रॉपर्टी को हटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


दिए गए ज्योमेट्री के लिए वजन सेट करता है, यह चैनल तक पहुँचे बिना टार्गेट के वजन को संशोधित करने का संक्षिप्त तरीका है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | लक्षित ज्यामिति |
| मान | double | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

