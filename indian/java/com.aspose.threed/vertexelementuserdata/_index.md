---
title: VertexElementUserData
second_title: Aspose.3D for Java API Reference
description: निर्दिष्ट घटकों के लिए कस्टम उपयोगकर्ता डेटा को परिभाषित करता है।
type: docs
weight: 221
url: /hi/java/com.aspose.threed/vertexelementuserdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementUserData extends VertexElement
```

निर्दिष्ट घटकों के लिए कस्टम उपयोगकर्ता डेटा परिभाषित करता है। आमतौर पर यह विशेष उद्देश्य के लिए एप्लिकेशन-विशिष्ट डेटा होता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [VertexElementUserData()](#VertexElementUserData--) | एक नया उदाहरण इनिशियलाइज़ करता है [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) क्लास का। |
## Methods

| Method | विवरण |
| --- | --- |
| [clear()](#clear--) | इस वर्टेक्स तत्व से सभी डेटा साफ़ करता है। |
| [clone(boolean withData)](#clone-boolean-) | वर्टेक्स तत्व की गहरी क्लोन बनाता है। |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | इस तत्व में संलग्न उपयोगकर्ता डेटा |
| [getIndices()](#getIndices--) | इंडेक्स डेटा प्राप्त करता है। |
| [getMappingMode()](#getMappingMode--) | तत्व कैसे मैप किया गया है, यह प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getReferenceMode()](#getReferenceMode--) | तत्व कैसे संदर्भित किया गया है, यह प्राप्त करता है। |
| [getVertexElementType()](#getVertexElementType--) | [VertexElement](../../com.aspose.threed/vertexelement) का प्रकार प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Object value)](#setData-java.lang.Object-) | इस तत्व में संलग्न उपयोगकर्ता डेटा |
| [setIndices(int[] data)](#setIndices-int---) | इंडेक्स लोड करें |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | तत्व कैसे मैप किया गया है, यह सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | तत्व कैसे संदर्भित किया गया है, यह सेट करता है। |
| [toString()](#toString--) | वर्टेक्स तत्व का स्ट्रिंग प्रतिनिधित्व। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUserData() {#VertexElementUserData--}
```
public VertexElementUserData()
```


एक नया उदाहरण इनिशियलाइज़ करता है [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) क्लास का।

### clear() {#clear--}
```
public void clear()
```


इस वर्टेक्स तत्व से सभी डेटा साफ़ करता है।

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


वर्टेक्स तत्व की गहरी क्लोन बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| withData | boolean | डायरेक्ट और इंडेक्स एरे के साथ वर्टेक्स को क्लोन करें। |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public Object getData()
```


इस तत्व में संलग्न उपयोगकर्ता डेटा

**Returns:**
java.lang.Object - इस तत्व में संलग्न उपयोगकर्ता डेटा
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


इंडेक्स डेटा प्राप्त करता है।

**Returns:**
java.util.List<java.lang.Integer> - इंडेक्स डेटा
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


तत्व कैसे मैप किया गया है, यह प्राप्त करता है।

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


तत्व कैसे संदर्भित किया गया है, यह प्राप्त करता है।

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


[VertexElement](../../com.aspose.threed/vertexelement) का प्रकार प्राप्त करता है।

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
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




### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


इस तत्व में संलग्न उपयोगकर्ता डेटा

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.Object | नया मान |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


इंडेक्स लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डेटा | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


तत्व कैसे मैप किया गया है, यह सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


तत्व कैसे संदर्भित किया गया है, यह सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | नया मान |

### toString() {#toString--}
```
public String toString()
```


वर्टेक्स तत्व का स्ट्रिंग प्रतिनिधित्व।

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

