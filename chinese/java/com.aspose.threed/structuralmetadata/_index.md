---
title: "StructuralMetadata"
second_title: "Aspose.3D for Java API 参考"
description: "此类提供对仅在 glTF 中使用的 EXT_structural_metadata 的支持。"
type: docs
weight: 180
url: /zh/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

此类提供对 EXT_structural_metadata 的支持，仅在 glTF 中使用。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | 将当前元数据附加到指定场景 |
| [createClass(String name)](#createClass-java.lang.String-) | 创建元类类型 |
| [createEnum(String name)](#createEnum-java.lang.String-) | 创建枚举类型 |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | 使用给定的元类类型创建新的属性表 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | 获取与指定场景关联的 [StructuralMetadata](../../com.aspose.threed/structuralmetadata)。 |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | 类定义。 |
| [getEnums()](#getEnums--) | 枚举类型定义 |
| [getPropertyTables()](#getPropertyTables--) | 此元数据中的属性表。 |
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


将当前元数据附加到指定场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


创建元类类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 类的名称 |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


创建枚举类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 枚举类型的名称 |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


使用给定的元类类型创建新的属性表

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 属性表的名称 |
| clazz | [ClassType](../../com.aspose.threed/classtype) | 新属性表的类类型 |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
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
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


获取与指定场景关联的 [StructuralMetadata](../../com.aspose.threed/structuralmetadata)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 要在何种场景中查找结构化元数据 |

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


类定义。

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - 类定义。
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


枚举类型定义

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - 枚举类型定义
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


此元数据中的属性表。

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - 此元数据中的属性表。
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

