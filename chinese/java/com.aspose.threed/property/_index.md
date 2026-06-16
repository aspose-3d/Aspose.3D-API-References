---
title: "StructuralMetadata.Property"
second_title: "Aspose.3D for Java API 参考"
description: "元数据类中的属性定义。"
type: docs
weight: 13
url: /zh/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

元数据类中的属性定义
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | 元数据属性的构造函数。 |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | 元数据属性的构造函数。 |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | 元数据属性的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 固定大小数组的数据计数。 |
| [getDescription()](#getDescription--) | 属性的描述。 |
| [getDisplayName()](#getDisplayName--) | 属性的名称，供 UI 用于显示。 |
| [getEnumType()](#getEnumType--) | 枚举类型。 |
| [getName()](#getName--) | 属性的唯一名称。 |
| [getNormalized()](#getNormalized--) | 数据是否已归一化。 |
| [getType()](#getType--) | 属性的数据类型。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | 固定大小数组的数据计数。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | 属性的描述。 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | 属性的名称，供 UI 用于显示。 |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | 枚举类型。 |
| [setNormalized(boolean value)](#setNormalized-boolean-) | 数据是否已归一化。 |
| [toString()](#toString--) | 获取此实例的字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


元数据属性的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 属性的唯一名称。 |
| displayName | java.lang.String | 属性的名称，供 UI 用于显示。 |
| description | java.lang.String | 属性的描述。 |
| type | java.lang.Class<?> | 属性的数据类型。 |
| normalized | 布尔 | 数据是否已归一化 |
| 计数 | java.lang.Integer | 固定大小数组的数据计数 |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


元数据属性的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 属性的唯一名称。 |
| displayName | java.lang.String | 属性的名称，供 UI 用于显示。 |
| description | java.lang.String | 属性的描述。 |
| type | [EnumType](../../com.aspose.threed/enumtype) | 属性的数据类型。 |
| 数组 | 布尔 | 每个属性值是数组还是标量 |
| 计数 | java.lang.Integer | 固定大小数组的数据计数 |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


元数据属性的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 属性的唯一名称。 |
| type | java.lang.Class<?> | 属性的数据类型。 |

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
### getCount() {#getCount--}
```
public Integer getCount()
```


固定大小数组的数据计数。

**Returns:**
java.lang.Integer - 固定大小数组的数据计数。
### getDescription() {#getDescription--}
```
public String getDescription()
```


属性的描述。

**Returns:**
java.lang.String - 属性的描述
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


属性的名称，供 UI 用于显示。

**Returns:**
java.lang.String - 属性的名称，用于 UI 表示。
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


枚举类型。

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


属性的唯一名称。

**Returns:**
java.lang.String - 属性的唯一名称
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


数据是否已归一化。

**Returns:**
boolean - 数据是否已归一化。
### getType() {#getType--}
```
public Class<?> getType()
```


属性的数据类型。

**Returns:**
java.lang.Class<?> - 属性的数据类型
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


固定大小数组的数据计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer | 新值 |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


属性的描述。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


属性的名称，供 UI 用于显示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


枚举类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | 新值 |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


数据是否已归一化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

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

