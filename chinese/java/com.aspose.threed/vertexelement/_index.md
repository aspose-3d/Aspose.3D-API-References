---
title: "VertexElement"
second_title: "Aspose.3D for Java API 参考"
description: "顶点元素的基类。"
type: docs
weight: 207
url: /zh/java/com.aspose.threed/vertexelement/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.IIndexedVertexElement](../../com.aspose.threed/iindexedvertexelement)
```
public abstract class VertexElement implements IIndexedVertexElement
```

顶点元素的基类。顶点元素类型由 VertexElementType 标识。VertexElement 描述顶点元素如何映射到几何表面以及映射信息在内存中的排列方式。VertexElement 包含法线、UV 或其他类型的信息。
## 方法

| 方法 | 描述 |
| --- | --- |
| [clear()](#clear--) | 清除此顶点元素的所有数据。 |
| [clone(boolean withData)](#clone-boolean-) | 深度克隆顶点元素 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIndices()](#getIndices--) | 获取索引数据 |
| [getMappingMode()](#getMappingMode--) | 获取元素的映射方式。 |
| [getName()](#getName--) | 获取名称。 |
| [getReferenceMode()](#getReferenceMode--) | 获取元素的引用方式。 |
| [getVertexElementType()](#getVertexElementType--) | 获取 [VertexElement](../../com.aspose.threed/vertexelement) 的类型 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setIndices(int[] data)](#setIndices-int---) | 加载索引 |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | 设置元素的映射方式。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | 设置元素的引用方式。 |
| [toString()](#toString--) | 顶点元素的字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clear() {#clear--}
```
public abstract void clear()
```


清除此顶点元素的所有数据。

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


深度克隆顶点元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| withData | 布尔 | 克隆具有 direct 和 index 数组的顶点 |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
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
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


获取索引数据

**Returns:**
java.util.List<java.lang.Integer> - 索引数据
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


获取元素的映射方式。

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


获取元素的引用方式。

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


获取 [VertexElement](../../com.aspose.threed/vertexelement) 的类型

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




### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


加载索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


设置元素的映射方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


设置元素的引用方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | 新值 |

### toString() {#toString--}
```
public String toString()
```


顶点元素的字符串表示。

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

