---
title: StructuralMetadata
second_title: Aspose.3D for Java API Reference
description: यह क्लास केवल glTF में उपयोग किए जाने वाले EXT_structural_metadata के लिए समर्थन प्रदान करती है।
type: docs
weight: 180
url: /hi/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

यह क्लास EXT\\_structural\\_metadata के लिए समर्थन प्रदान करती है, जो केवल glTF में उपयोग होता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | वर्तमान मेटा डेटा को निर्दिष्ट दृश्य से संलग्न करें |
| [createClass(String name)](#createClass-java.lang.String-) | एक मेटा क्लास प्रकार बनाएं |
| [createEnum(String name)](#createEnum-java.lang.String-) | एक एनम प्रकार बनाएं |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | दिए गए मेटा क्लास प्रकार के साथ एक नई प्रॉपर्टी टेबल बनाएं |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | निर्दिष्ट दृश्य से संबंधित [StructuralMetadata](../../com.aspose.threed/structuralmetadata) प्राप्त करें। |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | क्लास परिभाषाएँ। |
| [getEnums()](#getEnums--) | एनम प्रकार परिभाषाएँ |
| [getPropertyTables()](#getPropertyTables--) | इस मेटाडेटा में प्रॉपर्टी टेबल्स। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructuralMetadata() {#StructuralMetadata--}
```
public StructuralMetadata()
```


### attach(Scene scene) {#attach-com.aspose.threed.Scene-}
```
public void attach(Scene scene)
```


वर्तमान मेटा डेटा को निर्दिष्ट दृश्य से संलग्न करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


एक मेटा क्लास प्रकार बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | क्लास का नाम |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


एक एनम प्रकार बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | enum प्रकार का नाम |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


दिए गए मेटा क्लास प्रकार के साथ एक नई प्रॉपर्टी टेबल बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी टेबल का नाम |
| clazz | [ClassType](../../com.aspose.threed/classtype) | नए प्रॉपर्टी टेबल का क्लास प्रकार |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
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
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


निर्दिष्ट दृश्य से संबंधित [StructuralMetadata](../../com.aspose.threed/structuralmetadata) प्राप्त करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | संरचनात्मक मेटाडेटा के लिए कौन सा दृश्य देखना है |

**Returns:**
[StructuralMetadata](../../com.aspose.threed/structuralmetadata) - A valid instance of [StructuralMetadata](../../com.aspose.threed/structuralmetadata) if its found in the scene, otherwise null returned
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClasses() {#getClasses--}
```
public HashMap<String,StructuralMetadata.ClassType> getClasses()
```


क्लास परिभाषाएँ।

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - क्लास परिभाषाएँ।
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


एनम प्रकार परिभाषाएँ

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - enum प्रकार की परिभाषाएँ।
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


इस मेटाडेटा में प्रॉपर्टी टेबल्स।

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - इस मेटाडेटा में प्रॉपर्टी टेबल्स।
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

