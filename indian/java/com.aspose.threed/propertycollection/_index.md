---
title: PropertyCollection
second_title: Aspose.3D for Java API Reference
description: प्रॉपर्टीज़ का संग्रह
type: docs
weight: 140
url: /hi/java/com.aspose.threed/propertycollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class PropertyCollection implements Iterable<Property>
```

प्रॉपर्टीज़ का संग्रह
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String property)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [get(int idx)](#get-int-) | इंडेक्स द्वारा प्रॉपर्टी प्राप्त करता है। |
| [get(String property)](#get-java.lang.String-) | प्रॉपर्टी नाम द्वारा प्रॉपर्टी का मान प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [set(String property, Object value)](#set-java.lang.String-java.lang.Object-) | प्रॉपर्टी नाम द्वारा प्रॉपर्टी का मान सेट करता है। |
| [size()](#size--) | घोषित प्रॉपर्टियों की गिनती प्राप्त करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### findProperty(String property) {#findProperty-java.lang.String-}
```
public Property findProperty(String property)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेटिव प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(int idx) {#get-int-}
```
public Property get(int idx)
```


इंडेक्स द्वारा प्रॉपर्टी प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | प्रॉपर्टी का 0-आधारित इंडेक्स |

**Returns:**
[Property](../../com.aspose.threed/property) - the property by index.
### get(String property) {#get-java.lang.String-}
```
public Object get(String property)
```


प्रॉपर्टी नाम द्वारा प्रॉपर्टी का मान प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी का नाम |

**Returns:**
java.lang.Object - प्रॉपर्टी का मान
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<Property> iterator()
```


एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**Returns:**
java.util.Iterator<com.aspose.threed.Property>
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


डायनामिक प्रॉपर्टी को हटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### set(String property, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String property, Object value)
```


प्रॉपर्टी नाम द्वारा प्रॉपर्टी का मान सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी का नाम |
| मान | java.lang.Object | नया मान |

### size() {#size--}
```
public int size()
```


घोषित प्रॉपर्टियों की गिनती प्राप्त करता है।

**Returns:**
int - घोषित गुणों की गिनती।
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

