---
title: "Geometry.CreateElement"
second_title: "Aspose.3D for .NET API 参考"
description: "Geometry 方法。创建具有指定类型的顶点元素并将其添加到几何体中"
type: docs
weight: 90
url: /zh/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

创建具有指定类型的顶点元素并将其添加到几何体中。

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | VertexElementType | 顶点元素类型 |

### 返回值

已创建元素。

## 备注

如果类型是 UV，则会创建一个带有纹理映射类型为 Diffuse 的 [`VertexElementUV`](../../vertexelementuv/)。

### 另请参见

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

创建具有指定类型的顶点元素并将其添加到几何体中。

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | VertexElementType | 顶点元素类型 |
| mappingMode | MappingMode | 默认映射模式 |
| referenceMode | ReferenceMode | 默认引用模式 |

### 返回值

已创建元素。

## 备注

如果类型是 UV，则会创建一个带有纹理映射类型为 Diffuse 的 [`VertexElementUV`](../../vertexelementuv/)。

### 另请参见

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* enum [MappingMode](../../mappingmode/)
* enum [ReferenceMode](../../referencemode/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)


