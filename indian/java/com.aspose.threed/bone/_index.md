---
title: बोन
second_title: Aspose.3D for Java API Reference
description: एक बोन ज्योमेट्री के कंट्रोल पॉइंट के उपसमुच्चय को परिभाषित करता है और प्रत्येक कंट्रोल पॉइंट के लिए ब्लेंड वेट निर्धारित करता है।
type: docs
weight: 20
url: /hi/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

एक बोन ज्योमेट्री के कंट्रोल पॉइंट के उपसमुच्चय को परिभाषित करता है, और प्रत्येक कंट्रोल पॉइंट के लिए ब्लेंड वेट निर्धारित करता है। [Bone](../../com.aspose.threed/bone) ऑब्जेक्ट को सीधे उपयोग नहीं किया जा सकता, एक [SkinDeformer](../../com.aspose.threed/skindeformer) इंस्टेंस का उपयोग ज्योमेट्री को विकृत करने के लिए किया जाता है, और [SkinDeformer](../../com.aspose.threed/skindeformer) कई बोंस के सेट के साथ आता है, प्रत्येक बोन एक नोड से जुड़ा होता है। नोट: एक ज्योमेट्री का कंट्रोल पॉइंट एक से अधिक बोंस से बंधा हो सकता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | [Bone](../../com.aspose.threed/bone) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Bone()](#Bone--) | [Bone](../../com.aspose.threed/bone) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [get(int index)](#get-int-) | निर्दिष्ट कंट्रोल पॉइंट का ब्लेंड वेट प्राप्त करता है |
| [getBoneTransform()](#getBoneTransform--) | बोन का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | हड्डी का लिंक मोड यह दर्शाता है कि हड्डी को पदानुक्रमित संरचना में उसके पैरेंट हड्डी से कैसे जोड़ा या लिंक किया जाता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getNode()](#getNode--) | नोड प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getTransform()](#getTransform--) | हड्डी को शामिल करने वाले नोड का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है। |
| [getWeight(int index)](#getWeight-int-) | निर्दिष्ट इंडेक्स द्वारा नियंत्रक बिंदु के लिए वजन प्राप्त करता है |
| [getWeightCount()](#getWeightCount--) | वजन की गिनती प्राप्त करता है, यह स्वचालित रूप से [setWeight](../../com.aspose.threed/bone\#setWeight) द्वारा विस्तारित किया जाता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [set(int index, double value)](#set-int-double-) | निर्दिष्ट नियंत्रक बिंदु का ब्लेंड वजन सेट करता है |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | हड्डी का ट्रांसफ़ॉर्म मैट्रिक्स सेट करता है। |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | हड्डी का लिंक मोड यह दर्शाता है कि हड्डी को पदानुक्रमित संरचना में उसके पैरेंट हड्डी से कैसे जोड़ा या लिंक किया जाता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | नोड सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | हड्डी को शामिल करने वाले नोड का ट्रांसफ़ॉर्म मैट्रिक्स सेट करता है। |
| [setWeight(int index, double weight)](#setWeight-int-double-) | इंडेक्स द्वारा निर्दिष्ट नियंत्रक बिंदु के लिए वजन सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


[Bone](../../com.aspose.threed/bone) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |

### Bone() {#Bone--}
```
public Bone()
```


[Bone](../../com.aspose.threed/bone) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

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
### get(int index) {#get-int-}
```
public double get(int index)
```


निर्दिष्ट कंट्रोल पॉइंट का ब्लेंड वेट प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int | वजन का इंडेक्स |

**Returns:**
double - वजन
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


बोन का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


हड्डी का लिंक मोड यह दर्शाता है कि हड्डी को पदानुक्रमित संरचना में उसके पैरेंट हड्डी से कैसे जोड़ा या लिंक किया जाता है।

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getNode() {#getNode--}
```
public Node getNode()
```


नोड प्राप्त करता है। हड्डी नोड वह हड्डी है जिससे त्वचा जुड़ी होती है, [SkinDeformer](../../com.aspose.threed/skindeformer) हड्डी नोड का उपयोग नियंत्रक बिंदुओं के विस्थापन को प्रभावित करने के लिए करेगा। हड्डी नोड आमतौर पर एक [Skeleton](../../com.aspose.threed/skeleton) से जुड़ा होता है, लेकिन यह आवश्यक नहीं है। जुड़ा हुआ [Skeleton](../../com.aspose.threed/skeleton) आमतौर पर DCC सॉफ़्टवेयर द्वारा उपयोगकर्ता को कंकाल दिखाने के लिए उपयोग किया जाता है।

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


हड्डी को शामिल करने वाले नोड का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


निर्दिष्ट इंडेक्स द्वारा नियंत्रक बिंदु के लिए वजन प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int | नियंत्रक बिंदु का इंडेक्स |

**Returns:**
double - निर्दिष्ट इंडेक्स पर वजन, या यदि इंडेक्स अमान्य है तो 0
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


वजन की गिनती प्राप्त करता है, यह स्वचालित रूप से [setWeight](../../com.aspose.threed/bone\#setWeight) द्वारा विस्तारित किया जाता है

**Returns:**
int - वजन की गिनती, यह स्वचालित रूप से [setWeight](../../com.aspose.threed/bone\#setWeight) द्वारा विस्तारित किया जाता है
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


निर्दिष्ट नियंत्रक बिंदु का ब्लेंड वजन सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int | वजन का इंडेक्स |
| मान | double | नया मान |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


हड्डी का ट्रांसफ़ॉर्म मैट्रिक्स सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | नया मान |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


हड्डी का लिंक मोड यह दर्शाता है कि हड्डी को पदानुक्रमित संरचना में उसके पैरेंट हड्डी से कैसे जोड़ा या लिंक किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


नोड सेट करता है। हड्डी नोड वह हड्डी है जिससे त्वचा जुड़ी होती है, [SkinDeformer](../../com.aspose.threed/skindeformer) हड्डी नोड का उपयोग नियंत्रक बिंदुओं के विस्थापन को प्रभावित करने के लिए करेगा। हड्डी नोड आमतौर पर एक [Skeleton](../../com.aspose.threed/skeleton) से जुड़ा होता है, लेकिन यह आवश्यक नहीं है। जुड़ा हुआ [Skeleton](../../com.aspose.threed/skeleton) आमतौर पर DCC सॉफ़्टवेयर द्वारा उपयोगकर्ता को कंकाल दिखाने के लिए उपयोग किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


हड्डी को शामिल करने वाले नोड का ट्रांसफ़ॉर्म मैट्रिक्स सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | नया मान |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


इंडेक्स द्वारा निर्दिष्ट नियंत्रक बिंदु के लिए वजन सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int | नियंत्रक बिंदु का इंडेक्स |
| वजन | double | नया वजन |

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

