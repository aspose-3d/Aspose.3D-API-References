---
title: BindPoint
second_title: Aspose.3D for Java API Reference
description: आमतौर पर एक ऑब्जेक्ट की प्रॉपर्टी पर बनाया जाता है, कुछ प्रॉपर्टी प्रकारों में कई घटक फ़ील्ड होते हैं (जैसे Vector3 फ़ील्ड), जो प्रत्येक घटक फ़ील्ड के लिए एक चैनल उत्पन्न करेंगे और फ़ील्ड को एक या अधिक कीफ़्रेम सीक्वेंस इंस्टेंस के माध्यम से चैनलों से जोड़ते हैं।
type: docs
weight: 19
url: /hi/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

एक [BindPoint](../../com.aspose.threed/bindpoint) आमतौर पर एक ऑब्जेक्ट की प्रॉपर्टी पर बनाया जाता है, कुछ प्रॉपर्टी प्रकारों में कई घटक फ़ील्ड होते हैं (जैसे Vector3 फ़ील्ड), [BindPoint](../../com.aspose.threed/bindpoint) प्रत्येक घटक फ़ील्ड के लिए चैनल उत्पन्न करेगा और फ़ील्ड को एक या अधिक कीफ़्रेम सीक्वेंस इंस्टेंस(स) के माध्यम से चैनलों से जोड़ता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | [BindPoint](../../com.aspose.threed/bindpoint) क्लास का नया इंस्टेंस आरंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | निर्दिष्ट चैनल प्रॉपर्टी जोड़ता है। |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | निर्दिष्ट चैनल प्रॉपर्टी जोड़ता है। |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | कीफ़्रेम सीक्वेंस को निर्दिष्ट चैनल से बाइंड करें |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | एक नया कर्व बनाता है और इसे कर्व मैपिंग के पहले चैनल से जोड़ता है |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [get(String channelName)](#get-java.lang.String-) | दिए गए नाम से चैनल प्राप्त करता है |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | दिए गए नाम से चैनल प्राप्त करता है |
| [getChannelsCount()](#getChannelsCount--) | इस एनीमेशन कर्व मैपिंग में परिभाषित प्रॉपर्टी चैनलों की कुल संख्या प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | निर्दिष्ट चैनल में पहला कीफ़्रेम सीक्वेंस प्राप्त करता है |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty()](#getProperty--) | CurveMapping से जुड़ी प्रॉपर्टी प्राप्त करता है |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [resetChannels()](#resetChannels--) | इस एनीमेशन कर्व मैपिंग के प्रॉपर्टी चैनलों को खाली करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | CurveMapping से जुड़ी प्रॉपर्टी प्राप्त करता है |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) | ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


[BindPoint](../../com.aspose.threed/bindpoint) क्लास का नया इंस्टेंस आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | एनीमेशन को सम्मिलित करने वाला सीन। |
| prop | [Property](../../com.aspose.threed/property) | प्रॉपर्टी। |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


निर्दिष्ट चैनल प्रॉपर्टी जोड़ता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |
| type | java.lang.Class<?> | टाइप। |
| मान | java.lang.Object | वैल्यू। |

**Returns:**
बूलियन - true, यदि चैनल जोड़ा गया हो, अन्यथा false।
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


निर्दिष्ट चैनल प्रॉपर्टी जोड़ता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |
| मान | java.lang.Object | वैल्यू। |

**Returns:**
बूलियन - true, यदि चैनल जोड़ा गया हो, अन्यथा false।
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


कीफ़्रेम सीक्वेंस को निर्दिष्ट चैनल से बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| channelName | java.lang.String | कौन से चैनल से कीफ़्रेम सीक्वेंस बंधेगा |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | बाइंड करने के लिए कीफ़्रेम सीक्वेंस |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


एक नया कर्व बनाता है और इसे कर्व मैपिंग के पहले चैनल से जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नए सीक्वेंस का नाम। |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


दिए गए नाम से चैनल प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| channelName | java.lang.String | चैनल नाम |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


दिए गए नाम से चैनल प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| channelName | java.lang.String | खोजने के लिए चैनल नाम |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


इस एनीमेशन कर्व मैपिंग में परिभाषित प्रॉपर्टी चैनलों की कुल संख्या प्राप्त करता है।

**Returns:**
int - चैनलों की संख्या।
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


निर्दिष्ट चैनल में पहला कीफ़्रेम सीक्वेंस प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| channelName | java.lang.String | खोजने के लिए चैनल नाम |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


CurveMapping से जुड़ी प्रॉपर्टी प्राप्त करता है

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


इस एनीमेशन कर्व मैपिंग के प्रॉपर्टी चैनलों को खाली करता है।

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


CurveMapping से जुड़ी प्रॉपर्टी प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | नया मान |

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


ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है

**Returns:**
java.lang.String - ऑब्जेक्ट स्ट्रिंग
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

