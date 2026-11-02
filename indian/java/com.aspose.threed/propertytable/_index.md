---
title: "StructuralMetadata.PropertyTable"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "प्रॉपर्टी तालिका।"
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
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | property table का कंस्ट्रक्टर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | property table में एक नया प्रॉपर्टी जोड़ें। |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | property table में एक नया प्रॉपर्टी जोड़ें। |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | वर्तमान property table को निर्दिष्ट उपयोगकर्ता डेटा से संलग्न करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | निर्दिष्ट उपयोगकर्ता डेटा से संलग्न property table निकालें। |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | इस property table की meta class। |
| [getName()](#getName--) | property table का नाम। |
| [getValue(String name)](#getValue-java.lang.String-) | निर्दिष्ट property नाम का मान प्राप्त करता है। |
| [getValues()](#getValues--) | property table के मान। |
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


property table का कंस्ट्रक्टर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | इस टेबल इंस्टेंस का नाम। |
| mclass | [ClassType](../../com.aspose.threed/classtype) | इस property table की meta class परिभाषा। |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


property table में एक नया प्रॉपर्टी जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | किस प्रॉपर्टी को मान के साथ जोड़ना है। |
| मान | java.lang.Object | मानों का एरे। |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


property table में एक नया प्रॉपर्टी जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propName | java.lang.String | किस प्रॉपर्टी को मान के साथ जोड़ना है। |
| मान | java.lang.Object | मानों का एरे। |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


वर्तमान property table को निर्दिष्ट उपयोगकर्ता डेटा से संलग्न करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


निर्दिष्ट उपयोगकर्ता डेटा से संलग्न property table निकालें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | उपयोगकर्ता डेटा जो एक property table से जुड़ा है। |

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


इस property table की meta class।

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


property table का नाम।

**Returns:**
java.lang.String - property table का नाम।
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


निर्दिष्ट property नाम का मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - प्रॉपर्टी मान या यदि न मिला तो null।
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


property table के मान।

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - property table के मान।
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

