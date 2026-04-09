---
title: StructuralMetadata.PropertyTable
second_title: Aspose.3D for Java API Reference
description: प्रॉपर्टी तालिका।
type: docs
weight: 14
url: /hi/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

प्रॉपर्टी तालिका।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | प्रॉपर्टी टेबल का कंस्ट्रक्टर। |
## Methods

| Method | विवरण |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | प्रॉपर्टी टेबल में एक नई प्रॉपर्टी जोड़ें। |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | प्रॉपर्टी टेबल में एक नई प्रॉपर्टी जोड़ें। |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | वर्तमान प्रॉपर्टी टेबल को निर्दिष्ट यूज़र डेटा से संलग्न करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | निर्दिष्ट यूज़र डेटा से संलग्न प्रॉपर्टी टेबल निकालें। |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | इस प्रॉपर्टी टेबल की मेटा क्लास। |
| [getName()](#getName--) | प्रॉपर्टी टेबल का नाम। |
| [getValue(String name)](#getValue-java.lang.String-) | निर्दिष्ट प्रॉपर्टी नाम का मान प्राप्त करता है। |
| [getValues()](#getValues--) | प्रॉपर्टी टेबल के मान। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PropertyTable(String name, StructuralMetadata.ClassType mclass) {#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public PropertyTable(String name, StructuralMetadata.ClassType mclass)
```


प्रॉपर्टी टेबल का कंस्ट्रक्टर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | इस टेबल इंस्टेंस का नाम। |
| mclass | [ClassType](../../com.aspose.threed/classtype) | इस प्रॉपर्टी टेबल की मेटा क्लास परिभाषा। |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


प्रॉपर्टी टेबल में एक नई प्रॉपर्टी जोड़ें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | कौन सी प्रॉपर्टी को मान के साथ जोड़ना है। |
| मान | java.lang.Object | मानों की एरे। |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


प्रॉपर्टी टेबल में एक नई प्रॉपर्टी जोड़ें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| propName | java.lang.String | कौन सी प्रॉपर्टी को मान के साथ जोड़ना है। |
| मान | java.lang.Object | मानों की एरे। |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


वर्तमान प्रॉपर्टी टेबल को निर्दिष्ट यूज़र डेटा से संलग्न करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


निर्दिष्ट यूज़र डेटा से संलग्न प्रॉपर्टी टेबल निकालें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | यूज़र डेटा जो एक प्रॉपर्टी टेबल से जुड़ा है। |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The associated property table instance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetaClass() {#getMetaClass--}
```
public StructuralMetadata.ClassType getMetaClass()
```


इस प्रॉपर्टी टेबल की मेटा क्लास।

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


प्रॉपर्टी टेबल का नाम।

**Returns:**
java.lang.String - प्रॉपर्टी टेबल का नाम।
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


निर्दिष्ट प्रॉपर्टी नाम का मान प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - प्रॉपर्टी मान या यदि न मिले तो null।
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


प्रॉपर्टी टेबल के मान।

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - प्रॉपर्टी टेबल के मान।
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

