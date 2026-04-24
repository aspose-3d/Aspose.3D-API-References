---
title: StructuralMetadata.Property
second_title: Aspose.3D for Java API Reference
description: मेटा डेटा क्लासों में प्रॉपर्टी परिभाषा।
type: docs
weight: 13
url: /hi/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

मेटा डेटा की कक्षाओं में प्रॉपर्टी परिभाषा
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | मेटा डेटा की प्रॉपर्टी का कंस्ट्रक्टर। |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | मेटा डेटा की प्रॉपर्टी का कंस्ट्रक्टर। |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | मेटा डेटा की प्रॉपर्टी का कंस्ट्रक्टर। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | स्थिर आकार की एरे के लिए डेटा की गिनती। |
| [getDescription()](#getDescription--) | प्रॉपर्टी का विवरण। |
| [getDisplayName()](#getDisplayName--) | प्रॉपर्टी का नाम, UI द्वारा प्रतिनिधित्व के लिए उपयोग किया जाता है। |
| [getEnumType()](#getEnumType--) | एन्यूम प्रकार। |
| [getName()](#getName--) | प्रॉपर्टी का अद्वितीय नाम। |
| [getNormalized()](#getNormalized--) | क्या डेटा सामान्यीकृत है। |
| [getType()](#getType--) | प्रॉपर्टी का डेटा प्रकार। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | स्थिर आकार की एरे के लिए डेटा की गिनती। |
| [setDescription(String value)](#setDescription-java.lang.String-) | प्रॉपर्टी का विवरण। |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | प्रॉपर्टी का नाम, UI द्वारा प्रतिनिधित्व के लिए उपयोग किया जाता है। |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | एन्यूम प्रकार। |
| [setNormalized(boolean value)](#setNormalized-boolean-) | क्या डेटा सामान्यीकृत है। |
| [toString()](#toString--) | इस इंस्टेंस का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


मेटा डेटा की प्रॉपर्टी का कंस्ट्रक्टर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का अद्वितीय नाम। |
| displayName | java.lang.String | प्रॉपर्टी का नाम, UI द्वारा प्रतिनिधित्व के लिए उपयोग किया जाता है। |
| description | java.lang.String | प्रॉपर्टी का विवरण। |
| type | java.lang.Class<?> | प्रॉपर्टी का डेटा प्रकार। |
| normalized | boolean | क्या डेटा सामान्यीकृत है |
| गणना | java.lang.Integer | स्थिर आकार के एरे के लिए डेटा की गिनती |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


मेटा डेटा की प्रॉपर्टी का कंस्ट्रक्टर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का अद्वितीय नाम। |
| displayName | java.lang.String | प्रॉपर्टी का नाम, UI द्वारा प्रतिनिधित्व के लिए उपयोग किया जाता है। |
| description | java.lang.String | प्रॉपर्टी का विवरण। |
| type | [EnumType](../../com.aspose.threed/enumtype) | प्रॉपर्टी का डेटा प्रकार। |
| एरे | boolean | क्या प्रत्येक प्रॉपर्टी मान एरे है या स्केलर |
| गणना | java.lang.Integer | स्थिर आकार के एरे के लिए डेटा की गिनती |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


मेटा डेटा की प्रॉपर्टी का कंस्ट्रक्टर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का अद्वितीय नाम। |
| type | java.lang.Class<?> | प्रॉपर्टी का डेटा प्रकार। |

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
### getCount() {#getCount--}
```
public Integer getCount()
```


स्थिर आकार की एरे के लिए डेटा की गिनती।

**Returns:**
java.lang.Integer - स्थिर आकार के एरे के लिए डेटा की गिनती।
### getDescription() {#getDescription--}
```
public String getDescription()
```


प्रॉपर्टी का विवरण।

**Returns:**
java.lang.String - प्रॉपर्टी का विवरण
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


प्रॉपर्टी का नाम, UI द्वारा प्रतिनिधित्व के लिए उपयोग किया जाता है।

**Returns:**
java.lang.String - प्रॉपर्टी का नाम, UI द्वारा प्रतिनिधित्व के लिए उपयोग किया जाता है।
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


एन्यूम प्रकार।

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


प्रॉपर्टी का अद्वितीय नाम।

**Returns:**
java.lang.String - प्रॉपर्टी का अद्वितीय नाम
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


क्या डेटा सामान्यीकृत है।

**Returns:**
boolean - क्या डेटा सामान्यीकृत है।
### getType() {#getType--}
```
public Class<?> getType()
```


प्रॉपर्टी का डेटा प्रकार।

**Returns:**
java.lang.Class<?> - प्रॉपर्टी का डेटा प्रकार
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


स्थिर आकार की एरे के लिए डेटा की गिनती।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer | नया मान |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


प्रॉपर्टी का विवरण।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


प्रॉपर्टी का नाम, UI द्वारा प्रतिनिधित्व के लिए उपयोग किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


एन्यूम प्रकार।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | नया मान |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


क्या डेटा सामान्यीकृत है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### toString() {#toString--}
```
public String toString()
```


इस इंस्टेंस का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है।

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

