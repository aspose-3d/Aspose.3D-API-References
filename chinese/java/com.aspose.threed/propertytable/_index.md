---
title: "StructuralMetadata.PropertyTable"
second_title: "Aspose.3D for Java API 参考"
description: "属性表。"
type: docs
weight: 14
url: /zh/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

属性表。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | 属性表的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | 向属性表添加新属性。 |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | 向属性表添加新属性。 |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | 将当前属性表附加到指定的用户数据 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | 从指定的用户数据中提取已附加的属性表 |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | 此属性表的元类。 |
| [getName()](#getName--) | 属性表的名称。 |
| [getValue(String name)](#getValue-java.lang.String-) | 获取指定属性名称的值 |
| [getValues()](#getValues--) | 属性表的值。 |
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


属性表的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 此表实例的名称。 |
| mclass | [ClassType](../../com.aspose.threed/classtype) | 此属性表的元类定义 |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


向属性表添加新属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | 要添加的属性及其值 |
| 值 | java.lang.Object | 值数组 |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


向属性表添加新属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propName | java.lang.String | 要添加的属性及其值 |
| 值 | java.lang.Object | 值数组 |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


将当前属性表附加到指定的用户数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


从指定的用户数据中提取已附加的属性表

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | 与属性表关联的用户数据 |

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


此属性表的元类。

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


属性表的名称。

**Returns:**
java.lang.String - 属性表的名称。
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


获取指定属性名称的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 属性值，若未找到则为 null
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


属性表的值。

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - 属性表的值。
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

