---
title: "StructuralMetadata.ClassType"
second_title: "Aspose.3D for Java API 参考"
description: "元数据中的类定义"
type: docs
weight: 10
url: /zh/java/com.aspose.threed/structuralmetadata.classtype/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.ClassType
```

元数据中的类定义
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties)](#ClassType-java.lang.String-java.lang.String-java.lang.String-java.util.ArrayList-com.aspose.threed.StructuralMetadata.Property--) | 类定义的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addProperty(StructuralMetadata.Property property)](#addProperty-com.aspose.threed.StructuralMetadata.Property-) | 向此类添加指定属性 |
| [addProperty(String name, StructuralMetadata.EnumType type, boolean array)](#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-) |  |
| [addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count)](#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) |  |
| [addProperty(String name, Class<?> type)](#addProperty-java.lang.String-java.lang.Class----) | 添加具有指定类型的新属性 |
| [addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array)](#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-) |  |
| [addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) |  |
| [addProperty(String name, String displayName, String description, Class<?> type)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----) |  |
| [addProperty(String name, String displayName, String description, Class<?> type, boolean normalized)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-) |  |
| [addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 类的描述 |
| [getDisplayName()](#getDisplayName--) | 类的名称，用于 UI 表示 |
| [getName()](#getName--) | 类的唯一名称 |
| [getProperties()](#getProperties--) | 此类中定义的属性。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | 类的描述 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | 类的名称，用于 UI 表示 |
| [toString()](#toString--) | 获取此实例的字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties) {#ClassType-java.lang.String-java.lang.String-java.lang.String-java.util.ArrayList-com.aspose.threed.StructuralMetadata.Property--}
```
public ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties)
```


类定义的构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 类的唯一名称 |
| displayName | java.lang.String | 类的名称，用于 UI 表示 |
| description | java.lang.String | 类的描述 |
| 属性 | java.util.ArrayList<com.aspose.threed.StructuralMetadata.Property> | 此类中定义的属性 |

### addProperty(StructuralMetadata.Property property) {#addProperty-com.aspose.threed.StructuralMetadata.Property-}
```
public void addProperty(StructuralMetadata.Property property)
```


向此类添加指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) |  |

### addProperty(String name, StructuralMetadata.EnumType type, boolean array) {#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-}
```
public StructuralMetadata.Property addProperty(String name, StructuralMetadata.EnumType type, boolean array)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 数组 | 布尔 |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count) {#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 数组 | 布尔 |  |
| 计数 | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, Class<?> type) {#addProperty-java.lang.String-java.lang.Class----}
```
public StructuralMetadata.Property addProperty(String name, Class<?> type)
```


添加具有指定类型的新属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 属性名称 |
| type | java.lang.Class<?> | 属性的数据类型 |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array) {#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 数组 | 布尔 |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 数组 | 布尔 |  |
| 计数 | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type, boolean normalized) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type, boolean normalized)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |
| normalized | 布尔 |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |
| normalized | 布尔 |  |
| 计数 | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


类的描述

**Returns:**
java.lang.String - 类的描述
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


类的名称，用于 UI 表示

**Returns:**
java.lang.String - 类的名称，用于 UI 表示
### getName() {#getName--}
```
public String getName()
```


类的唯一名称

**Returns:**
java.lang.String - 类的唯一名称
### getProperties() {#getProperties--}
```
public List<StructuralMetadata.Property> getProperties()
```


此类中定义的属性。

**Returns:**
java.util.List<com.aspose.threed.StructuralMetadata.Property> - 此类中定义的属性。
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


类的描述

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


类的名称，用于 UI 表示

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### toString() {#toString--}
```
public String toString()
```


获取此实例的字符串表示形式。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

