---
title: CreateElement
second_title: Aspose.3D for .NET API 参考
description: 创建具有指定类型的顶点元素并将其添加到几何图形中
type: docs
weight: 90
url: /zh/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

创建具有指定类型的顶点元素并将其添加到几何图形中。

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | VertexElementType | 顶点元素类型 |

### 返回值

创建的元素。

### 评论

如果类型是UV， 一个[`VertexElementUV`](../../vertexelementuv)纹理映射类型为Diffuse将被创建。

### 也可以看看

* class [VertexElement](../../vertexelement)
* enum [VertexElementType](../../vertexelementtype)
* class [Geometry](../../geometry)
* 命名空间 [Aspose.ThreeD.Entities](../../geometry)
* 部件 [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

创建具有指定类型的顶点元素并将其添加到几何图形中。

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | VertexElementType | 顶点元素类型 |
| mappingMode | MappingMode | 默认映射模式 |
| referenceMode | ReferenceMode | 默认参考模式 |

### 返回值

创建的元素。

### 评论

如果类型是UV， 一个[`VertexElementUV`](../../vertexelementuv)纹理映射类型为Diffuse将被创建。

### 也可以看看

* class [VertexElement](../../vertexelement)
* enum [VertexElementType](../../vertexelementtype)
* enum [MappingMode](../../mappingmode)
* enum [ReferenceMode](../../referencemode)
* class [Geometry](../../geometry)
* 命名空间 [Aspose.ThreeD.Entities](../../geometry)
* 部件 [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
