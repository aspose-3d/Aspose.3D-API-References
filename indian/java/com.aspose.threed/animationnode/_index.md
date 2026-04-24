---
title: AnimationNode
second_title: Aspose.3D for Java API Reference
description: Aspose.3Ds एनीमेशन पदानुक्रम का समर्थन करता है, प्रत्येक एनीमेशन कई एनीमेशन और एनीमेशन की की-फ़्रेम परिभाषा द्वारा निर्मित हो सकता है।
type: docs
weight: 15
url: /hi/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D एनीमेशन पदानुक्रम का समर्थन करता है, प्रत्येक एनीमेशन कई एनीमेशन और एनीमेशन की की-फ़्रेम परिभाषा द्वारा निर्मित हो सकता है। [AnimationNode](../../com.aspose.threed/animationnode) समय के साथ एक प्रॉपर्टी मान के परिवर्तन को परिभाषित करता है, उदाहरण के लिए, एनीमेशन नोड का उपयोग नोड के परिवर्तन या अन्य [A3DObject](../../com.aspose.threed/a3dobject) ऑब्जेक्ट की संख्यात्मक प्रॉपर्टीज़ को नियंत्रित करने के लिए किया जा सकता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | नए [AnimationNode](../../com.aspose.threed/animationnode) वर्ग का एक नया उदाहरण आरंभ करता है। |
| [AnimationNode()](#AnimationNode--) | नए [AnimationNode](../../com.aspose.threed/animationnode) वर्ग का एक नया उदाहरण आरंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | प्रॉपर्टी डेटा टाइप के आधार पर एक BindPoint बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | लक्ष्य और नाम द्वारा बाइंड पॉइंट खोजता है। |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | दिए गए प्रॉपर्टी पर एनीमेशन बाइंड पॉइंट प्राप्त करता है। |
| [getBindPoints()](#getBindPoints--) | वर्तमान प्रॉपर्टी बाइंड पॉइंट्स प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | दिए गए प्रॉपर्टी पर कीफ़्रेम क्रम प्राप्त करता है। |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | दिए गए प्रॉपर्टी और चैनल पर कीफ़्रेम अनुक्रम प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getSubAnimations()](#getSubAnimations--) | वर्तमान एनीमेशन के अंतर्गत सब-एनीमेशन नोड्स प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


नए [AnimationNode](../../com.aspose.threed/animationnode) वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


नए [AnimationNode](../../com.aspose.threed/animationnode) वर्ग का एक नया उदाहरण आरंभ करता है।

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


प्रॉपर्टी डेटा टाइप के आधार पर एक BindPoint बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | ऑब्जेक्ट। |
| propName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


लक्ष्य और नाम द्वारा बाइंड पॉइंट खोजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | बाइंड पॉइंट का लक्ष्य खोजने के लिए। |
| name | java.lang.String | बाइंड पॉइंट का नाम खोजने के लिए। |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


दिए गए प्रॉपर्टी पर एनीमेशन बाइंड पॉइंट प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | किस ऑब्जेक्ट पर बाइंड पॉइंट बनाना है। |
| propName | java.lang.String | प्रॉपर्टी का नाम। |
| बनाएँ | boolean | यदि true सेट किया गया है तो बाइंड पॉइंट बनाएँ यदि वह मौजूद नहीं है। |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


वर्तमान प्रॉपर्टी बाइंड पॉइंट्स प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - वर्तमान प्रॉपर्टी बाइंड पॉइंट्स
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


दिए गए प्रॉपर्टी पर कीफ़्रेम क्रम प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | किस इंस्टेंस पर कीफ़्रेम अनुक्रम बनाना है। |
| propName | java.lang.String | प्रॉपर्टी का नाम। |
| बनाएँ | boolean | यदि true सेट किया गया है, तो अनुक्रम बनाएँ यदि वह मौजूद नहीं है। |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


दिए गए प्रॉपर्टी और चैनल पर कीफ़्रेम अनुक्रम प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | किस इंस्टेंस पर कीफ़्रेम अनुक्रम बनाना है। |
| propName | java.lang.String | प्रॉपर्टी का नाम। |
| channelName | java.lang.String | चैनल का नाम। |
| बनाएँ | boolean | यदि true सेट किया गया है तो एनीमेशन अनुक्रम बनाएँ यदि वह मौजूद नहीं है। |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


वर्तमान एनीमेशन के अंतर्गत सब-एनीमेशन नोड्स प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - वर्तमान एनीमेशन के अंतर्गत सब-एनीमेशन नोड्स
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

