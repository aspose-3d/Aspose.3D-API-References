---
title: Mesh.op_Subtraction
second_title: Aspose.3D for .NET API 参考手册
description: Mesh 方法。计算两个网格的差集
type: docs
weight: 150
url: /zh/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

计算两个网格的差集

```csharp
public static Mesh operator -(Mesh a, Mesh b)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | 网格 | 第一个网格 |
| b | 网格 | 第二个网格 |

### 返回值

结果网格

## 示例

以下代码展示了如何计算两个网格的差异：

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 - box2;
```

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


