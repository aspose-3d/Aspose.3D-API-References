---
title: VertexDeclaration
second_title: Aspose.3D for Java API Reference
description: कस्टम परिभाषित वर्टेक्स संरचना की घोषणा
type: docs
weight: 206
url: /hi/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

कस्टम परिभाषित वर्टेक्स की संरचना की घोषणा
## Constructors

| Constructor | विवरण |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | एक नया वर्टेक्स फ़ील्ड जोड़ें |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | एक नया वर्टेक्स फ़ील्ड जोड़ें |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | एक नया वर्टेक्स फ़ील्ड जोड़ें |
| [clear()](#clear--) | सभी फ़ील्ड साफ़ करें. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | इस इंस्टेंस की तुलना एक निर्दिष्ट ऑब्जेक्ट से करता है और उनके सापेक्ष मानों का संकेत लौटाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह इंस्टेंस और एक निर्दिष्ट ऑब्जेक्ट, जो भी एक [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) ऑब्जेक्ट होना चाहिए, समान मान रखते हैं या नहीं. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | एक [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) बनाएं जो एक [Geometry](../../com.aspose.threed/geometry) की लेआउट पर आधारित हो. |
| [get(int index)](#get-int-) | इंडेक्स द्वारा [VertexField](../../com.aspose.threed/vertexfield) प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | इस [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) में परिभाषित सभी फ़ील्ड की गिनती प्राप्त करता है |
| [getSealed()](#getSealed--) | एक [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) को सील किया जाएगा जब इसे [TriMesh](../../com.aspose.threed/trimesg) द्वारा उपयोग किया गया हो, आगे कोई संशोधन की अनुमति नहीं है. |
| [getSize()](#getSize--) | वर्टेक्स संरचना का बाइट में आकार. |
| [hashCode()](#hashCode--) | इस स्ट्रिंग के लिए हैश कोड लौटाता है। |
| [iterator()](#iterator--) | इस इंस्टेंस में सभी वर्टेक्स फ़ील्ड को पार करने के लिए एक इनेमरेटर प्राप्त करता है. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) का स्ट्रिंग प्रतिनिधित्व |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


एक नया वर्टेक्स फ़ील्ड जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dataType | int | वर्टेक्स फ़ील्ड का डेटा प्रकार |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | यह फ़ील्ड किस लिए उपयोग किया जाएगा |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


एक नया वर्टेक्स फ़ील्ड जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dataType | int | वर्टेक्स फ़ील्ड का डेटा प्रकार |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | यह फ़ील्ड किस लिए उपयोग किया जाएगा |
| सूचकांक | int | एक ही फ़ील्ड सेमांटिक के लिए सूचकांक, -1 स्वचालित निर्माण के लिए |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


एक नया वर्टेक्स फ़ील्ड जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dataType | int | वर्टेक्स फ़ील्ड का डेटा प्रकार |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | यह फ़ील्ड किस लिए उपयोग किया जाएगा |
| सूचकांक | int | एक ही फ़ील्ड सेमांटिक के लिए सूचकांक, -1 स्वचालित निर्माण के लिए |
| उपनाम | java.lang.String | फ़ील्ड का उपनाम |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


सभी फ़ील्ड साफ़ करें.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


इस इंस्टेंस की तुलना एक निर्दिष्ट ऑब्जेक्ट से करता है और उनके सापेक्ष मानों का संकेत लौटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह इंस्टेंस और एक निर्दिष्ट ऑब्जेक्ट, जो भी एक [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) ऑब्जेक्ट होना चाहिए, समान मान रखते हैं या नहीं.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


एक [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) बनाएं जो एक [Geometry](../../com.aspose.threed/geometry) की लेआउट पर आधारित हो.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | डबल प्रकार के बजाय फ्लोट का उपयोग करें |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


इंडेक्स द्वारा [VertexField](../../com.aspose.threed/vertexfield) प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


इस [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) में परिभाषित सभी फ़ील्ड की गिनती प्राप्त करता है

**Returns:**
int - इस [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) में परिभाषित सभी फ़ील्डों की गिनती
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


एक [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) को सील किया जाएगा जब इसे [TriMesh](../../com.aspose.threed/trimesg) द्वारा उपयोग किया गया हो, आगे कोई संशोधन की अनुमति नहीं है.

**Returns:**
boolean - एक [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) को सील किया जाएगा जब इसे [TriMesh](../../com.aspose.threed/trimesh) द्वारा उपयोग किया गया हो, आगे कोई संशोधन की अनुमति नहीं है।
### getSize() {#getSize--}
```
public int getSize()
```


वर्टेक्स संरचना का बाइट में आकार.

**Returns:**
int - वर्टेक्स संरचना का बाइट में आकार।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस स्ट्रिंग के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


इस इंस्टेंस में सभी वर्टेक्स फ़ील्ड को पार करने के लिए एक इनेमरेटर प्राप्त करता है.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - इटरेटर
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) का स्ट्रिंग प्रतिनिधित्व

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

