---
title: PolygonBuilder
second_title: Aspose.3D for Java API Reference
description: एक सहायक वर्ग जो बहुभुज बनाने के लिए है  Example
type: docs
weight: 133
url: /hi/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

पॉलीगॉन बनाने के लिए एक सहायक क्लास [Mesh](../../com.aspose.threed/mesh) **उदाहरण:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

के बराबर :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

यदि सभी सूचकांक उपयोग के लिए तैयार हैं, तो [Mesh](../../com.aspose.threed/mesh) को प्राथमिकता दी जाती है, अन्यथा [PolygonBuilder](../../com.aspose.threed/polygonbuilder) बेहतर विकल्प होगा।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | [PolygonBuilder](../../com.aspose.threed/polygonbuilder) क्लास का नया इंस्टेंस प्रारंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | पॉलीगॉन में एक वर्टेक्स इंडेक्स जोड़ता है |
| [begin()](#begin--) | एक नया पॉलीगॉन जोड़ना शुरू करता है |
| [end()](#end--) | पॉलीगॉन निर्माण समाप्त करता है |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


[PolygonBuilder](../../com.aspose.threed/polygonbuilder) क्लास का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | किस मेष पर पॉलीगॉन बनाना है। |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


पॉलीगॉन में एक वर्टेक्स इंडेक्स जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int |  |

### begin() {#begin--}
```
public void begin()
```


एक नया पॉलीगॉन जोड़ना शुरू करता है

### end() {#end--}
```
public void end()
```


पॉलीगॉन निर्माण समाप्त करता है

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

