---
title: "Matrix4.Inverse"
second_title: "Aspose.3D for .NET API 参考"
description: "Matrix4 方法。对该实例求逆"
type: docs
weight: 260
url: /zh/net/aspose.threed.utilities/matrix4/inverse/
---
## Matrix4.Inverse method

对该实例求逆。

```csharp
public Matrix4 Inverse()
```

### 返回值

逆矩阵4

## 示例

以下代码演示如何对矩阵求逆

```csharp
var t = Matrix4.Translate(0, 10, 9);
var mat = t.Inverse();
Console.WriteLine($"Inversed Matrix: {mat}");
```

### 另请参见

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


