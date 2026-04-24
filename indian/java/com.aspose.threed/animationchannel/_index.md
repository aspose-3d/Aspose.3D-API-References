---
title: AnimationChannel
second_title: Aspose.3D for Java API Reference
description: एक चैनल प्रॉपर्टी के कंपोनेंट फ़ील्ड को कीफ़्रेम अनुक्रमों के सेट से मैप करता है।
type: docs
weight: 13
url: /hi/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

एक चैनल प्रॉपर्टी के कंपोनेंट फ़ील्ड को कीफ़्रेम सीक्वेंस के सेट से मैप करता है।
## Methods

| Method | विवरण |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | निर्दिष्ट मान के साथ एक नया कुंजी फ़्रेम बनाएं |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | निर्दिष्ट मान के साथ एक नया कुंजी फ़्रेम बनाएं |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBindPoint()](#getBindPoint--) | उस प्रॉपर्टी बाइंड पॉइंट को प्राप्त करता है जो इस कर्व का स्वामित्व रखता है |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | कंपोनेंट फ़ील्ड का प्रकार प्राप्त करता है। |
| [getDefaultValue()](#getDefaultValue--) | चैनल का डिफ़ॉल्ट मान प्राप्त करता है। |
| [getKeyFrames()](#getKeyFrames--) | इस कर्व के कुंजी फ़्रेम प्राप्त करता है। |
| [getKeyframeSequence()](#getKeyframeSequence--) | इस चैनल के भीतर संबंधित कीफ़्रेम अनुक्रम प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getPostBehavior()](#getPostBehavior--) | पोस्ट व्यवहार प्राप्त करता है जो दर्शाता है कि अंतिम कुंजी फ़्रेम के बाद नमूना मान क्या होना चाहिए। |
| [getPreBehavior()](#getPreBehavior--) | प्रि व्यवहार प्राप्त करता है जो दर्शाता है कि पहले कुंजी फ़्रेम से पहले नमूना मान क्या होना चाहिए। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | सभी कुंजी फ़्रेमों को पार करने के लिए एन्यूमरेटर प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [reset()](#reset--) | सभी कुंजी फ़्रेमों को हटाता है और पोस्ट/प्रि व्यवहारों को रीसेट करता है। |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | चैनल का डिफ़ॉल्ट मान सेट करता है। |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | इस चैनल के भीतर संबंधित कीफ़्रेम अनुक्रम प्राप्त करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


निर्दिष्ट मान के साथ एक नया कुंजी फ़्रेम बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| समय | double | समय स्थिति (सेकंड में मापी गई) |
| मान | फ़्लोट | इस समय स्थिति पर मान |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


निर्दिष्ट मान के साथ एक नया कुंजी फ़्रेम बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| समय | double | समय स्थिति (सेकंड में मापी गई) |
| मान | फ़्लोट | इस समय स्थिति पर मान |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | इस कुंजी फ़्रेम का इंटरपोलेशन प्रकार |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


उस प्रॉपर्टी बाइंड पॉइंट को प्राप्त करता है जो इस कर्व का स्वामित्व रखता है

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


कंपोनेंट फ़ील्ड का प्रकार प्राप्त करता है।

**Returns:**
java.lang.Class<?> - कंपोनेंट फ़ील्ड का प्रकार
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


चैनल का डिफ़ॉल्ट मान प्राप्त करता है। यदि किसी चैनल से कोई कीफ़्रेम अनुक्रम जुड़ा नहीं है, तो एनीमेशन मूल्यांकन के दौरान डिफ़ॉल्ट मान उपयोग किया जाएगा। एक वास्तविक परिदृश्य: एनीमेशन केवल एक नोड के x निर्देशांक को एनीमेट करता है, y और z नहीं बदले जाते, तब पूर्ण ट्रांसलेशन मूल्यांकन के दौरान डिफ़ॉल्ट मान उपयोग किया जाएगा।

**Returns:**
java.lang.Object - चैनल का डिफ़ॉल्ट मान। यदि किसी चैनल से कोई कीफ़्रेम अनुक्रम जुड़ा नहीं है, तो एनीमेशन मूल्यांकन के दौरान डिफ़ॉल्ट मान उपयोग किया जाएगा। एक वास्तविक परिदृश्य: एनीमेशन केवल एक नोड के x निर्देशांक को एनीमेट करता है, y और z नहीं बदले जाते, तब पूर्ण ट्रांसलेशन मूल्यांकन के दौरान डिफ़ॉल्ट मान उपयोग किया जाएगा।
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


इस कर्व के कुंजी फ़्रेम प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - इस कर्व के कुंजी फ़्रेम।
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


इस चैनल के भीतर संबंधित कीफ़्रेम अनुक्रम प्राप्त करता है।

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


पोस्ट व्यवहार प्राप्त करता है जो दर्शाता है कि अंतिम कुंजी फ़्रेम के बाद नमूना मान क्या होना चाहिए।

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


प्रि व्यवहार प्राप्त करता है जो दर्शाता है कि पहले कुंजी फ़्रेम से पहले नमूना मान क्या होना चाहिए।

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


सभी कुंजी फ़्रेमों को पार करने के लिए एन्यूमरेटर प्राप्त करता है।

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
### reset() {#reset--}
```
public void reset()
```


सभी कुंजी फ़्रेमों को हटाता है और पोस्ट/प्रि व्यवहारों को रीसेट करता है।

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


चैनल का डिफ़ॉल्ट मान सेट करता है। यदि किसी चैनल से कोई कीफ़्रेम अनुक्रम जुड़ा नहीं है, तो एनीमेशन मूल्यांकन के दौरान डिफ़ॉल्ट मान उपयोग किया जाएगा। एक वास्तविक परिदृश्य: एनीमेशन केवल एक नोड के x निर्देशांक को एनीमेट करता है, y और z नहीं बदले जाते, तब पूर्ण ट्रांसलेशन मूल्यांकन के दौरान डिफ़ॉल्ट मान उपयोग किया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.Object | नया मान |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


इस चैनल के भीतर संबंधित कीफ़्रेम अनुक्रम प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | नया मान |

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

