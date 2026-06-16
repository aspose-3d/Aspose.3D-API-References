---
title: "VertexElementUV"
second_title: "Aspose.3D for Java API 参考"
description: "为指定的分量定义 UV 坐标。"
type: docs
weight: 220
url: /zh/java/com.aspose.threed/vertexelementuv/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementVector4](../../com.aspose.threed/vertexelementvector4)
```
public class VertexElementUV extends VertexElementVector4
```

定义指定组件的 UV 坐标。一个几何体可以拥有多个 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 元素，并且每个都有不同的 [TextureMapping](../../com.aspose.threed/texturemapping)。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VertexElementUV()](#VertexElementUV--) | 初始化 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 类的新实例。 |
| [VertexElementUV(TextureMapping textureMapping)](#VertexElementUV-com.aspose.threed.TextureMapping-) | 初始化 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addData(Iterable<Vector2> data)](#addData-java.lang.Iterable-com.aspose.threed.Vector2--) | 向 VertexElementUV.Data 添加一组 [Vector2](../../com.aspose.threed/vector2)。 |
| [addData2(Iterable<Vector3> data)](#addData2-java.lang.Iterable-com.aspose.threed.Vector3--) | 向 VertexElementUV.Data 添加一组 [Vector3](../../com.aspose.threed/vector3)。 |
| [clear()](#clear--) | 从 direct 和 index 数组中移除所有元素。 |
| [clone(boolean withData)](#clone-boolean-) | 深度克隆顶点元素 |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementVector4 target)](#copyTo-com.aspose.threed.VertexElementVector4-) | 将数据复制到指定的元素 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | 获取顶点数据 |
| [getIndices()](#getIndices--) | 获取索引数据 |
| [getMappingMode()](#getMappingMode--) | 获取元素的映射方式。 |
| [getName()](#getName--) | 获取名称。 |
| [getReferenceMode()](#getReferenceMode--) | 获取元素的引用方式。 |
| [getVertexElementType()](#getVertexElementType--) | 获取 [VertexElement](../../com.aspose.threed/vertexelement) 的类型 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Vector4[] data)](#setData-com.aspose.threed.Vector4---) | 加载数据 |
| [setIndices(int[] data)](#setIndices-int---) | 加载索引 |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | 设置元素的映射方式。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | 设置元素的引用方式。 |
| [toString()](#toString--) | 顶点元素的字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUV() {#VertexElementUV--}
```
public VertexElementUV()
```


初始化 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 类的新实例。默认的纹理映射类型是 [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE)。

### VertexElementUV(TextureMapping textureMapping) {#VertexElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV(TextureMapping textureMapping)
```


初始化 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | 纹理映射类型。 |

### addData(Iterable<Vector2> data) {#addData-java.lang.Iterable-com.aspose.threed.Vector2--}
```
public void addData(Iterable<Vector2> data)
```


向 VertexElementUV.Data 添加一组 [Vector2](../../com.aspose.threed/vector2)。这是一个快捷方式，此方法会将 [Vector2](../../com.aspose.threed/vector2) 转换为 [Vector4](../../com.aspose.threed/vector4)，其中 z 为 0，w 为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | java.lang.Iterable<com.aspose.threed.Vector2> |  |

### addData2(Iterable<Vector3> data) {#addData2-java.lang.Iterable-com.aspose.threed.Vector3--}
```
public void addData2(Iterable<Vector3> data)
```


向 VertexElementUV.Data 添加一组 [Vector3](../../com.aspose.threed/vector3)。这是一个快捷方式，此方法会将 [Vector3](../../com.aspose.threed/vector3) 转换为 [Vector4](../../com.aspose.threed/vector4)，其中 w 为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | java.lang.Iterable<com.aspose.threed.Vector3> |  |

### clear() {#clear--}
```
public void clear()
```


从 direct 和 index 数组中移除所有元素。

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
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| withDirect | 布尔 |  |
| withIndice | 布尔 |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### copyTo(VertexElementVector4 target) {#copyTo-com.aspose.threed.VertexElementVector4-}
```
public void copyTo(VertexElementVector4 target)
```


将数据复制到指定的元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [VertexElementVector4](../../com.aspose.threed/vertexelementvector4) | 目标。 |

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
### getData() {#getData--}
```
public List<Vector4> getData()
```


获取顶点数据

**Returns:**
java.util.List<com.aspose.threed.Vector4> - 顶点数据
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




### setData(Vector4[] data) {#setData-com.aspose.threed.Vector4---}
```
public void setData(Vector4[] data)
```


加载数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [Vector4\[\]](../../com.aspose.threed/vector4) |  |

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

