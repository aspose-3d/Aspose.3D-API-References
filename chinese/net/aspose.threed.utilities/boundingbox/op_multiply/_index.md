---
title: "BoundingBox.op_Multiply"
second_title: "Aspose.3D for .NET API 参考"
description: "BoundingBox 方法。运算符重载用于乘法，新包围盒的最小和最大角点将通过矩阵进行变换"
type: docs
weight: 170
url: /zh/net/aspose.threed.utilities/boundingbox/op_multiply/
---
## BoundingBox Multiply operator

乘法运算符重载，新边界框的最小和最大角将被矩阵变换。

```csharp
public static BoundingBox operator *(BoundingBox bbox, Matrix4 mat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bbox | BoundingBox | 输入的包围盒。 |
| 矩阵 | Matrix4 | 用于变换包围盒角点的矩阵 |

### 返回值

包围盒与变换矩阵的乘积。

### 另请参见

* struct [Matrix4](../../matrix4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


