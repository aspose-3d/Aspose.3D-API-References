---
title: "IVertexBuffer"
second_title: "Aspose.3D for Java API 参考"
description: "顶点缓冲区保存将发送到渲染管线的多边形顶点数据。"
type: docs
weight: 259
url: /zh/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

顶点缓冲区保存将发送到渲染管线的多边形顶点数据。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | 获取顶点声明 |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | 从 [TriMesh](../../com.aspose.threed/trimesh) 加载顶点数据 |
| [loadData(Object array)](#loadData-java.lang.Object-) | 从数组加载数据 |
| [loadData(long data, int size)](#loadData-long-int-) | 从给定位置加载数据 |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


获取顶点声明

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


从 [TriMesh](../../com.aspose.threed/trimesh) 加载顶点数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


从数组加载数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数组 | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


从给定位置加载数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | long |  |
| 大小 | int |  |

