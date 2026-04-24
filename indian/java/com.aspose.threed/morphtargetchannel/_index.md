---
title: MorphTargetChannel
second_title: Aspose.3D for Java API Reference
description: एक MorphTargetChannel का उपयोग  द्वारा लक्ष्य ज्यामितियों को व्यवस्थित करने के लिए किया जाता है।
type: docs
weight: 107
url: /hi/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

एक MorphTargetChannel का उपयोग [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) द्वारा लक्ष्य ज्यामितियों को व्यवस्थित करने के लिए किया जाता है। FBX जैसे कुछ फ़ाइल स्वरूप समानांतर में कई चैनलों का समर्थन करते हैं। **Remarks:** वजन 0 और 1.0 के बीच है, और लक्ष्य के लिए डिफ़ॉल्ट वजन 0.0 है;
## Constructors

| Constructor | विवरण |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | नए [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) वर्ग का एक नया उदाहरण आरंभ करता है। |
| [MorphTargetChannel()](#MorphTargetChannel--) | नए [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) वर्ग का एक नया उदाहरण आरंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | मॉर्फ़ लक्ष्य के लिए डिफ़ॉल्ट वजन। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | निर्दिष्ट ज्यामिति के लिए वजन प्राप्त करता है |
| [getChannelWeight()](#getChannelWeight--) | इस चैनल का डीफ़ॉर्मर वजन प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getTargets()](#getTargets--) | चैनल से जुड़े सभी लक्ष्यों को प्राप्त करता है। |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | निर्दिष्ट लक्ष्य के लिए वजन प्राप्त करता है, यदि लक्ष्य इस चैनल से संबंधित नहीं है, तो डिफ़ॉल्ट मान 0 लौटाया जाता है। |
| [getWeights()](#getWeights--) | लक्ष्य ज्यामितियों के पूर्ण वजन मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | निर्दिष्ट ज्यामिति के लिए वजन सेट करता है |
| [setChannelWeight(double value)](#setChannelWeight-double-) | इस चैनल का डीफ़ॉर्मर वजन सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | निर्दिष्ट लक्ष्य के लिए वजन सेट करता है, डिफ़ॉल्ट मान 1 है, सीमा 0~1 के बीच होनी चाहिए |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | निर्दिष्ट लक्ष्य के लिए वजन सेट करता है, डिफ़ॉल्ट मान 1 है, सीमा 0~1 के बीच होनी चाहिए |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


नए [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


नए [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) वर्ग का एक नया उदाहरण आरंभ करता है।

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


मॉर्फ़ लक्ष्य के लिए डिफ़ॉल्ट वजन।

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


निर्दिष्ट ज्यामिति के लिए वजन प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | लक्ष्य ज्यामिति। |

**Returns:**
double - वजन
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


इस चैनल का डीफ़ॉर्मर वजन प्राप्त करता है। वजन 0.0 और 1.0 के बीच है।

**Returns:**
double - इस चैनल का डीफ़ॉर्मर वजन। वजन 0.0 और 1.0 के बीच है।
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


चैनल से जुड़े सभी लक्ष्यों को प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.Shape> - चैनल से जुड़े सभी लक्ष्य।
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


निर्दिष्ट लक्ष्य के लिए वजन प्राप्त करता है, यदि लक्ष्य इस चैनल से संबंधित नहीं है, तो डिफ़ॉल्ट मान 0 लौटाया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


लक्ष्य ज्यामितियों के पूर्ण वजन मान प्राप्त करता है।

**Returns:**
java.util.List<java.lang.Double> - लक्ष्य ज्यामितियों के पूर्ण वजन मान।
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


निर्दिष्ट ज्यामिति के लिए वजन सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | लक्ष्य ज्यामिति। |
| मान | double | नया मान |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


इस चैनल का डीफ़ॉर्मर वजन सेट करता है। वजन 0.0 और 1.0 के बीच है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


निर्दिष्ट लक्ष्य के लिए वजन सेट करता है, डिफ़ॉल्ट मान 1 है, सीमा 0~1 के बीच होनी चाहिए

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


निर्दिष्ट लक्ष्य के लिए वजन सेट करता है, डिफ़ॉल्ट मान 1 है, सीमा 0~1 के बीच होनी चाहिए

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| वजन | double |  |

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

